FROM obsidiandynamics/kafdrop

RUN rm -r /kafdrop-3.30.0
RUN mkdir kafdrop-3.31.0
copy /kafdrop-3.31.0 /kafdrop-3.31.0 \
COPY <filename>.zip /
RUN unzip <filename>.zip
RUN rm <filename>.zip

ENTRYPOINT ["/kafdrop.sh"]