FROM python:alpine3.10 # base image where we start building our docker image.
WORKDIR /app # Set working directory
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 5000
CMD python ./launch.py

#COPY requirements.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]
