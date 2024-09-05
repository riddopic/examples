FROM python:3.12.5-alpine
COPY . /app
WORKDIR /app
EXPOSE 80
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["helloworld.py"]