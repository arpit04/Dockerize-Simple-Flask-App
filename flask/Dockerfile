#Use the Python3.7.2 container image
FROM python:3.7.2-stretch

#Set the working directory to /app
WORKDIR /app

#Copy the current directory contents into the container at /app
ADD . /app

#Install the dependencies
RUN pip install -r requirements.txt

#run the command
# use CMD ["python", "./run.py"] for run python file to your server
CMD ["echo", "hello aliens"]
