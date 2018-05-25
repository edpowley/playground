FROM rikorose/gcc-cmake:gcc-6

COPY . /ismcts
RUN mkdir /ismcts/build
WORKDIR /ismcts/build
RUN cmake ..
RUN make
CMD ["./main"]

