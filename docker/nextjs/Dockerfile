FROM node:18-alpine

WORKDIR /opt/app

COPY package.json *.lock ./
RUN yarn install --frozen-lockfile

CMD ["yarn", "dev"]