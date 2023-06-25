FROM steamcmd/steamcmd:latest

USER satisfactory
WORKDIR /home/satisfactory/FactoryGameServer/install

RUN steamcmd +force_install_dir . +login anonymous +app_update 1690800 -beta experimental validate +quit 

CMD ["bash", "FactoryServer.sh"]
EXPOSE 15777
