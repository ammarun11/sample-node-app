FROM node:14
ENTRYPOINT ["docker-entrypoint.sh"]
WORKDIR /usr/src/app
COPY package*.json app.js ./
ENTRYPOINT ["docker-entrypoint.sh"]
RUN npm install
EXPOSE 3000
CMD ["node", "app.js"]
