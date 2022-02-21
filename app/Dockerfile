FROM python:3

WORKDIR /opt

RUN python -m pip install --upgrade pip

# The below can be used to install python requirements as needed
#COPY requirements.txt ./
#RUN pip3 install -r requirements.txt

COPY /application /opt

CMD [ "python", "hello_python.py" ]

# Build Image
# docker build -t app ./app/
# Run Image
# docker run -it --name app app 