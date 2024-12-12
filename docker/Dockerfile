FROM python:3.10

RUN apt-get update && apt-get install -y curl

RUN apt-get install nano -y

WORKDIR /app

COPY . /app

RUN python -m pip install --upgrade pip

RUN pip install --no-cache-dir -r requirements.txt

CMD ["bash"]