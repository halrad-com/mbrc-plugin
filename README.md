# MusicBee Remote Control Plugin (MBRC)

  MusicBee plugin that enables remote control of your music library over your network.

  **[Download & Documentation](https://halrad.com/MBXRemote/plugin.html)**

  ## About

  This is a fork of the original [MBRC Plugin](https://github.com/musicbeeremote/plugin) by (kelsos).

  ## What it does

  - Exposes MusicBee to remote clients over your local network
  - Works with MBXRemote and other MBRC-compatible clients
  - Controls playback, library browsing, playlists, and more

  ## Changes from original

  - fork with new features and updates
  
    
ARiA Features (v1.5.26.3+)

    Remote Keyboard Automation: Execute keyboard commands on the MusicBee host
    Tab Navigation: Switch MusicBee UI tabs remotely using RIA1-10 hotkeys
    Focus Control: Send keys to MusicBee (!mb!) or current window (!nofocus!)
    Command Chaining: Execute multiple commands with delays (sndKeys();delay();sndKeys())
    Security Toggle: ARiA can be enabled/disabled in plugin settings

Enhancements Over Standard Plugin

    Enhanced Metadata: Album and artist counts included in library browsing
    Extended Track Data: Library tracks include Year, Rating, Bitrate, Format, PlayCount, SkipCount, LastPlayed, and Loved fields
    Protocol Negotiation: Plugin responds with v4.5 features when requested by the client
    Library Subscriptions: Plugin supports real-time library change notifications - clients can subscribe to receive updates when tracks are modified, rated, played, or deleted
    Remote Library Editing: Edit ratings and love status remotely - changes write back to MusicBee library instantly


# Designed for MBXRemote

  Windows desktop client for MusicBee Remote Plugin.

  **[Download | Sources & Documentation](https://halrad.com/MBXRemote/)**

  Part of [HALRAD Research](https://halrad.com)

  # MusicBee Remote Control Plugin

  **[More info](https://halrad.com/MBXRemote/plugin.html)**

  ## Credits

  Original MBCR plugin by [Konstantinos Paparas](https://github.com/kelsos) and the [MusicBee Remote](https://github.com/musicbeeremote) project.
