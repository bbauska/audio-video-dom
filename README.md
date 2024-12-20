# audio-video-dom
## audio, video and the dom.
### HTML Audio and Video DOM Reference

The HTML5 DOM has methods, properties, and events for the <audio> and <video> elements.

### HTML Audio/Video Methods

| Method   | Description |
|----------|-------------------------------|
| addTextTrack() | Adds a new text track to the audio/video |
| canPlayType() | Checks if the browser can play the specified audio/video type |
| load() | Re-loads the audio/video element |
| play() | Starts playing the audio/video |
| pause() | Pauses the currently playing audio/video |

### HTML Audio/Video Properties
| Property	 | Description |
|:-----------:|---------------------------|
| audioTracks | Returns an AudioTrackList object representing available audio tracks |
| autoplay | Sets or returns whether the audio/video should start playing as soon as it is loaded |
| buffered | Returns a TimeRanges object representing the buffered parts of the audio/video |
| controller | Returns the MediaController object representing the current media controller of the audio/video |
| controls | Sets or returns whether the audio/video should display controls (like play/pause etc.) |
| crossOrigin | Sets or returns the CORS settings of the audio/video |
| currentSrc | Returns the URL of the current audio/video |
| currentTime | Sets or returns the current playback position in the audio/video (in seconds) |
| defaultMuted | Sets or returns whether the audio/video should be muted by default |
| defaultPlaybackRate | Sets or returns the default speed of the audio/video playback |
| duration | Returns the length of the current audio/video (in seconds) |
| ended | Returns whether the playback of the audio/video has ended or not |
| error | Returns a MediaError object representing the error state of the audio/video |
| loop | Sets or returns whether the audio/video should start over again when finished |
| mediaGroup | Sets or returns the group the audio/video belongs to (used to link multiple audio/video elements) |
| muted | Sets or returns whether the audio/video is muted or not |
| networkState | Returns the current network state of the audio/video |
| paused | Returns whether the audio/video is paused or not
| playbackRate | Sets or returns the speed of the audio/video playback |
| played | Returns a TimeRanges object representing the played parts of the audio/video |
| preload | Sets or returns whether the audio/video should be loaded when the page loads |
| readyState | Returns the current ready state of the audio/video |
| seekable | Returns a TimeRanges object representing the seekable parts of the audio/video |
| seeking | Returns whether the user is currently seeking in the audio/video |
| src | Sets or returns the current source of the audio/video element |
| startDate | Returns a Date object representing the current time offset |
| textTracks | Returns a TextTrackList object representing the available text tracks |
| videoTracks | Deprecated. Do not use it. |
| volume | Sets or returns the volume of the audio/video |

