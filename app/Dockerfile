FROM node:10-alpine
RUN apk add g++ make python
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "/app/src/index.js"]