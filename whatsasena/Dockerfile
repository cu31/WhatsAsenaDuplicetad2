FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cu31/WhatsAsenaDuplicetad2 /root/WhatsAsenaDuplicetad2
WORKDIR /root/WhatsAsenaDuplicetad2/
RUN git clone https://github.com/cu31/WhatsAsenaDuplicetad2
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit


CMD ["node", "bot.js"]
