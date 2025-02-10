FROM agrigorev/zoomcamp-model:mlops-2024-3.10.13-slim

# do stuff here

RUN pip install pipenv

COPY . /app

WORKDIR /app

RUN pipenv install --system --deploy

ENTRYPOINT ["python", "starter.py"]