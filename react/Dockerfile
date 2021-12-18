FROM node:14
WORKDIR /usr/src/app
COPY Frontend .
WORKDIR /usr/src/app/Frontend
RUN npm install
EXPOSE 3000
CMD ["npm", "start"]