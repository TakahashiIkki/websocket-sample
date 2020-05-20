FROM node:12

# アプリケーションディレクトリを作成する
ENV APP_PATH /src

RUN mkdir -p $APP_PATH

WORKDIR $APP_PATH

# App
ADD . $APP_PATH

# Install app dependencies
RUN npm install

EXPOSE  3000

CMD ["node", "/src/index.js"]