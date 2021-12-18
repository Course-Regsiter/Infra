FROM node:14
WORKDIR /usr/src/app
COPY Course-Server .
WORKDIR /usr/src/app/Course-Server
RUN npm install
EXPOSE 4000
CMD ["npm", "start"]