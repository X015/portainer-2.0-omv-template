# Portainer 2.0 Application Template for Docker

# Instructions

You should be using OpenMediaVault as your OS on your NAS.  
Add the following Shares to your OMV  

- appdata
- books
- comics
- downloads
- logs
- movies
- music
- playlists
- podcasts
- tv

Search for "/srv/dev-disk-by-id-md-name-Nexus-0/appdata" and replace it with your config path.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/books" and replace it with the path to your books.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/comics and replace it with the path to your comics.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/downloads and replace it with the path to your download folder  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/logs and replace it with the path to your log folder.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/movies and replace it with the path to your movies.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/music replace with music folder path.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/playlists replace with playlist folder path.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/podcasts replace with podcasts folder path.  
Search for "/srv/dev-disk-by-id-md-name-Nexus-0/tv replace with path to your tv shows.  

# How to find the Paths?!

1. Login to your OMV Dashboard
2. Go to Access Right Managment on the left side and click on Shared Folder
3. Make a right Click on the Absolute Path and click Inspect Element and Copy the path -> Search, Replace and Repeat with the next Shared Folder
   If you cant see any Absolute Paths the Mouse Over the Name Column and press on the Arrow pointing down and select Absolute Path.
   
   
# Screenshots:

![Screenshot](/Images/Screenshot/screenshot.png)

Source: https://github.com/SelfhostedPro/selfhosted_templates/tree/OMV5  
BIG TY to @ https://github.com/SelfhostedPro for the Idea!!
