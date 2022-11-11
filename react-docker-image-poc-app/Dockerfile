FROM node:19-alpine as baseImage 

WORKDIR /App

COPY ./package.json /App/

RUN npm install

COPY . /app
# copy all the stuffs from the base to /app directory 
CMD ["npm" "start"]