# DeepGlobe Land Cover Classification with U-Net 🌍🛰️

This project i use U-Net model for multiclass segmentation of land cover. Trained on the [DeepGlobe Land Cover Classification Dataset](https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset). The model classifies high-resolution satellite images into seven land cover classes.

## 📊 Dataset

- **Source**: DeepGlobe Challenge (CVPR 2018)
- **Resolution**: 2448×2448 RGB satellite images
- **Classes**:
  - Urban Land (0,255,255)
  - Agriculture Land (255,255,0)
  - Rangeland (255,0,255)
  - Forest Land (0,255,0)
  - Water (0,0,255)
  - Barren Land (255,255,255)
  - Unknown (0,0,0)

## 🧠 Model

- **Architecture**: U-Net
- **Framework**: PyTorch
- **Loss Function**: Cross Entropy with weights
- **Optimizer** - Adam
- **Performance**:
  - **Dice Score**: ~0.75–0.80

## 🛠 Technologies Used

- Google Colab (Python 3, Jupyter Notebook)
- PyTorch
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- PIL, cv2

## 🚀 How to Run

You can open and run the notebook in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MatoKamenicky/airline-passenger-satisfaction/blob/main/Airline_Satisfaction_MLP.ipynb)

Or clone this repository and run locally:

```bash
git clone https://github.com/MatoKamenicky/landcover-classification-unet
cd airline-passenger-satisfaction
jupyter notebook
```




