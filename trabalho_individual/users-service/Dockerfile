FROM node:lts
WORKDIR /users-service/
COPY . .
RUN npm install 
EXPOSE 7101
CMD ["sh","-c","npm run watch"]