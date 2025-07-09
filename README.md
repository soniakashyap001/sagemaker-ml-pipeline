# 🧠 End-to-End ML Pipeline with Amazon SageMaker (XGBoost)

This project demonstrates how to build a complete machine learning pipeline on AWS SageMaker using the built-in XGBoost algorithm. The pipeline includes data upload, training, model deployment, and inference — all done programmatically using Boto3 and SageMaker SDK.

## 🚀 Steps Covered

- Creating an S3 bucket
- Uploading train/test data using Boto3
- Setting up SageMaker notebook instance with IAM roles
- Training a model using SageMaker's built-in XGBoost container
- Deploying the model for inference
- Making predictions and decoding outputs

## 📁 Project Structure

```
sagemaker-ml-pipeline/
├── data/           # Sample train/test CSVs (optional)
├── notebook/       # Jupyter notebook with full code
├── screenshots/    # Screenshots from AWS console
├── requirements.txt
└── README.md
```

## 📸 Screenshots

| Creating S3 Bucket | Notebook Instance | Model Output |
| ------------------ | ----------------- | ------------ |
|                    |                   |              |

## 🔗 Medium Article

📖 [Building an End-to-End ML Pipeline with Amazon SageMaker (XGBoost)](https://medium.com/@soniakashyap001/building-an-end-to-end-ml-pipeline-with-amazon-sagemaker-xgboost-2fb580f6ce45)

## 🛠 Requirements

```bash
boto3
sagemaker
pandas
numpy
```

Install them with:

```bash
pip install -r requirements.txt
```

## 💬 Author

**Sonia Kashyap**\
[LinkedIn](https://linkedin.com/in/soniakashyap001) • [Medium](https://medium.com/@soniakashyap001)

---

Feel free to fork this repo, open issues, or suggest improvements!

