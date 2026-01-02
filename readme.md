<p align="center">
  <img src="https://github.com/gellston/PsTorch/blob/main/logo.png?raw=true" width="400" />
</p>


# Introduction
PsTorch

PsTorch is an experimental, PowerShell-first toolkit inspired by PyTorch—built for people who want to define “torch-like” models directly in PowerShell and save/load models (weights + architecture metadata) in a repeatable way for scripting, automation, and deployment.

The goal is to make model development feel familiar to PyTorch users (e.g., a Module-style mindset and a clear forward flow), while still embracing what PowerShell is good at: composable commands, reproducible scripts, and automation-friendly tooling. 

Intended capabilities

Torch-style model authoring in PowerShell: define layers/modules, compose them into reusable networks, and run forward passes from scripts.

Model persistence as a first-class feature: save checkpoints and reload them reliably (model parameters + versioned metadata), so you can ship and reproduce results.

Automation-friendly workflows: train/infer/evaluate from CI pipelines and scripted environments, without needing a full Python project structure.

Backend-agnostic direction (planned): keep the PowerShell API stable while evaluating practical execution backends (e.g., .NET/libtorch integrations).

Project status

PsTorch is currently under review, and I'am collecting materials (prior art, design references, serialization approaches, and API requirements). Expect the API and implementation details to evolve as research and prototyping progresses.