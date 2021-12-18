FROM node:14
WORKDIR /usr/src/app
COPY Backend .
WORKDIR /usr/src/app/Backend
RUN npm install
EXPOSE 4001
CMD ["npm", "start"]