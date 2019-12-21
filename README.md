# Youtube-dl

# Download Youtube playlists and videos in HD format and save according to filename/playlist_name.

# For Playlist
youtube-dl -f 22 -i -o "Path/%(playlist_title)s/%(playlist_index)s - %(title)s.%(ext)s" https://www.youtube.com/playlist?list=PL-osiE80TeTuRUfjRe54Eea17-YfnOOAx

# For Videos
youtube-dl -f 22 -i -o "%(title)s.%(ext)s" https://www.youtube.com/watch?v=HVsySz-h9r4
