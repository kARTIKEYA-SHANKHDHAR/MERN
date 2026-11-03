FROM node:20

WORKDIR /app

COPY . .

RUN cd server && npm install
RUN cd client && npm install && npm run build

EXPOSE 3000

CMD ["npm", "start"]