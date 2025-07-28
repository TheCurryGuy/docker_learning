FROM node:22-alpine

WORKDIR /app

COPY ./package.json /app/package.json

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "index.js"] 
# this cmd runs when the image is called in engine only
# upr wala baki sab image creation k haa isko chor k

#cmd - "docker build -t name_of_image ."