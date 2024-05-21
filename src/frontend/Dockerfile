FROM nginx

WORKDIR /app


CMD ["uvicorn", "bisheng.main:app", "--workers", "2",  "--host", "0.0.0.0", "--port", "7860"]
