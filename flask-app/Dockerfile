FROM python:3.10

#set working directory
WORKDIR /usr/src/app

#copy all files to container
COPY . .

#install dependencies
RUN pip install --no-cache-dir -r requirements.txt

#Define the port number to be exposed
EXPOSE 5000

#Run the command
CMD ["python", "app.py"]
