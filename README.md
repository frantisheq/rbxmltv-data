cz-sk.xml - czech & slovak xmltv file

For Enigma2 sat receivers:
- CrossEPG - download frantisheq_xmltv.conf to /usr/crossepg/providers
- ImportEPG - download frantisheq.sources.xml to /etc/epgimport


If there is guide missing or incorrect and it's available on tvp.cz you'll need to provide name of the channel on tvp.cz, name of the channel on your satellite receiver including satellite position and numbers like these 1:0:1:13F1:C87:3:EB0000:0:0:0: which can be found in services.m3u downloaded from your receiver using OpenWebif.
Create an issue or fork, edit frantisheq.channels.xml and submit pull request.

An example from services.m3u playlist for Jednotka on Skylink:

#EXTINF:-1 tvg-chno="4905" tvg-logo="http://..." tvg-id="1:0:19:1329:CA2:3:EB0000:0:0:0:" tvg-name="Jednotka",Jednotka

in frantisheq.channels.xml it'll look like this. 10-stv1 is an xmltv id from cz-sk.xml:

\<!-- 23.5E -->\<channel id="10-stv1">1:0:19:1329:CA2:3:EB0000:0:0:0:\</channel>\<!-- Jednotka -->
