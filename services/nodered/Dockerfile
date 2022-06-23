FROM nodered/node-red:latest
USER root
RUN apk update && apk add --no-cache eudev-dev
USER node-red


RUN cd /usr/src/node-red && npm install --save  node-red-node-serialport 
RUN cd /usr/src/node-red && npm install --save  node-red-configurable-ping
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-boolean-logic
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-bigtimer
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-dwd-local-weather
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-influxdb
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-light-scheduler
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-modbus
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-moving-average
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-state-machine
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-sun-position
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-tplink-iot
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-ui-level 
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-ui-multistate-switch
RUN cd /usr/src/node-red && npm install --save  node-red-contrib-zigbee2mqtt
RUN cd /usr/src/node-red && npm install --save  node-red-dashboard
RUN cd /usr/src/node-red && npm install --save  node-red-node-geofence
RUN cd /usr/src/node-red && npm install --save  node-red-node-ui-lineargauge
