# podcast-dl

## A CLI for downloading podcasts with a focus on archiving.

## How to Use

**[Node Required](https://nodejs.org/en/)**

`npx podcast-dl --url <PODCAST_RSS_URL>`

`npx podcast-dl --url "http://friendsatthetable.libsyn.com/rss"`

## Options

| Option                | Type   | Required | Description                                                                                |
| --------------------- | ------ | -------- | ------------------------------------------------------------------------------------------ |
| url                   | String | true     | URL to podcast RSS feed.                                                                   |
| out-dir               | String | false    | Specify output directory for episodes and metadata. Defaults to current working directory. |
| include-meta          |        | false    | Write out podcast metadata to JSON.                                                        |
| include-episode-meta  |        | false    | Write out individual episode metadata to JSON.                                             |
| ignore-episode-images |        | false    | Ignore downloading found images from --include-episode-meta                                |
| version               |        | false    | Output the version number.                                                                 |
| help                  |        | false    | Output usage information.                                                                  |