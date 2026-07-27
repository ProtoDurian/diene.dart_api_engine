# Changelog

All notable changes to this package are documented here. Releases are managed
from conventional commits by the repository release workflow.

## 1.0.0 (2026-07-27)

### 📜 Documentation 📜

- **api-engine:** write the package doc and the required parity note ([95e5bd5](https://github.com/AtomiCloud/diene.dart_api_engine/commit/95e5bd5bd20ba5f9439c0abb17665d4b48452f3d))

### ✨ Features ✨

- **shared:** add agnostic standards payload ([2d65acb](https://github.com/AtomiCloud/diene.dart_api_engine/commit/2d65acb118ebcc797cca0f13b0d9e979e7a8c29c))
- **probes:** add nix root suite ([27e4184](https://github.com/AtomiCloud/diene.dart_api_engine/commit/27e41843f06e38cfcc26a516c05f4ae4fb294ac0))
- **dart-lib:** add pure-Dart publishable library template package ([47a4837](https://github.com/AtomiCloud/diene.dart_api_engine/commit/47a4837f54f7ad0342a4539ff1320c4f94d7df71))
- **probes:** add shared authoring helpers ([f20d53f](https://github.com/AtomiCloud/diene.dart_api_engine/commit/f20d53f805564fe21e0ee32084fc49f2973a50e4))
- materialize atomi/nix sample (yes_basic_yes_llm) as chain root ([24105ef](https://github.com/AtomiCloud/diene.dart_api_engine/commit/24105ef4948ff884353011be24b915f69c7c8382))
- materialize workspace spine baseline ([f74cf31](https://github.com/AtomiCloud/diene.dart_api_engine/commit/f74cf3179989e12f662b1c98061aeb2d4803f563))
- **shared-wo-docker:** remove Docker axis ([b125b74](https://github.com/AtomiCloud/diene.dart_api_engine/commit/b125b74a556f5b5f5d82ef973a79c80079c5b63e))
- **shared-wo-docker-helm:** remove Helm axis ([e01fe36](https://github.com/AtomiCloud/diene.dart_api_engine/commit/e01fe368b9fe30bee238c809a58444c9170998f2))
- **api-engine:** transplant diene_api_engine onto the dart-lib layout ([a347d29](https://github.com/AtomiCloud/diene.dart_api_engine/commit/a347d29c5747f54fece2f2bcb70f1dd37be60919))
- **dart-lib:** wire Dart CI, release, and OIDC publish machinery ([770b8ec](https://github.com/AtomiCloud/diene.dart_api_engine/commit/770b8ec512e44ccfb0495daebbcad081a65344c5))

### 🐛 Bug Fixes 🐛

- **probes:** attribute actionlint smoke overlap ([bfb0271](https://github.com/AtomiCloud/diene.dart_api_engine/commit/bfb02717d6eca8c86f617efe50286008da328fe1))
- **nix:** check precommit from repository root ([c6046ac](https://github.com/AtomiCloud/diene.dart_api_engine/commit/c6046ac3d877f2fed40073ff333fe2b877b778a8))
- **api-engine:** contain a transport that breaks its throw contract ([cdaec68](https://github.com/AtomiCloud/diene.dart_api_engine/commit/cdaec6876f9714bff8acd3cf049ad8639b4646de))
- **nix:** enforce root formatter probes ([3b4188a](https://github.com/AtomiCloud/diene.dart_api_engine/commit/3b4188aa9797c14f10fb448e68cdeefeb9ae231e))
- **api-engine:** give pana the Flutter SDK and buildable lower bounds ([ed5b472](https://github.com/AtomiCloud/diene.dart_api_engine/commit/ed5b472188bf9ba047519e60c3cf69eff9f1f9e0))
- **api-engine:** honour the R-E14 wire-id law and close the meta ledger ([d2423e1](https://github.com/AtomiCloud/diene.dart_api_engine/commit/d2423e188736cdc476dc6e7536cac72b193248c2))
- **probes:** isolate cross-template mutations ([f8169d0](https://github.com/AtomiCloud/diene.dart_api_engine/commit/f8169d002a3db773f638a01a280c0170781164f5))
- **dart-lib:** make the released changelog formatter-clean at generation ([#121](https://github.com/AtomiCloud/diene.dart_api_engine/issues/121)) ([59a812b](https://github.com/AtomiCloud/diene.dart_api_engine/commit/59a812bf5b78e986dee16c47e4da90f18b20bd7c))
- **dart-lib:** preserve nested C0 result files ([#126](https://github.com/AtomiCloud/diene.dart_api_engine/issues/126)) ([602610f](https://github.com/AtomiCloud/diene.dart_api_engine/commit/602610fd452430fd7e8a3cdd396cfd0b0f8235ee))
- **api-engine:** stop tracking the generated Flutter plugin manifest ([0b4bbcf](https://github.com/AtomiCloud/diene.dart_api_engine/commit/0b4bbcf3abc5acc8388205aad6a220bffb38e2af))
- **api-engine:** track the two C0 release files gitignore was hiding ([ec3f616](https://github.com/AtomiCloud/diene.dart_api_engine/commit/ec3f6169d796363bfe74fa08aaefa312ab43c596))
- **dart-lib:** use credentialed pub.dev publishing ([#107](https://github.com/AtomiCloud/diene.dart_api_engine/issues/107)) ([796d025](https://github.com/AtomiCloud/diene.dart_api_engine/commit/796d0252fa94b14e2ec418fd9c70e3f75e792813))

### 🧪 Tests 🧪

- **dart-lib:** add TEMPLATE-ONLY CyanPrint probe matrix ([6a1f748](https://github.com/AtomiCloud/diene.dart_api_engine/commit/6a1f748e2960ae7cd07d768eec81bdbbd68c0ed7))
- **api-engine:** cover a constructor hidden by const evaluation ([28ab6bb](https://github.com/AtomiCloud/diene.dart_api_engine/commit/28ab6bbf06e86d8afb116ba2fa20e6e316df6c7d))
- **api-engine:** cover the adapter body fallbacks dio cannot reach ([9f2cbbc](https://github.com/AtomiCloud/diene.dart_api_engine/commit/9f2cbbc2cbe4ae729f27646886608bb8bed1f4de))
- **api-engine:** cover the generated codecs and the engine's real paths ([301bcb2](https://github.com/AtomiCloud/diene.dart_api_engine/commit/301bcb29cd361474ce0865742ad94129d9d04853))
- **api-engine:** cover the rescue retry, config types and doc decoding ([a9b970a](https://github.com/AtomiCloud/diene.dart_api_engine/commit/a9b970a6ad890bf01a0a5369c4a8e51f6546f588))
- **api-engine:** cover the SDK adapter, transport and config edge paths ([81d6cb8](https://github.com/AtomiCloud/diene.dart_api_engine/commit/81d6cb88cb98e7bd37ef73dfe75172fb60940b75))
- **api-engine:** cover the transport, probe and generated-client paths ([6a5f170](https://github.com/AtomiCloud/diene.dart_api_engine/commit/6a5f170f024dd0888f830003592dd7a295ae3ac3))
- **api-engine:** drive BackendClientAdapter through a real Dio client ([9ad6428](https://github.com/AtomiCloud/diene.dart_api_engine/commit/9ad64283cb63bc192e66d25ce5f41fc48d229709))
- **dart-lib:** fix dead-code and credential-policy mutation sabotages ([f1737e9](https://github.com/AtomiCloud/diene.dart_api_engine/commit/f1737e95d097716c53139fe2b64822dddb71aa6b))
- **dart-lib:** fix deadcode-whole-package sabotage target ([226e3d2](https://github.com/AtomiCloud/diene.dart_api_engine/commit/226e3d2de16ff2ce5b206f434e12fcac9fd79354))
- **dart-lib:** fix probe baselines for gitlint hook and pana ([1519f9a](https://github.com/AtomiCloud/diene.dart_api_engine/commit/1519f9a4939ab0811cac827e1c36d2eaa2da1d05))
- **dart-lib:** restore workspace deps for skills-freshness sandbox ([9a2e5bf](https://github.com/AtomiCloud/diene.dart_api_engine/commit/9a2e5bffc1e4ff36d259c1abc2b5021a7b7bca87))

## 0.0.0

- Establish the pure-Dart library template: workspace-member package metadata,
  strict analysis options, and pub.dev publish hygiene.
- Add the replaceable `Note` sample: an immutable value type with a JSON wire
  codec and the pure `summarizeNote` transform, exported from the barrel.
- Add the dependency-light `assertNoteSummary` TestHelper and its meta suite.
- Add the C0 fixture harness with a SHA-256 digest manifest and a
  decode/encode/decode round trip.
