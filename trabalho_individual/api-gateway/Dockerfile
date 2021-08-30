FROM node:lts
WORKDIR /api-gateway
COPY . .
RUN yarn
EXPOSE 7001
CMD ["yarn", "watch"]