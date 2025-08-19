# Example apps.yaml
```
twitch_thumbs:
  module: twitch_thumbs
  class: TwitchConcat
  entity: sensor.twitch_online_streamers
  attribute: online_detail
  format: bmp
  mode: RGB
  size: [32, 32]
  out_dir: /config/www/twitch
  out_file: online_strip.bmp
```