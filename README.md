# metadata

Metadata for various shows from CCT, ongoing shows will be updated via scraping various sites and video releases

If you've got any metadata please create a [new issue](https://github.com/chikichikitube/metadata/issues/new/choose) and send a link to the data, then it will be incorporated into the data building pipeline

## Data

### `segment_ja.csv` and `segment_ja.json`
Japanese language metadata at the episode or segment level:
- cctid: tentative universal id
- show: string of showname (matching CCT channel name)
- date: air-date or release date
- episode: episode number (or 'SP' if unnumbered)
- segment: segment order within episode if available
- name_ja: Japanese episode name
- description_ja: Japanese description of episode
- metadata: Additional data specific to the show (i.e. Knight Scoop detective names)

## Sources

### Gaki no Tsukai
- Official NTV Website: https://www.ntv.co.jp/gaki/r_backnumber
- Ghiaccio Fanmade database (unmaintained): http://ghia.chu.jp/wiki/index.php https://web.archive.org/web/20220216073641/ghia.chu.jp/wiki/index.php
- Gaki no Tsukai Forum: https://gaki-no-tsukai.com

### Knight Scoop
- Braxen Fanmade database: https://knightscoop.yabai.moe/

### Gottsu A Kanji
- huh009 fanmade database: https://docs.google.com/spreadsheets/d/1iagP08wj7WMH8WCAks-NezdcBfMmJCC0EevcH_rZm5M/edit?usp=sharing

### Documental
- Amazon Prime Video JP Scrape

### Freeze
- Amazon Prime Video JP Scrape

### MHK
- Official DVD Information

### Documental
- The TV DB: https://thetvdb.com/series/346564-show/

### Wednesday Downtown / Suiyoubi no Downtown
- The TV DB: https://thetvdb.com/series/wednesdays-downtown/
