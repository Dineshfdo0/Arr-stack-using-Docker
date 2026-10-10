# Arr-stack-using-Docker
 # RADARR – Movies     7878:7878   # SONARR - TV Shows   8989:8989   # LIDARR - Music   8686:8686   # BAZARR - Subtitles   6767:6767   # PROWLARR - Indexer Manager   9696:9696   # QBITTORRENT - Downloader   - 8080:8080   - 6881:6881   - 6881:6881/udp   # JELLYFIN - Media Server   8096:8096  

###########################################################################

###########################################################################

Create folder structure as per this TRASH GUIDE now:

sudo mkdir -p /data/{torrents/{tv,movies,music},media/{tv,movies,music}}
sudo apt install tree
tree /data
sudo chown -R 1000:1000 /data
sudo chmod -R a=,a+rX,u+w,g+w /data
ls -ln /data

###########################################################################

###########################################################################
