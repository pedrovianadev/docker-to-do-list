FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
EXPOSE 3001
COPY ./ ./
ADD node_modules.tar.gz .
ENTRYPOINT ["npm"]
CMD ["start"]
