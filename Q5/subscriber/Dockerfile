FROM node:alpine
WORKDIR /usr/sharukh/subscriber
COPY subscriber.js /usr/sharukh/subscriber
RUN npm install mqtt
CMD ["node", "subscriber.js"]

