Test PID: 899
=== Batch Panel Generator v2 ===
Checkpoint: NoobAI-XL-v1.1.safetensors
Style LoRA: iLLMythD4rkL1nesV2.safetensors (0.7)
Resolution: 832x1216 (no upscale)
VAE: Standard (lowvram mode handles memory)
Steps: 25, Sampler: euler_ancestral/karras, CFG: 7.0
ComfyUI: http://192.168.0.121:8188
Output: /Volumes/synologyNFS/Mardov/panels

--- Panel Status (all 85 panels) ---
  Rendered:         59
  Needs refinement: 26
  Pending:          0

Mode: refinements-only
Jobs to generate: 1

  Waiting for ComfyUI (up to 120s)............. OK
ComfyUI 0.15.1 -- cuda:0 NVIDIA GeForce RTX 3060 Ti : cudaMallocAsync
VRAM free: 7.0 GB
[1/1] Panel 9: panel-09-the-road-draft.png [needs_refinement]
  Prompt: D4rkL1nes, masterpiece, best quality, absurdres, wide landscape, winding road through dark forest, riders on horseback s...
  ERROR: HTTP 400 - {"error": {"type": "prompt_outputs_failed_validation", "message": "Prompt outputs failed validation", "details": "", "extra_info": {}}, "node_errors": {"7": {"errors": [{"type": "required_input_missing", "message": "Required input is missing", "details": "temporal_overlap", "extra_info": {"input_name": "temporal_overlap"}}, {"type": "required_input_missing", "message": "Required input is missing", "details": "temporal_size", "extra_info": {"input_name": "temporal_size"}}, {"type": "required_inpu
  Retry 1/2...
  Waiting for ComfyUI (up to 180s)......................... TIMEOUT
  ComfyUI did not recover -- skipping panel 9


=== Batch Complete ===
Succeeded: 0, Failed: 0
Total time: 3.3 minutes
