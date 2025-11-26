# Ensemble-Deep-Learning-for-Precision-Detection-and-Severity-Assessment-of-Wheat-Diseases
Ensemble Deep Learning for Precision Detection and Severity Assessment of Wheat Diseases
🔗 Availability of Code and Dataset

Source Code (GitHub DOI): DOI: xxxx (replace after Zenodo DOI generation)

Dataset (Zenodo DOI): DOI: xxxx

Both resources are publicly available to support transparency and reproducibility.

📂 Repository Structure
├── data/               # Dataset path (images and labels)
├── models/             # Saved weights and trained models
├── src/                # Training and evaluation scripts
│   ├── dataloader.py
│   ├── model.py
│   ├── train.py
│   ├── test.py
│   └── utils.py
├── results/            # Evaluation metrics and visualizations
├── requirements.txt    # Dependencies
└── README.md

⚙️ Dependencies

Install packages using:

pip install -r requirements.txt


Main libraries:

Python 3.8+

TensorFlow / Keras or PyTorch (depending on your implementation)

NumPy

OpenCV

Scikit-learn

Matplotlib

🗂 Dataset

The dataset contains wheat leaf images categorized by disease type and severity level.

Download and extract dataset to data/ directory:

data/
    ├── Healthy/
    ├── Disease_1/
    ├── Disease_2/
    ├── ...


Dataset DOI: xxxx (replace once uploaded)

🚀 Training

To train the ensemble deep learning model:

python src/train.py --epochs 100 --batch_size 32 --img_size 224

🧪 Testing / Evaluation

To evaluate the trained model:

python src/test.py --weights models/best_model.h5

📊 Outputs

The repository generates:

Accuracy and loss curves

Confusion matrices

Severity classification results

CSV reports

Results are saved in the results/ directory.

📝 Citation

If you use this code or dataset, please cite the manuscript:

This repository contains the official implementation of the manuscript titled
"Ensemble Deep Learning for Precision Detection and Severity Assessment of Wheat Diseases,"
submitted to *The Visual Computer*.

If you use this code or dataset in your research, please cite our manuscript.


(Full BibTeX will be added after acceptance.)

✉ Contact

For questions or collaborations:

Author: Muhammad Asim
Email: Muhammad Asim
