FROM python:3.12.0a1-alpine
COPY . /python
WORKDIR /python
RUN pip install -r requirements.txt
CMD python /python/app.py
