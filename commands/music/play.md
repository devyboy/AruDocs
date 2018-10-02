# Play Command

## Description:
**Play songs!**
If the user is in a voice channel and there's no song playing, I'll join your channel before starting.
If I'm already playing another song, the song will be added to the end of the queue.

## Usage:
`ad!play` + attachment - Loads and plays the song from the attachment.

`ad!play <song url>` - Loads and plays the song from the URL.

`ad!play [youtube/yt] <search term>` - Searches for the video in Youtube.

`ad!play <soundcloud/sc> <search term>` - Searches for the song in SoundCloud.

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
`playnow` `playnext` `forceplay` `forceplaynow` `forceplaynext`
