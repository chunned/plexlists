Plexlists is an application that facilitates creating more advanced playlists and collections than are possible by default in Plex.

The initial focus of the project is on music libraries.

# Plex API Documentation
- [URL Commands](https://support.plex.tv/articles/201638786-plex-media-server-url-commands/)
- [Plexopedia](https://www.plexopedia.com/plex-media-server/api/)
- [Plexapi.dev](https://plexapi.dev/Intro)

# SDK
- [plexpy](https://github.com/LukeHagar/plexpy)


# Plans
- Have not yet thought about the real structure of the application and its feature set. The main idea is having a way to create and manage playlists, avoiding the shortcomings of building playlists in Plex directly. 
- Also just a general alternative to making playlists in Plex. I hate the Plex UI for smart playlists
  - Additionally, some fields available for smart playlists don't always work. For instance, I am unable to create a collection of The Simpsons episodes airing before a certain year, despite all episodes having the necessary metadata

Examples:
- List of completed albums (every track having at least 1 listen)
- Artist playlists
  - Plex can easily make a smart playlist based on track artist, but what about tracks the artist is only featured on?


## Misc
- Want it to be a TUI app
- Consider switching to Go before moving too far with Python (for no reason other than I want to get better at Go)
- Probably will have playlists defined as configuration files that state the properties of the playlist
- Avoid modifying any existing playlists not created by PlexLists
- Random list of albums
  - [Ref](https://old.reddit.com/r/plexamp/comments/1hwode7/album_plays_filter_behaviour/m63ba9t/)
  - Create a playlist from a group of albums. Shuffle the albums, but keep the track listings for each individual album in order. User can then press play (non-shuffle) to listen to the albums in random order.
  - Reordering would require rerunning the application

## To Do
- Look at how Kometa manages playlists
- Look into TUI libraries
- Search Plex + PlexAmp subreddits and forums for things people want that are not possible
  - [1](https://old.reddit.com/r/plexamp/comments/1hwode7/album_plays_filter_behaviour/)

