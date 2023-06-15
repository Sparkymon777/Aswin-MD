FROM node:latest
RUN git clone https://github.com/Sparkymon777/Aswin-MD /root/Aswin-MD
WORKDIR /root/Aswin-MD
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"] 


