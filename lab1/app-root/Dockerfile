FROM node:18

WORKDIR /app

COPY public/ /app/public

RUN npm install -g serve

EXPOSE 8080

CMD ["serve", "-s", "public", "-l", "8080"]
