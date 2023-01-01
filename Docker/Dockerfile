FROM node:14
ENTRYPOINT ["docker-entrypoint.sh"]
WORKDIR /usr/src/app
COPY package*.json app.js ./
RUN npm install
EXPOSE 3000
CMD ["node", "app.js"]
