# PlayNext Command

## Description:
**Play songs!**
If the user is in a voice channel and there's no song playing, I'll join your channel before starting.
If I'm already playing a song, this command will add the song to the begin of the queue.

## Usage:
`ad!playnext` + attachment - Loads and plays the song from the attachment.

`ad!playnext <song url>` - Loads and plays the song from the URL.

`ad!playnext [youtube/yt] <search term>` - Searches for the video in Youtube.

`ad!playnext <soundcloud/sc> <search term>` - Searches for the song in SoundCloud.

## Note:
**Magic Prefixes**:
`ad!play --volume <volume> <...>` - Sets the volume of the player.
`ad!play --repeat <mode> <...>` - Sets the repeat mode of the player.
`ad!play --shuffled <...>` - Shuffles the order of the playlist added. Has no effects on single tracks.
(You need the permissions to set the volume or the repeat mode)

**Aliases**:
 - Volume: `--vol`, `-v`
 - Repeat: `-r`
 - Shuffle Playlists: `-s`

## See Also:
`play` `playnow` `forceplay` `forceplaynow` `forceplaynext`
