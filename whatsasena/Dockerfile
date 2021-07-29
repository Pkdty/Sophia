FROM fusuf/whatsasena:latest

RUN gitclonehttps://github.com/Pkdty/Sophia/root/WhatsAsenaDuplicated
WORKDIR/root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
