An api for connecting to Last.FM through StepZen's GraphQL implementation.

Example API url: http://ws.audioscrobbler.com/2.0/?method=tag.gettopalbums&tag=disco&api_key=YOU_API_KEY&format=json

Example API Return for tag "disco":
```js
{
    "albums": {
        "album": [
            {
                "name": "Dynamite",
                "mbid": "",
                "url": "https://www.last.fm/music/BTS",
                "artist": {
                    "name": "BTS",
                    "mbid": "0d79fe8e-ba27-4859-bb8c-2f255f346853",
                    "url": "https://www.last.fm/music/BTS"
                },
                "image": [
                    {
                        "#text": "https://lastfm.freetls.fastly.net/i/u/34s/88188455b6b1d562c6db01e24f725165.png",
                        "size": "small"
                    },
                    {
                        "#text": "https://lastfm.freetls.fastly.net/i/u/64s/88188455b6b1d562c6db01e24f725165.png",
                        "size": "medium"
                    },
                    {
                        "#text": "https://lastfm.freetls.fastly.net/i/u/174s/88188455b6b1d562c6db01e24f725165.png",
                        "size": "large"
                    },
                    {
                        "#text": "https://lastfm.freetls.fastly.net/i/u/300x300/88188455b6b1d562c6db01e24f725165.png",
                        "size": "extralarge"
                    }
                ],
                "@attr": {
                    "rank": "1"
                }
            }
        ]
    }
}
```