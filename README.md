# Intellihack_TeamX_Task3
Submission for IntelliHack 5.0 LLM Task 1 by TeamX.

## Contents
- `IntelliHack_LLM_Submission.ipynb`: Notebook with training, evaluation, inference, and report.
- **Model Files**:
  - Model files : [Google Drive Link to qwen_finetuned](https://drive.google.com/drive/folders/1iblM9GfxnS9642wwiQwTwystp5gmtzFg?usp=drive_link)

## Instructions
1. Open `IntelliHack_LLM_Submission.ipynb` in Google Colab.
2. Mount Drive: `from google.colab import drive; drive.mount('/content/drive')`.
3. Install dependencies: `!pip install torch==2.6.0+cu124 -f https://download.pytorch.org/whl/torch_stable.html; !pip install unsloth==2025.3.9 transformers==4.48.3 datasets==2.19.0`.
4. Run cells to load model and test inference.
5. Model files are in Drive (links above) or upload locally by downloading them.

## Notes
- Trained on 5 DeepSeek `.md` files, 43 train/11 test examples.
- Uses Qwen2-0.5B with LoRA, 4-bit quantization for efficiency.
