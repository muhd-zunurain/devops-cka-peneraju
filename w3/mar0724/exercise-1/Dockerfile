FROM node:hydrogen-alpine3.18
WORKDIR /usr/src/app
COPY . .
RUN ls && npm install
EXPOSE 3000
CMD ["node", "index.js"]