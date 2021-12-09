## Important commands -
conda create --prefix ./env python=3.7 -y && conda activate ./env && pip install -r requirement.txt

mlflow ui

mlflow server \
--backend-store-uri sqlite:///mlflow.db \
--default-artifact-root ./artifacts \
--host 127.0.0.1 -p 1234

git init
[do the "first commit"-- public repository]
