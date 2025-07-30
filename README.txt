{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # SenseOrPass - Proteomic Cancer Classifier\
\
This project implements a deep learning classifier trained on proteomic biomarker data filtered by a predefined protein list. It includes model evaluation using ROC/AUC and SHAP interpretability.\
\
## \uc0\u55357 \u56514  Structure\
\
- `notebooks/` \'96 Jupyter notebook with complete pipeline\
- `src/` \'96 Modular Python scripts for preprocessing, modeling, and evaluation\
- `data/` \'96 Selected protein list and input data\
- `outputs/` \'96 Trained models and plots\
\
## \uc0\u55357 \u56549  Data Access\
\
Data for this study is available through the following portals:\
- [Head and Neck 5000](https://headandneck5000.org.uk/information-for-researchers/)\
- [Exeter 10,000](https://exetercrfnihr.org/about/exeter-10000/)\
\
## \uc0\u55358 \u56810  Setup\
\
```bash\
pip install -r requirements.txt\
}