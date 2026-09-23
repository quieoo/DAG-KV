# DAG-KV Artifact for USENIX ATC '26

This repository documents the artifact for the following paper:

> **DAG-KV: DAG-Guided KV Propagation for Structure-Aware Knowledge Reuse**  
> USENIX Annual Technical Conference 2026 (USENIX ATC '26)

## Artifact Access

This GitHub repository contains documentation only; it does not distribute the source code or experimental files. For Artifact Evaluation, authorized reviewers will be given access to a preconfigured environment hosted by the authors. The server will be temporarily reachable over the network during the evaluation period. Connection instructions and temporary credentials will be shared through the designated private AE channel; no server address or credentials are published here.

## Evaluation Status

The primary evaluation targets are the main accuracy results and the reuse-efficiency results reported in Secs. 5.2–5.4. Additional experiments from Secs. 5.5–5.7 will be made available soon.

| Paper section | Result | Status |
|---|---|---|
| Sec. 5.2 | Main results (Figure 6 and Table 3) | Ready |
| Sec. 5.3 | Structural reasoning (Figures 7–8) | Ready |
| Sec. 5.4 | Reuse efficiency (Figure 9) | Ready |
| Sec. 5.5 | Knowledge editability (Figure 10) | In progress |
| Sec. 5.6 | Ablation study (Figure 11) | In progress |
| Sec. 5.7 | Sensitivity analysis (Figure 12) | In progress |

The status table will be updated as the remaining evaluation materials are finalized.

## Evaluation Environment

The evaluation environment is preconfigured. The main experimental setup includes:

- NVIDIA L40 GPUs
- CUDA 12.4
- PyTorch 2.6.0
- Transformers 4.57.6
- FAISS-CPU 1.13.2
- LlamaIndex 0.14.21

## Reproducing Results

After connecting to the evaluation environment, follow `ArtifactEvaluation/README.md` in the workspace for the exact commands and expected outputs for each result. The scripts and stored outputs are organized by figure and table. Some workflows summarize existing outputs by default; full reruns are available where documented and may take substantially longer. Reruns that use external API services require the corresponding credentials to be configured in the environment.

Runtime varies by figure and dataset. If you encounter an issue during evaluation, contact the authors through the designated AE channel.
