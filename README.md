# Bastiaan Quast

Code 💻 here on Github 🐙; datasets 📊 and models (weights) 📈 on [Hugging Face 🤗](https://huggingface.co/bquast)

[Gists 📄](https://gist.github.com/bquast) are even more elegant than repos, I add instructions in the comments below the code file.

## Current projects
- [mlx-profiler](https://github.com/bquast/mlx-profiler) - operation-level profiler for Apple Silicon / MLX, torch.profiler equivalent for  MLX
- [py-arena.com](https://py-arena.com) ([repo](https://github.com/bquast/py-arena)) - side-by-side code LLM battle arena for vanilla Python challenges, executes locally using pyodide
- [CodePromptIdeas.com](https://codepromptideas.com) ([repo](https://github.com/bquast/js-arena)) - side-by-side code LLM battle arena focused on vanilla JavaScript, inspiring users, and generating a new dataset for LLM coding.
- [simple-agent-harness](https://github.com/bquast/simple-agent-harness) - bare-bones AI agent harnass (like OpenClaw 🦞), using a local LLM via Ollama (default `gemma4:e2b`)
- [autoresearch-mesa](https://github.com/bquast/autoresearch-mesa) - adaptation of Karpathy's autoresearch, in turn an OpenClaw 🦞 style AI agent (agent harness), to explore hyperparameters. Uses the python ABM framework [mesa](https://github.com/mesa). Version using only prompts: [autoresearch-mesa-prompt](https://github.com/bquast/autoresearch-mesa-prompts).
- [homomorphic-encryption](https://github.com/bquast/homomorphic-encryption) - from-scratch javascript implementations and demonstrations of homomorphic encryption in the major schema: BFV, BGV and CKKS (including complex-numbe encoder). Also a demonstration of the partially homomorphic properties of RSA encryption. ([Grok explanation of HE](https://grok.com/share/c2hhcmQtMg_776a4ad3-9199-4128-a39f-b9891d03ff64))
- [error-correction-codes](https://github.com/bquast/error-correction-codes) - grokking algorithms for major error-correction algos: Reed-Solomon, Hamming, BCH
- [adapt-ui](https://adaptui.pages.dev) ([repo](https://github.com/bquast/adaptui)) - adapt the UI of this LLM interface directly by prompting the LLM what you want the interface to look like. WIP: work with design.md files


## WIP
- [AgentsArena.live](https://agentsarena.live) ([repo](https://github.com/bquast/agent-arena)) - side-by-side benchmark for agentic tasks, compare performance of leading models operations (as opposed to text/code generation), e.g. writing and patching files, executing commands, etc. Uses CloudFlare agent enviroments as sandboxes to run the models in.
- [homomorphic-encryption.go](https://github.com/bquast/homomorphic-encryption.go) - from-scratch implementations of homomorphic encryption algorithms in Go, compiled to Web Assembly (WASM) using Github Actions, an end-to-end verifiable pipeline
- [Common Vulnerabilities Exposures dataset](https://huggingface.co/datasets/bquast/Common-Vulnerabilities-Exposures-1995-2025/tree/main) - cybersecurity training dataset [CVE] 1995-2025
- - `eurotrip` dataset - a `jsonl` dataset of conversations that are walking directions in historic city centers, e.g. for SFT use with nanochat-d34
- `eurotrip` model - a SFT version of `nanochat-d34`, which provides directions

## Long-term projects
- [rrn](https://github.com/bquast/rnn) - (2013-) native R implementations of recurrent neural network algorithms: vanilla RNN, LSTM, GRU, etc, >100k downloads from CRAN
- [transformer](https://github.com/bquast/transformer) - (2020-) native R implementation of the transformer algorithm, available on CRAN
- [HomomorphicEncryption](https://github.com/bquast/HomomorphicEncryption) - (2021-) perform computations, functions, such as AI models on encrypted data, native R implementations of the major FHE schema: BFV, BGV, CKKS
- [HEtools](https://github.com/bquast/HEtools) - (2021-) python (and [Julia](https://github.com/bquast/HEtools.jl)) implementation of homomorphic encryption primitives
- [error-correction-codes](https://github.com/bquast/error-correction-codes) - (2023-) from-scratch implementations of major error-correction codes schema: Reed-Solomon, Hamming, BCH

## iOS / MacOS App Store
- [SwissWallet](https://apps.apple.com/ch/app/swisswallet/id6737986330?l=en-GB) (iOS + MacOS): swift implementations of barcode, QR code, MicroQR, etc. rendering
- [Big Files Tree Map](https://apps.apple.com/ch/app/big-files-tree-map/id6743767388?l=en-GB&mt=12) (MacOS): Square multi-level pie chart to vizualize large files on disk, for saving space
- [LiteText](https://apps.apple.com/ch/app/litetext/id6745022159?l=en-GB&mt=12) (MacOS): ObjectiveC no-dependencies flat text editor in Y2K style, include line and column indicators
- [KneeBoard](https://apps.apple.com/ch/app/kneeboard-notes/id6745168130?l=en-GB&mt=12) (MacOS): menubar quick text widget, always at hand for taking notes or copying text, just like a pilot's kneeboard

[full resume online / PDF](https://github.com/bquast/resume/)
