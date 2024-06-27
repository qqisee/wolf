FROM node:16-alpine


COPY ./ /opt/wolf/server
WORKDIR /opt/wolf/server
RUN npm install

EXPOSE 12180
ENTRYPOINT ["sh", "./entrypoint.sh"]
