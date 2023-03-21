FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY node_modules.tar.gz .
COPY ./ ./
ENTRYPOINT [ "npm" ]
CMD ["test"]
