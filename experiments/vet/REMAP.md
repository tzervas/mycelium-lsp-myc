# Remap Manifest — mycelium-lsp → lsp

_DN-109 §5.2 provenance ledger. Guarantee: **Declared** — this records proposed/performed structural and idiom choices; it does not certify them (no guarantee-tag upgrade from the manifest's existence alone, VR-5). Rendered from `remap` in `summary.json` — this file is a pure projection, never a second source of truth._

## Nodules (25)

| Target nodule | Operation | Safety | API surface changed | Identity neutral | Sources | Rationale |
|---|---|---|---|---|---|---|
| `lsp.baseline` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/baseline.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.bin.mycelium-lsp` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/bin/mycelium-lsp.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.completions` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/completions.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.definition` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/definition.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.diagnostics.audit` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/diagnostics/audit.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.diagnostics` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/diagnostics/mod.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.diagnostics.policy` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/diagnostics/policy.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.diagnostics.record` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/diagnostics/record.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.diagnostics.registry` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/diagnostics/registry.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.diagnostics.sink` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/diagnostics/sink.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.expand` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/expand.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.feedback` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/feedback.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.fmt` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/fmt.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.hover` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/hover.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/lib.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.lint` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/lint.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.llm_canonical_parser` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/llm_canonical_parser.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.project` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/project.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.recover.effect` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/recover/effect.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.recover` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/recover/mod.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.recover.policy` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/recover/policy.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.semantic` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/semantic.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.span` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/span.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.sync` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/sync.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |
| `lsp.wire` | Keep | Safe | false | true | `/root/git/isolated/mycelium/crates/mycelium-lsp/src/wire.rs` | structure-preserving 1:1 (DN-109 §5.3-B v0 default: every emitted nodule keeps its source file's mod-tree position, no restructuring proposed) |

## Idiom choices (0)

_(none in this run — v0 Mechanical-only auto-fire with no located idiom-choice instrumentation yet; see DN-109 §7-e and this module's doc comment)_
