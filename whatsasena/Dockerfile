FROM fusuf/whatsasena:latest

RUN git clone https:// https://github.com/Hisham-Muhammed/Sophia/pullsroot/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
