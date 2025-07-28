FROM python:3.9-slim
WORKDIR /app
COPY app.py .
RUN pip install --upgrade pip && \
    pip install --no-warn-script-location flask || true
CMD ["python", "app.py"]
