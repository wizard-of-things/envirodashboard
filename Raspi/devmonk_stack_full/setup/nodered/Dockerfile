FROM nodered/node-red:1.2.0-10-arm32v6
RUN for addonnodes in \
node-red-node-pi-gpiod \
node-red-dashboard \
node-red-contrib-influxdb \
; do \
npm install ${addonnodes} ;\
done;
