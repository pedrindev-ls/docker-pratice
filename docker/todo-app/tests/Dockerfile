FROM mjgargani/puppeteer:trybe1.0 as todotests
WORKDIR /tests
ADD node_modules.tar.gz /tests
COPY package*.json ./
ENTRYPOINT [ 'npm', 'test' ]