FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
EXPOSE 3000
COPY ./ ./
ADD node_modules.tar.gz .
ENTRYPOINT ["npm"]
CMD ["start"]