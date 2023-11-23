FROM node:20.9.0-bullseye

WORKDIR /front

COPY package.json package-lock.json ./
RUN npm install --frozen-lockfile

COPY . .

EXPOSE 3000
EXPOSE 6006
