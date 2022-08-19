FROM node:alpine
WORKDIR /usr/abdur/subscriber
COPY  subscriber.js /usr/abdur/subscriber
RUN npm install mqtt
CMD ["node","subscriber.js"]