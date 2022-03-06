FROM debian
RUN apt update
RUN apt install python3-pip -y
WORKDIR /app
COPY . .
RUN pip3 install -r requirements.txt
EXPOSE 5000
CMD [ "python3",  "app.py"]]

 
