FROM node:16

WORKDIR /workdir

COPY ./ ./

RUN npm install

EXPOSE 9080

CMD ["sh", "-c", "node ratings.js 9080"]
