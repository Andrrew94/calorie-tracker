FROM node:16.14.0
WORKDIR /var/www/calories
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8001
CMD ["npm", "start"]
# ENTRYPOINT ["tail", "-f", "/dev/null"]
