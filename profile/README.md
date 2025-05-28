## What is Mopro?

Mopro is a toolkit for ZK app development on mobile. Mopro makes client-side proving on mobile simple.

It offers the following features:

-   Directly imports and executes **any Rust crate**.
-   Exports bindings for **iOS (Swift)** and **Android (Kotlin)**.
-   Generates **WebAssembly (WASM)** with Rayon for browser compatibility.
-   Provides project templates for
    -   **[Swift in Xcode](https://developer.apple.com/xcode/)**
    -   **[Kotlin in Android Studio](https://developer.android.com/kotlin)**
    -   **[React Native](https://reactnative.dev/)**
    -   **[Flutter](https://flutter.dev/)**
    -   **Web development**

## To learn more

-   📱 Main Github Repo: https://github.com/zkmopro/mopro
-   📚 Documentation: https://zkmopro.org
-   ⚒️ Getting Started: https://zkmopro.org/docs/getting-started
-   💡 Projects you can build: https://zkmopro.org/docs/projects
-   🎥 Demo App: https://github.com/zkmopro/android-benchmark-app
-   🏎️ Benchmark: https://zkmopro.org/docs/performance
-   💬 Community and Talks: https://zkmopro.org/docs/community
-   📰 Blog: https://zkmopro.org/blog

## What we also offer

### Circom

-   [circom-witnesscalc](https://github.com/zkmopro/circom-witnesscalc): A fork of [circom-witnesscalc](https://github.com/iden3/circom-witnesscalc)
-   [witnesscalc_adapter](https://github.com/zkmopro/witnesscalc_adapter): A Rust wrapper for [witnesscalc](https://github.com/0xPolygonID/witnesscalc).
-   [rust-witness](https://github.com/chancehudson/rust-witness): Alternative implementation of witness generation.
-   [rust-rapidsnark](https://github.com/zkmopro/rust-rapidsnark): A Rust wrapper for [Rapidsnark](https://github.com/iden3/rapidsnark).
-   [ark-zkey](https://github.com/zkmopro/ark-zkey): Compresses and decompresses zkey files for Arkworks.
-   [circom-prover](https://github.com/zkmopro/mopro/tree/main/circom-prover): A high-performance Rust-based Circom prover with seamless cross-platform support.

### Noir

-   [noir-rs](https://github.com/zkmopro/noir-rs): Rust wrapper for Noir circuits integration.
-   [Pre-built barretenberg libraries](https://bb.zkmopro.org/): Pre-built binaries: `https://bb.zkmopro.org/bb-<target>.tar.gz`

### Mopro Bindings for Multiplatform

-   [mopro-kotlin-package](https://github.com/zkmopro/mopro-kotlin-package): Kotlin bindings for Android.
-   [mopro-swift-package](https://github.com/zkmopro/mopro-swift-package): Swift bindings for iOS.
-   [mopro-react-native-package](https://github.com/zkmopro/mopro-react-native-package): A React Native wrapper.
-   [mopro_flutter_package](https://github.com/zkmopro/mopro_flutter_package): Flutter bindings for Dart-based apps.

### Mopro Bindings for zkEmail

-   [zkemail-swift-package](https://github.com/zkmopro/zkemail-swift-package): Swift bindings for zkEmail verifier.
-   [zkemail-kotlin-package](https://github.com/zkmopro/zkemail-kotlin-package): Kotlin bindings for zkEmail verifier.
-   [zkemail-react-native-package](https://github.com/zkmopro/zkemail-react-native-package): A React Native wrapper for zkEmail.
-   [zkemail_flutter_package](https://github.com/zkmopro/zkemail_flutter_package): Flutter bindings for zkEmail.


## Research

We are also exploring ways to leverage client-side native **GPUs** and other **proving systems** to enhance on-device proof generation. Here are our research findings.

-   [GPU acceleration](https://github.com/zkmopro/gpu-acceleration): Implementing accelerated multi-scalar multiplication (MSM) on iOS devices for enhanced performance.

## Ways to contribute

-   🎯 Please checkout out [open issues](https://github.com/zkmopro/mopro/issues)
-   🔍 Report and issue and feature request [New issue](https://github.com/zkmopro/mopro/issues/new?template=issue-template.md)

## Who are we

Mopro is part of [Privacy & Scaling Explorations (PSE)](https://pse.dev), a multidisciplinary team supported by the Ethereum Foundation. PSE explores new use cases for zero knowledge proofs and other cryptographic primitives.
