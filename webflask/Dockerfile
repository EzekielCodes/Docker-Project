FROM ubuntu 

RUN apt-get update 
RUN apt-get install python3-pip -y
RUN pip3 install flask 
ADD index.py /
WORKDIR /
EXPOSE 8001
ENV VALUE="Eerste site"
CMD ["python3" ,"index.py"]