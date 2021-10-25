# selfhosted-music-overview

selfhosted-music-overview intends to provide an overview of different self-hostable music streaming sites.




## Server Overview



|                       |     Scrobbling     |     Jukebox Mode     |         Can Read Tags          |         Can Write Tags         |           API            |            Can Share Music             | Multi-User Support | Multi-Library Support |  Smart Playlists   |  Heart/ Favorites  |   5 Star Rating    |    Replay Gain     |     Transcode      |                  free                  |                Demo                 |              Source Code               |     License     | Reviewed Version |
| --------------------- | :----------------: | :----------------------------: | :----------------------------: | :----------------------: | :------------------------------------: | :----------------: | :-------------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :------------------------------------: | :---------------------------------: | :------------------------------------: | :-------------: | :--------------: | :--------------: |
| Airsonic              |                    |                    |                                |                                | subsonic :grey_question: |                                        |                    |                       |                    |                    |                    |                    |                    | :heavy_check_mark: :heavy_dollar_sign: |                                     | :heavy_check_mark: [^github-airsonic]  |      GPLv3      |                  |
| Ampache               |                    |                    |       :heavy_check_mark:       | :heavy_check_mark: File or DB  | subsonic :grey_question: |                                        | :heavy_check_mark: |                       | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: |                                        |  :heavy_check_mark: [^ampachedemo]  |                                        |                 |                  |
| Emby                  |                    |                    |                                |                                |                          |                                        |                    |                       |                    |                    |                    |                    |                    |                                        |                                     |   :heavy_check_mark: [^github-emby]    |      GPLv2      |                  |
| Funkwhale             |                    |                    |                                |                                |     :grey_question:      |           :heavy_check_mark:           |                    |                       |                    |                    |                    |                    |                    |                                        |                                     | :heavy_check_mark: [^gitlab-funkwhale] | :grey_question: |                  |
| Jellyfin              | :heavy_check_mark: |  |       :heavy_check_mark:       |       :heavy_check_mark:       | subsonic :grey_question: |           :heavy_check_mark:           | :heavy_check_mark: |  :heavy_check_mark:   |        :x:         | :heavy_check_mark: |        :x:         |        :x:         | :heavy_check_mark: |                                        | :heavy_check_mark: [^jellyfindemo]  |  :heavy_check_mark:[^github-jellyfin]  |      GPLv2      |                  |
| Koel                  |                    |                    |                                |                                |                          |                                        |                    |                       |                    |                    |                    |                    |                    |                                        |                                     |                                        |                 |                  |
| LMS                   | :heavy_check_mark: |  | :heavy_check_mark: Multi-Value | :heavy_check_mark: Multi-Value |     :grey_question:      |                                        | :heavy_check_mark: |                       | :heavy_check_mark: | :heavy_check_mark: |                    |                    |                    |                                        |    :heavy_check_mark: [^lmsdemo]    |    :heavy_check_mark:[^github-lms]     |      GPLv3      |                  |
| Logitech Media Server | :heavy_check_mark: | :grey_question: | :heavy_check_mark: |      :x:       |     :x:      |       :x:       | :heavy_check_mark: :grey_question: [^review1] | :heavy_check_mark: [^logitech-multi] | :heavy_check_mark: [^logitech-comment-playlist] | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:  | :heavy_check_mark: [^github-logitech] |  GPLv2  |       8.2        |
| Mopidy                |                    |                    |                                |                                |                          |                                        |                    |                       |                    |                    |                    |                    |                    |                                        |                                     |                                        |                 |                  |
| MPD                   |                    |                    |                                |                                |                          |                                        |                    |                       |                    |                    |                    |                    |                    |                                        |                                     |                                        |                 |                  |
| mStream               |                    |                    |                                |                                |     :grey_question:      |           :heavy_check_mark:           |                    |                       |        :x:         |                    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                                        |  :heavy_check_mark: [^mstreamdemo]  |                                        |                 |                  |
| Navidrome             | :heavy_check_mark: |  |       :heavy_check_mark:       |              :x:               | subsonic :grey_question: |           :heavy_check_mark:           | :heavy_check_mark: |      :x:       |     :x:     | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |                                        | :heavy_check_mark: [^navidromedemo] | :heavy_check_mark:[^github-navidrome]  |      GPLv3      |                  |
| Plex                  |                    |                    |       :heavy_check_mark:       |       :heavy_check_mark:       |     :grey_question:      | :heavy_check_mark: :heavy_dollar_sign: | :heavy_check_mark: |  :heavy_check_mark:   | :heavy_check_mark: | :heavy_check_mark: |                    |                    |                    |                                        |   :heavy_check_mark: [^plexdemo]    |   :heavy_check_mark: [^github-plex]    | :grey_question: |                  |
| Serviio               |                    |                    |                                |                                |                          |                                        |                    |                       |                    |                    |                    |                    |                    |                                        |                                     |                                        |                 |                  |
| Subsonic              |                    |                    |                                |                                | subsonic :grey_question: |                                        |                    |                       |                    |                    |                    |                    |                    |                                        |                                     | :heavy_check_mark: [^github-subsonic]  | :grey_question: |                  |







[^plexdemo]: [Plex Demo](https://app.plex.tv/desktop/#!/)
[^jellyfindemo]: [Jellyfin Demo](https://demo.jellyfin.org/)
[^navidromedemo]: [Navidrome Demo](https://www.navidrome.org/demo/)
[^lmsdemo]: [lms Demo](https://lms.demo.poupon.io/)
[^mstreamdemo]: [mstream Demo](https://demo.mstream.io/?)
[^ampachedemo]: [Ampache Demo](https://ampache.org/demo.html)


[^github-plex]: https://github.com/plexinc
[^github-emby]: https://github.com/MediaBrowser/Emby
[^github-jellyfin]: https://github.com/jellyfin/jellyfin
[^github-navidrome]: https://github.com/navidrome/navidrome
[^github-airsonic]: https://airsonic.github.io/
[^github-subsonic]: https://github.com/subsonic
[^gitlab-funkwhale]: https://dev.funkwhale.audio/funkwhale
[^github-lms]: https://github.com/epoupon/lms

[^website-funkwhale]: https://funkwhale.audio/
[^website-mstream]: https://mstream.io/
[^website-ampache]: https://ampache.org/
[^website-mopidy]: https://docs.mopidy.com/
[^website-koel]: https://koel.dev/
[^website-musicpd]: https://www.musicpd.org/
[^website-serviio]: https://www.serviio.org/
[^website-squeezebox]: https://www.mysqueezebox.com/download

[^website-jellyfin]: https://jellyfin.org


[^review1]: needs review
[^logitech-multi]: [Plugin](https://wiki.slimdevices.com/index.php/Multi_Library_plugin.html) 
[^logitech-comment-playlist]: works best if music library has been analysed by MusicIP beforehand, otherwise limited capability
[^github-logitech]: https://github.com/Logitech/slimserver

## Client Overview

|             |   OS    | Gapless Playback |     Album View     |     Songs View     |    Folder View     |    Artist View     |     Genre View     |    Decade View     |     Year View      |  Playlist Support  |  Most Played Song  | Most Played Album  | Recently Played Song | Recently Played Album | Recently Added Song | Recently Added Album | Frequently Played Album |    Offline Mode    |              Download Music               |      Podcasts      |     Scrobbling     |     Scrobbling     |   Similar Songs    |  Artist Top Songs  |    Shuffle Play    |    Random Album    | Favourites / Starred / Bookmark |      5 Stars       |  Search function   | Chromecast Support |  Android Auto   |        mp3         |        opus        |        flac        |     Dark Mode      |     Themeable      |    Open Source     |        free        | Smart Recommendations |   Video Support    |   Internet Radio   | API  |                 f-droid                 |             Source Code             |     License     | Reviewed Version |
| ----------- | :-----: | :--------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :------------------: | :-------------------: | :-----------------: | :------------------: | :---------------------: | :----------------: | :---------------------------------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :-----------------------------: | :----------------: | :----------------: | :----------------: | :-------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :-------------------: | :----------------: | :----------------: | :--: | :-------------------------------------: | :---------------------------------: | :-------------: | :--------------: |
| Gelli       | Android |                  |                    |                    |                    |                    |                    |                    |                    |                    |                    |                    |                      |                       |                     |                      |                         |                    |                                           |                    |                    |                    |                    |                    |                    |                    |                                 |                    |                    |                    |                 |                    |                    |                    |                    |                    | :heavy_check_mark: | :heavy_check_mark: |                       |                    |                    |      |   :heavy_check_mark: [^fdroid-gelii]    |       github [^github-gelli]        |      GPLv3      |      1.3.2       |
| Finamp      | Android |                  |                    |                    |                    |                    |                    |                    |                    |                    |                    |                    |                      |                       |                     |                      |                         | :heavy_check_mark: |            :heavy_check_mark:             |                    |                    |                    |                    |                    |                    |                    |                                 |                    |                    |                    |                 |                    |                    |                    |                    |                    | :heavy_check_mark: | :heavy_check_mark: |                       |                    |                    |      |   :heavy_check_mark: [^fdroid-finamp]   |      github  [^github-finamp]       |     MPL 2.0     |      0.5.1       |
| substreamer | Android |                  | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: |        :x:         |        :x:         |         :x:          |          :x:          |         :x:         |         :x:          |           :x:           | :heavy_check_mark: |            :heavy_check_mark:             | :heavy_check_mark: |        :x:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |        :x:         |       :heavy_check_mark:        |        :x:         | :heavy_check_mark: | :heavy_check_mark: | :grey_question: | :heavy_check_mark: | :heavy_check_mark: |  :grey_question:   | :heavy_check_mark: |        :x:         |        :x:         | :heavy_check_mark: |  :heavy_check_mark:   |        :x:         |        :x:         |      |                   :x:                   |                 :x:                 | :grey_question: |      0.5.1       |
| Ultrasonic  | Android |                  | :heavy_check_mark: |        :x:         |        :x:         | :heavy_check_mark: |        :x:         |        :x:         | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: |         :x:          |  :heavy_check_mark:   |         :x:         |  :heavy_check_mark:  |                         |        :x:         |            :heavy_check_mark:             |                    |        :x:         | :heavy_check_mark: |                    |                    | :heavy_check_mark: |                    |       :heavy_check_mark:        | :heavy_check_mark: | :heavy_check_mark: |        :x:         |       :x:       | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |                    | :heavy_check_mark: | :heavy_check_mark: |                       |                    |                    |      | :heavy_check_mark: [^fdroid-ultrasonic] |     github [^github-ultrasonic]     |      GPLv3      |      2.23.1      |
| Funkwhale   | Android |                  |                    |                    |                    |                    |                    |                    |                    |                    |                    |                    |                      |                       |                     |                      |                         |                    |                                           |                    |                    |                    |                    |                    |                    |                    |                                 |                    |                    |                    |                 |                    |                    |                    |                    |                    | :heavy_check_mark: | :heavy_check_mark: |                       |                    |                    |      | :heavy_check_mark: [^fdroid-funkwhale]  |     gitlab [^gitlab-funkwhale]      |       MIT       |      0.1.4       |
| Subtracks   | Android |                  | :heavy_check_mark: |        :x:         |        :x:         | :heavy_check_mark: |        :x:         |        :x:         |        :x:         | :heavy_check_mark: |        :x:         |        :x:         |         :x:          |  :heavy_check_mark:   |         :x:         |         :x:          |   :heavy_check_mark:    |        :x:         | :grey_question:[^help-subtracks-download] |        :x:         | :heavy_check_mark: |        :x:         |        :x:         |        :x:         | :heavy_check_mark: | :heavy_check_mark: |       :heavy_check_mark:        |        :x:         | :heavy_check_mark: |        :x:         |       :x:       | :heavy_check_mark: | :heavy_check_mark: |  :grey_question:   |   :white_circle:   |        :x:         | :heavy_check_mark: | :heavy_check_mark: |          :x:          |        :x:         |        :x:         |      | :heavy_check_mark: [^fdroid-subtracks]  |     github [^github-subtracks]      |      GPLv3      |      1.0.1       |
| Dsub        | Android |                  |        :x:         |        :x:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: |        :x:         |        :x:         |         :x:          |          :x:          | :heavy_check_mark:  |         :x:          |           :x:           | :heavy_check_mark: |            :heavy_check_mark:             | :heavy_check_mark: |        :x:         |        :x:         |        :x:         |        :x:         | :heavy_check_mark: |        :x:         |       :heavy_check_mark:        | :heavy_check_mark: |        :x:         | :heavy_check_mark: | :grey_question: | :heavy_check_mark: | :heavy_check_mark: |  :grey_question:   |        :x:         |        :x:         | :heavy_check_mark: | :heavy_check_mark: |          :x:          | :heavy_check_mark: | :heavy_check_mark: |      |    :heavy_check_mark: [^fdroid-dsub]    |        github [^github-dsub]        |      GPLv3      |      5.5.2       |
| Audinaut    | Android |                  |                    |                    |                    |                    |                    |                    |                    |                    |                    |                    |                      |                       |                     |                      |                         |                    |                                           |                    |                    |                    |                    |                    |                    |                    |                                 |                    |                    |                    |                 |                    |                    |                    |                    |                    | :heavy_check_mark: | :heavy_check_mark: |                       |                    |                    |      |  :heavy_check_mark: [^fdroid-audinaut]  |      github [^github-audinaut]      |      GPLv3      |   0.5.1 (202)    |
| Subsonic    | Android |                  |                    |                    |                    |                    |                    |                    |                    |                    |                    |                    |                      |                       |                     |                      |                         |                    |                                           |                    |                    |                    |                    |                    |                    |                    |                                 |                    |                    |                    |                 |                    |                    |                    |                    |                    | :heavy_check_mark: | :heavy_check_mark: |                       |                    |                    |      |  :heavy_check_mark: [^fdroid-subsonic]  | sourceforge [^sourceforge-subsonic] |      GPLv3      |     4.4 (59)     |
| Navidrome   |   Web   |                  | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: | :heavy_check_mark: |        :x:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  :heavy_check_mark:  |  :heavy_check_mark:   | :heavy_check_mark:  |  :heavy_check_mark:  |                         |        :x:         |            :heavy_check_mark:             |        :x:         |                    | :heavy_check_mark: |        :x:         |        :x:         | :heavy_check_mark: |                    |       :heavy_check_mark:        |        :x:         | :heavy_check_mark: |                    |                 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |          :x:          |        :x:         |        :x:         |      |             :white_circle:              |     github [^github-navidrome]      |      GPLv3      |      0.46.0      |

[^fdroid-gelii]: https://f-droid.org/en/packages/com.dkanada.gramophone/
[^github-gelli]: https://github.com/dkanada/gelli
[^fdroid-finamp]: https://f-droid.org/en/packages/com.unicornsonlsd.finamp/
[^github-finamp]: https://github.com/UnicornsOnLSD/finamp
[^fdroid-ultrasonic]: https://www.f-droid.org/en/packages/org.moire.ultrasonic/
[^github-finamp]: https://github.com/UnicornsOnLSD/finamp

[^github-ultrasonic]: https://github.com/ultrasonic
[^gplay-substreamer]: https://play.google.com/store/apps/details?id=com.ghenry22.substream2&hl=en&gl=US
[^gitlab-funkwhale]: https://dev.funkwhale.audio/funkwhale/funkwhale-android
[^fdroid-subtracks]: https://f-droid.org/en/packages/com.subtracks/
[^github-subtracks]: https://github.com/austinried/subtracks
[^fdroid-dsub]: https://f-droid.org/en/packages/github.daneren2005.dsub/
[^github-dsub]: https://github.com/daneren2005/Subsonic
[^fdroid-audinaut]: https://f-droid.org/en/packages/net.nullsum.audinaut/
[^github-audinaut]: https://github.com/nvllsvm/Audinaut
[^fdroid-subsonic]: https://f-droid.org/en/packages/net.sourceforge.subsonic.androidapp/
[^sourceforge-subsonic]: https://sourceforge.net/projects/subsonic/
[^github-navidrome]: https://github.com/navidrome

[^help-subtracks-download]: There is a download button. It doesn't work for me.
[^website-subsonic]: http://www.subsonic.org/pages/index.jsp
[^website-funkwhale]: https://funkwhale.audio/
[^fdroid-funkwhale]: https://f-droid.org/en/packages/audio.funkwhale.ffa/



## Index

- :heavy_check_mark: means yes, it is supported
- :x: means no, it is not supported
- :heavy_dollar_sign: means the service/feature has a price `p` where `p>0` 
- :grey_question: means help wanted, original author wasn't sure or couldn't judge the covered topic.
- :white_circle: means the feature doesn't apply to this service and cannot be evaluated.

## Further Readings

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)

[MIT License](https://mit-license.org/)

## How to Contribute

tba

## Footnotes
