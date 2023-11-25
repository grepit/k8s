# this is basic docker file we are using for k8 project
FROM node:alpine
WORKDIR /app
EXPOSE 3000
COPY package.json package-lock.json ./
RUN npm install
# how we are copying the code from local to our image
COPY . ./
CMD ["npm", "start"]
