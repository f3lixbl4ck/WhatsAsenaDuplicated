FROM fusuf/whatsasena:latest

RUN git clone https://github.com/f3lixl4ck/WhatsAsenaDuplicated /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
