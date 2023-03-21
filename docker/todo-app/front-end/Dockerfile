FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
EXPOSE 3000
ADD node_modules.tar.gz .
COPY ./ ./
ENTRYPOINT ["npm"]
CMD ["start"]