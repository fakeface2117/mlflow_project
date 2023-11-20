FROM python:3.11

WORKDIR /app

RUN pip install --upgrade pip && \
    pip install --no-cache-dir 'mlflow==1.26.1'

CMD mlflow server \
    --host 0.0.0.0
    #--default-artifact-root $ARTIFACT_ROOT \
#     --backend-store-uri sqlite:////app/mlruns.db \