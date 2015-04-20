## Plex Media Server plugin for channel PEAR ##

1. [Introduction][1]
2. [Installation][2]
3. [Load your Library][3]
4. [Compatible devices][4]
5. [Credits][5]
6. [License][6]

### Introduction ###
This plugin provides access to your channel PEAR library via Plex.

### Installation ###
1. Must have [Plex Media Server][GetPlex] installed
2. Must have a channel PEAR account with sources in your library
3. Download the archive and extract it to the Plex plugin folder, for more details read the [official channel installation guide](https://support.plex.tv/hc/en-us/articles/201187656-How-do-I-manually-install-a-channel-):
  * on Windows: *C:\Users\USERNAME\AppData\Local\Plex Media Server\Plug-ins\*
  * on Mac: *~Library/Application Support/Plex Media Server/Plug-ins/*
  * on Linux: */usr/lib/plexmediaserver/Resources/Plug-ins* or */var/lib/plex/Plex Media Server/Plug-ins/*
  * on FreeBSD *usr/pbi/plexmediaserver-amd64/plexdata/Plex\ Media\ Server/Plug-ins/*
4. Rename folder from **channelpear.bundle-master** to **channelpear.bundle**
5. Restart Plex Media Server

### Load your Library ###
Once you've installed the plugin successfully, you'll need to link it to your channel PEAR library. **The plugin will not work until you complete this step**

### Compatible devices ###
Streams **will play only on clients that are able to handle the stream natively**. Below is a list of devices that support playback to some extent:

* **Desktop Clients**:
  * **[Plex Media Center]** - plays most streams without problems
* **Connected Devices**:
  * **Plex for LG TV ([MediaLink])** plays HTTP and RTSP streams
  * **[PlexConnect](https://forums.plex.tv/index.php?/topic/69410-READ-BEFORE-POSTING) (Apple TV)** - plays most streams without problems, may need to alternate between transcoding options
  * **[Plex for Roku][GetPlex]** - plays most streams without problems
  * **[Plex for Chromecast][GetPlex]** - not tested
  * **[Plex for Google TV][GetPlex]** - not tested
  * **[Plex for Samsung][GetPlex]** - not tested
* **Mobile Devices**:
  * **[Plex for Android][GetPlex]** - not tested, however devices with Android 4.1+ support m3u8 playback which means you can access your library directly from the channelpear.com website and play streams via Chrome
  * **[Plex for iOS][GetPlex]** - not tested, however iOS supports m3u8 playback matively which means you can access your library directly from the channelpear.com website and play streams

### Credits ###
* Developer: [channel PEAR]
* built off of the original IPTV.bundle plugin by Cigaras

### License ###
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](http://www.gnu.org/copyleft/gpl.html) for more details.

  [1]: #introduction "Introduction"
  [2]: #installation "Installation"
  [3]: #load-your-library "Load your Library"
  [4]: #compatible-devices "Compatible devices"
  [5]: #credits "Credits"
  [6]: #license "License"
  [channel PEAR]: https://channelpear.com/
  [IPTV]: http://en.wikipedia.org/wiki/IPTV
  [GetPlex]: https://www.plex.tv/downloads
  [Plex Web]: https://support.plex.tv/hc/en-us/articles/200288666-Opening-Plex-Web-App
  [Plex Media Center]: https://support.plex.tv/hc/en-us/articles/201142378--Deprecated-Plex-Media-Center-Windows-OS-X
  [MediaLink]: http://www.plexapp.com/medialink
