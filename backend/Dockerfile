FROM node:latest
WORKDIR /app
RUN apt-get update && apt-get upgrade -y
COPY . .
RUN npm i
COPY .env.sample .env
EXPOSE 5000
CMD ["npm", "start"]
