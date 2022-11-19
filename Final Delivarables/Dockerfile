FROM python:3
WORKDIR /app
ADD . /app
RUN python3 -m pip install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["app.py"]
