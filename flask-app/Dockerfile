#Base image with python
FROM python:3.9

#Working directory for app
WORKDIR app/

#Copy the code from system
COPY app.py .

#install required library
RUN pip install flask

#Run the application

CMD ["python","app.py"]
