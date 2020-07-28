FROM node:10.0-alpine
ADD . /app
WORKDIR /app
RUN npm config set package-lock false
RUN npm install
EXPOSE 80
CMD ["npm", "start"]