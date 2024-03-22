FROM python:3.9.19-alpine
COPY . /app
WORKDIR /app
EXPOSE 80
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["helloworld.py"]