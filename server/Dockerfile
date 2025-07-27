FROM node:22-alpine

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 3000

CMD ["node", "index.js"] 
# this cmd runs when the image is called in engine only
# upr wala baki sab image creation k haa isko chor k

#cmd - "docker build -t name_of_image ."