FROM python:slim

WORKDIR /app

COPY requirement.txt .

RUN pip install -r requirement.txt

COPY panda_demo.py .

CMD ["python", "panda_demo.py"]