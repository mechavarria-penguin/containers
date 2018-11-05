FROM tensorflow/tensorflow:latest-gpu

RUN apt-get update && apt-get -y install git
RUN cd / && git clone https://github.com/tensorflow/benchmarks.git
RUN cd /benchmarks && git checkout cnn_tf_v1.11_compatible
RUN pip install portpicker
