FROM node:14.18.0

WORKDIR /app

COPY ./ ./
RUN npm install

EXPOSE 8500
CMD ["node", "index.js"]