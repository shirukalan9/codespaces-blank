# TEESimulator

This workspace contains the TEESimulator Android project in [`TEESimulator/`](TEESimulator/).
TEESimulator routes selected apps through a software KeyMint running inside the Android
keystore daemon while leaving other keys on the device's hardware-backed KeyMint.

## Documentation

See [`TEESimulator/README.md`](TEESimulator/README.md) for project details, requirements,
installation, configuration, and build instructions.

## Quick start

The project requires Android 10 or newer, a 64-bit device, and a supported root manager.
To build the release module, install the Android SDK and NDK, then run from `TEESimulator/`:

```sh
./gradlew zipRelease
```

The flashable release archive is written under `TEESimulator/out/`.
