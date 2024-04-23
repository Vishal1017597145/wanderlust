FROM node:latest
WORKDIR /app
COPY . .
RUN apt update && apt upgrade -y
RUN npm i
COPY .env.sample .env.local
EXPOSE 5173
CMD ["npm" ,"run", "dev", "--", "--host"]
