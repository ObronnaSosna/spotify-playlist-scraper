# spotify-playlist-scraper
It's a simple script that scrapes all important metadata from spotify playlist and saves it to .csv file without need to add an app to your spotify account.
## INSTALL
```
git clone https://github.com/ObronnaSosna/spotify-playlist-scraper.git
cd spotify-playlist-scraper
pip3 install -r requirements.txt
```
## USAGE
```
python3 sps.py <playlist id>
```
It will create file in your current directory with metadata named \<playlist id\>\.csv
## How to get playlist id
You can get playlist id from share link in spotify app. Id is everything after playlist/ and before ?si
For example in:
```
https://open.spotify.com/user/spotifycharts/playlist/37i9dQZEVXbMDoHDwVN2tF?si=Dd2q7nM4SC6w_En1zy85_w
```
id is
```
37i9dQZEVXbMDoHDwVN2tF
```
