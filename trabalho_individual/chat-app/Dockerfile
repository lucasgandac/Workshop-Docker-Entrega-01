FROM node:lts
WORKDIR /chat-app
COPY package.json ./
COPY yarn.lock ./
RUN yarn install 
CMD ["npm", "start"]
