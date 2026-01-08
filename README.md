# SIBI Word Recognition – Inference & Paper

This repository contains the **inference code** and the accompanying **research paper** for an AI-based system that performs **word-level recognition of Indonesian Sign Language (SIBI)** from video input.

The work focuses on SIBI gestures commonly used in **formal and academic contexts**, with an emphasis on real-world applicability and performance trade-offs.

## Repository Structure

- `Inference Code.ipynb`  
  Jupyter Notebook containing the complete inference pipeline, including:
  - Video/frame preprocessing
  - Model loading
  - Real-time or offline gesture inference

- `Paper SLR.pdf`  
  The research paper describing:
  - Dataset construction
  - Model architectures (3D CNN and CNN–LSTM)
  - Experimental results and analysis

- `README.md`  
  Project overview and usage instructions.

## Model

The provided model is based on a **CNN–LSTM architecture**:
- A CNN extracts spatial features from individual video frames
- An LSTM models temporal dependencies across frames

The model is trained for **word-level SIBI gesture recognition**, not alphabet-level classification.

## Model Weights

Download the pretrained model from the link below and place it in the appropriate directory as referenced in the notebook:

**Model download:**  
https://drive.google.com/file/d/1gD_gsBWIVYkQsBgWlwnH_iTxZrbGkI-f/view?usp=sharing

## Usage

1. Download the pretrained model from the link above  
2. Open `Inference Code.ipynb`
3. Install required dependencies (as specified in the notebook)
4. Run the notebook cells to perform inference on video input

The notebook is intended for **research, evaluation, and demonstration purposes**.

## Notes

- The dataset used in this research is **not publicly available** due to privacy and consent constraints.
- Inference performance depends heavily on hardware configuration (CPU vs GPU).
- The system is designed for **word-level SIBI recognition**, not continuous sentence translation.

## Citation

If you use this work in your research, please cite the paper accordingly.
