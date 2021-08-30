FROM node:lts
WORKDIR /chat-app
COPY . .
RUN yarn
EXPOSE 7001
CMD ["yarn", "watch"]