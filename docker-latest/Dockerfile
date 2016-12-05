FROM tnarihi/dl-base:latest

RUN pip install chainer==1.4
RUN pip install gym
RUN pip install futures
RUN wget https://github.com/google/protobuf/releases/download/v3.1.0/protoc-3.1.0-linux-x86_64.zip \
    && unzip protoc-3.1.0-linux-x86_64.zip -d protoc \
    && cp protoc/bin/protoc /usr/local/bin \
    && chmod +x /usr/local/bin/protoc \
    && rm -rf protoc*
RUN pip install "protobuf>=3"
