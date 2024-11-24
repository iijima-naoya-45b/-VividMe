FROM node:20.11.0

ENV TZ Asia/Tokyo

WORKDIR /app

COPY package.json  /app/
RUN npm install

COPY . /app

CMD ["yarn", "dev", "-p", "4000"]
