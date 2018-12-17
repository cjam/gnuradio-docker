FROM cjam/gnuradio:latest

RUN apt-get update && apt-get dist-upgrade -yf && apt-get clean && apt-get autoremove
RUN apt-get install -y \
        libcppunit-dev

CMD ["/bin/bash"]
