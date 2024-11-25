# Multi-Modal Retrieval-Augmented Text-to-3D Generation with Accelerated Sampling

This repository contains the official implementation of the paper **"Multi-Modal Retrieval-Augmented Text-to-3D Generation with Accelerated Sampling"**.

## 📰 News
We are currently organizing the related code. Please stay tuned and thank you for your patience!

## 🚀 Features
- Multi-modal retrieval mechanism for improved efficiency.
- Enhanced semantic consistency between generated 3D models and textual prompts.
- Significant reduction in sampling time.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/lingdoudoulingling/MM-Re3D.git
   cd MM-Re3D
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure compatibility with your environment:
   - **CUDA version:** 11.6  
   - **Python version:** 3.10 
   - Other dependencies listed in `requirements.txt`.

## 📂 Project Structure
- `src/`: Core implementation of MM-Re3D.
- `data/`: Sample datasets for testing.
- `configs/`: Configuration files for experiments.
- `scripts/`: Utility scripts for preprocessing and evaluation.
- `results/`: Generated 3D models and benchmarks.

## 📋 Usage

1. Preprocess data:
   ```bash
   python scripts/preprocess.py --config configs/preprocess.yaml
   ```

2. Train the model:
   ```bash
   python src/train.py --config configs/train.yaml
   ```

3. Generate 3D models:
   ```bash
   python src/generate.py --input your_text_prompts.txt
   ```

4. Evaluate results:
   ```bash
   python scripts/evaluate.py --generated_folder results/
   ```

## ✏️ Citation
If you find our work useful, please cite us:
```bibtex
@article{your_paper,
  title={Multi-Modal Retrieval-Augmented Text-to-3D Generation with Accelerated Sampling},
  author={Your Name and Others},
  journal={Journal/Conference Name},
  year={2024}
}
```

## 🙌 Acknowledgements
This project is inspired by prior works on Shap.E, SDFusion, Ret3D .etc.


