FROM python:3.14.0a1-alpine
COPY . /app
WORKDIR /app
EXPOSE 80
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["helloworld.py"]