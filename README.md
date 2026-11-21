# Ollama 

Offline model runner for executing Qwen, Bonsai 27B, and open-weight GGUF models directly on your local GPU with zero telemetry.

<img width="844" height="844" alt="images1" src="https://github.com/user-attachments/assets/2def1d68-ca47-4101-8f08-bf80101dfced" />
<img width="897" height="585" alt="images2" src="https://github.com/user-attachments/assets/bb9bf3a4-1800-4f53-b5b9-da278d86bc3e" />

## Running Models with Modelfiles

```bash
ollama pull qwen3:latest
ollama run bonsai:27b
```

<img width="651" height="307" alt="images3" src="https://github.com/user-attachments/assets/2cb0c17f-e129-4bca-a57d-b75d5cec7c14" />
<img width="626" height="319" alt="images4" src="https://github.com/user-attachments/assets/4c8956df-6186-4d1a-8c6e-3b837e159bc8" />

<details>
<summary>GPU Offloading & Context Tuning</summary>

Adjust `num_ctx` and layer allocation inside `files/model/Modelfile.bonsai` to balance VRAM usage across CUDA or ROCm cards.

</details>

<img width="676" height="295" alt="images5" src="https://github.com/user-attachments/assets/02ed9064-974d-4971-a3a5-620186fd6f01" />
