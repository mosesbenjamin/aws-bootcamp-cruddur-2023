FROM node:16.18

ENV PORT=3000

COPY . /frontend-react-js
WORKDIR /frontend-react-js
RUN npm install
RUN chmod +x ./script.sh
EXPOSE ${PORT}
CMD ["./script.sh"]