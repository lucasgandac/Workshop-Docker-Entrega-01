FROM node:lts
WORKDIR /chat-service
COPY . .
RUN yarn
EXPOSE 7100
CMD ["yarn", "watch"]