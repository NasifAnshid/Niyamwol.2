FROM fusuf/whatsasena:latest

RUN git clone https://github.com/NasifAnshid/Niyamwol.2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/NasifAnshid/Niya-media

CMD ["node", "bot.js"]
