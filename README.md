[![Github Actions Workflow](https://github.com/DiogoCarapito/Access_AWS_from_Studio_Lab_Deployment/actions/workflows/main.yaml/badge.svg)](https://github.com/DiogoCarapito/Access_AWS_from_Studio_Lab_Deployment/actions/workflows/main.yaml)

# Access_AWS_from_Studio_Lab_Deployment
Deploy A Hugging Face Pretrained Model to Amazon SageMaker Serverless Endpoint - Boto3

[https://studiolab.sagemaker.aws/import/github/aws/studio-lab-examples/blob/main/connect-to-aws/Access_AWS_from_Studio_Lab_Deployment.ipynb](https://studiolab.sagemaker.aws/import/github/aws/studio-lab-examples/blob/main/connect-to-aws/Access_AWS_from_Studio_Lab_Deployment.ipynb)

## cheat sheet

### venv
create venv
```bash
python3 -m venv .venv
```

activate venv
```bash
source .venv/bin/activate
```

### Docker
build docker image
```bash
docker build -t main:latest .
```

