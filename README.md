# Semantic Attention Research Pipeline

Folder organization:

1. 01_semantic_attention_statistics
   - Main A–E participant-level semantic attention analysis
   - g_H, g_P, g_C, g_O, Semantic Focus = 1 - g_O
   - Descriptive statistics, mixed-effects models, pairwise comparisons, FDR

2. 02_compositional_analysis
   - ILR / log-ratio analysis of G=[g_H,g_P,g_C,g_O]

3. 03_vlm_semantic_scoring
   - Local VLM inference to estimate S=[s_H,s_P,s_C,s_O]

4. 04_human_vlm_alignment
   - Participant-level JSD(G,S), condition comparisons

5. 05_gaze_routing
   - H/P/C/O fixation sequences and transition matrices

6. 06_transition_entropy
   - Transition entropy and gaze-structure analysis

7. 07_spatial_map_alignment
   - Human heatmaps vs model maps: CC, SIM, NSS, JSD

Run steps in numerical order.
