---
layout: default
---

[Video-Embed](https://github.com/eug/jekyll-video-embed) is a [Jekyll](https://jekyllrb.com/) plugin
that can transform [Markdown](https://en.wikipedia.org/wiki/Markdown) into a YouTube, Vimeo, Ustream and TED video window.

Read the [documentation](https://github.com/eug/jekyll-video-embed) to get started.

## Usage
To include a video in your jekyll post, just use the string '{% tag video_id width height %}' and replace by its respective 'tag' and 'video_id', the 'width' (default value: 640) and 'height'(default value: 360) are optional.

## Description
The following table shows the supported websites, their respective 'tag', and where is located the 'video_id' (highlighted) in the URL of each video.

|    Website  |   Tag   |  Video ID                                                   |
|-------------|---------|-------------------------------------------------------------|
| ted.com     | ted     | ted.com/talks/**ken_robinson_says_schools_kill_creativity** |
| ustream.tv  | ustream | ustream.tv/channel/**6540154**                              |
| vimeo.com   | vimeo   | vimeo.com/**22439234**                                      |
| youtube.com | youtube | youtube.com/watch?v=**9bZkp7q19f0**                         |

## Exemple
{% youtube EEIk7gwjgIM %}'