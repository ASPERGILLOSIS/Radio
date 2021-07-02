# Radio
Radio setup based on MPD.FM (https://github.com/florianheinemann/MPD.FM)





## Stations update

### Manual way:
```
su srv-mpd-fm
```
```
nano /home/srv-mpd-fm/MPD.FM/data/stations.json
```

### Automatic way:
```
su srv-mpd-fm
```
```
cd /home/srv-mpd-fm
```
```
rm -rf Radio && git clone https://github.com/ASPERGILLOSIS/Radio/ && mv /home/srv-mpd-fm/Radio/stations.json /home/srv-mpd-fm/MPD.FM/data/stations.json
```
