# Step 03 — Grounded VLM Semantic Oracle

Main notebook:
- `03_grounded_vlm_semantic_oracle.ipynb`

Core output:
- `outputs/vlm_semantic_master.csv`

Method:
- prompt ensemble × repeated runs
- semantic uncertainty via Jensen–Shannon divergence
- H/P/C grounding stability via IoU
- Semantic Hierarchy Drift relative to original A
- intended semantic route for later scanpath analysis
- optional counterfactual semantic ablation

Default model:
- Qwen/Qwen3-VL-8B-Instruct

Optional robustness:
- Qwen/Qwen3-VL-30B-A3B-Instruct with 4-bit loading

Important:
The model is explicitly instructed not to predict human gaze.
