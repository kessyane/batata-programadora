class Spotify {
  constructor() { 
    this.playlists = {};
 }

// adicionar uma musica 
addSong(title, artist) {
this.songs.push({ title, artist });
}

// criar uma playlist
createplaylist(name) {
this.playlist[name] = [];
}

// adicionar uma musica a uma playlist
addsongToplaylist(playlistName, songTitle) {
 const
