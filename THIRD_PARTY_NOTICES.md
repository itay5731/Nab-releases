# Third-party notices

Nab includes or depends on the open-source software listed below. Each component is © its respective authors and
licensed under the license shown. Full license texts are in each package's distribution (`node_modules/<pkg>/LICENSE`,
or the crate source on crates.io).

## JavaScript / TypeScript

| Component | License |
|---|---|
| React | MIT |
| React DOM | MIT |
| Zustand | MIT |
| Lucide (lucide-react) | ISC |
| highlight.js (diff syntax highlighting, loaded on demand) | BSD-3-Clause |
| Mermaid (diagrams in issue text, loaded on first use) | MIT |
| KaTeX (math in issue text, loaded on first use) | MIT |
| DOMPurify (sanitizes diagram and math output) | Apache-2.0 OR MPL-2.0 |
| @tauri-apps/api | MIT OR Apache-2.0 |
| @tauri-apps/plugin-global-shortcut | MIT OR Apache-2.0 |
| @tauri-apps/plugin-http | MIT OR Apache-2.0 |
| @tauri-apps/plugin-notification | MIT OR Apache-2.0 |
| @tauri-apps/plugin-opener | MIT OR Apache-2.0 |
| @tauri-apps/cli (build only) | MIT OR Apache-2.0 |
| Tailwind CSS, @tailwindcss/vite (build only) | MIT |
| Vite, @vitejs/plugin-react (build only) | MIT |
| TypeScript (build only) | Apache-2.0 |

## Fonts

| Component | License |
|---|---|
| DM Sans (via @fontsource-variable/dm-sans) | SIL Open Font License 1.1 |

## Rust

| Crate | License |
|---|---|
| tauri, tauri-build | MIT OR Apache-2.0 |
| tauri-plugin-http, tauri-plugin-notification, tauri-plugin-opener, tauri-plugin-global-shortcut | MIT OR Apache-2.0 |
| keyring | MIT OR Apache-2.0 |
| serde, serde_json | MIT OR Apache-2.0 |

Transitive dependencies are under their own (generally MIT, Apache-2.0, BSD or ISC) licenses. To get a complete list,
run `npx license-checker --summary` and `cargo license` (from `cargo install cargo-license`) in `src-tauri/`.

## AI models (not bundled)

Nab does **not** ship any AI model. When you choose local AI, you download models yourself through
[Ollama](https://ollama.com), under each model's own license:

| Model | License |
|---|---|
| Qwen2.5-7B-Instruct (`qwen2.5:7b`) | Apache-2.0 |
| Phi-4-mini (`phi4-mini`) | MIT |
| nab-qwen (Nab's fine-tune of Qwen3.5-9B; v1.0: Qwen2.5-7B-Instruct), downloaded from the project's releases with its LICENSE and NOTICE | Apache-2.0 |

If you use a cloud provider (OpenAI-compatible or Anthropic), that provider's terms of service apply.

## Trademarks

GitLab is a trademark of GitLab Inc. Nab is not affiliated with or endorsed by GitLab Inc. Other names may be
trademarks of their respective owners.
