FROM node:9.11.1-alpine
WORKDIR /project
COPY . /project
RUN npm install
RUN npm install -g create-react-app
RUN create-react-app myapp
