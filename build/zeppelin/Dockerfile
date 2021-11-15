FROM apache/zeppelin:0.10.0

USER root
RUN apt update
RUN apt install net-tools

RUN pip install influxdb
RUN pip install papermill
RUN pip install python-kucoin
RUN pip install xlrd openpyxl
RUN pip install jupyter
RUN pip install grpcio
RUN pip install protobuf
RUN pip install jupyter-client ipykernel
RUN pip install pivottablejs

USER 1000