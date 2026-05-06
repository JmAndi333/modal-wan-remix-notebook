# 🎬 Wan 2.2 Remix I2V - Modal One-Click Deployment

[![Deploy on Modal](https://img.shields.io/badge/Deploy%20on-Modal-7B61FF?style=for-the-badge)](https://modal.com/notebooks/import?url=https://raw.githubusercontent.com/JmAndi333/modal-wan-remix-notebook/main/wan_remix_i2v_modal.ipynb)

Generate high-quality videos from images using **Wan 2.2 Remix I2V** on **Modal.com's A100 GPUs**.

## 🚀 One-Click Deploy

**No downloads, no setup required.**

1.  Click the **Deploy on Modal** button above
2.  In Cell 2, replace `YOUR_CIVITAI_API_KEY_HERE` with your **Civitai API key**
3.  Run each cell with **Shift+Enter**
4.  Open your **ComfyUI URL** and load the Wan2.2 Remix workflow
5.  Upload a start image, enter your prompt, and click **Queue Prompt**

## 📦 What's Included
| Component | Details |
| :--- | :--- |
| **Main Model** | Wan 2.2 Remix I2V High v3.0 (fp8, 13.3GB) |
| **VAE** | Wan 2.1 VAE |
| **Text Encoder** | UMT5-XXL (fp8) |
| **Custom Nodes** | rgthree, VideoHelperSuite, ComfyUI Essentials, MixLab, cg-nodes |
| **GPU** | NVIDIA A100 80GB |
| **Workflow** | Compatible with 肥猴's I2V workflow |

## 🔗 Resources
- [Wan2.2 Remix on Civitai](https://civitai.com/models/2003153/wan22-remix-t2vandi2v)
- [Workflow by 肥猴](https://www.runninghub.ai/workflow/2051406785923305474)
- [GGUF Quantized Versions](https://huggingface.co/BigDannyPt/Wan-2.2-Remix-GGUF)

## ⚙️ Hardware & Costs
- **GPU:** NVIDIA A100 80GB
- **Storage:** Persistent Modal Volume (models cached)
- **Estimated cost:** ~$2.50/hour of generation time

## 📝 License
Model subject to original Wan2.2 Remix license terms.
