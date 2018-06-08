## To run server:

### Open command prompt and copy/paste the following (first=std, second=optimized):

java -Xmx1024M -Xms1024M -jar minecraft_server.1.12.2.jar nogui

java -Xms2048M -Xmx2048M -Djava.net.preferIPv4Stack=true -XX:MaxPermSize=128M -XX:UseSSE=3 -XX:-DisableExplicitGC -XX:+UseParallelOldGC -XX:ParallelGCThreads=4 -XX:+AggressiveOpts -XX:+UseCompressedStrings -jar minecraft_server.1.12.1.jar nogui

*Server IP:* **73.213.13.208**

