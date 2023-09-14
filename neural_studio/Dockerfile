FROM node:20-buster-slim

EXPOSE 5175

WORKDIR /svelte

COPY ./front_end /svelte/

RUN npm install --registry http://registry.npm.taobao.org

CMD [ "sh", "-c", "npm run dev" ]