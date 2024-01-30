FROM tiangolo/uvicorn-gunicorn-fastapi:python3.9

COPY ./requirements.txt /app/requirements.txt
COPY ./bikeshare_model-0.0.1-py3-none-any.whl /app/bikeshare_model-0.0.1-py3-none-any.whl

RUN pip install -r /app/requirements.txt

COPY ./app /app