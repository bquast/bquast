# Bastiaan Quast

Code 💻 here on Github; datasets 📊 and models (weights) 📈 on [Hugging Face 🤗](https://huggingface.co/bquast)

## Current projects
- [mlx-profiler](https://github.com/bquast/mlx-profiler) - Operation-level profiler for Apple Silicon / MLX. The missing torch.profiler equivalent for the MLX ecosystem.
- [autoresearch-mesa](https://github.com/bquast/autoresearch-mesa) - an adaptation of Karpathy's autoresearch, in turn an OpenClaw 🦞 style AI agent (agent harness) to explore hyperparameters. Uses the python ABM framework [mesa](https://github.com/mesa).
- [autoresearchABM](https://github.com/bquast/autoresearchABM) - an adaptation of Karpathy's autoresearch, in turn an OpenClaw 🦞 style AI agent to explore hyperparameters. This framework is adapted to task the AI agent to fine-tune the parameters of an ABM model, such as as the epidemiological SIR recovery model. Custom-built ABM framework that runs headless, logs everything.
- [autoresearch-mesa-prompt](https://github.com/bquast/autoresearch-mesa-prompts) - using the autoresearch paradigm to probe ABM models using the [mesa](https://github.com/mesa) framework, using only prompts in Claude web.
- eurotrip dataset - a jsonl dataset of conversations that are walking directions in historic city centers, e.g. for SFT use with nanochat-d34
- eurotrip model - a SFT version of nanochat-d34, which provides directions
