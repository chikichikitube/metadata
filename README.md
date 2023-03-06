# metadata

Metadata for various shows from CCT, ongoing shows will be updated via scraping various sites and video releases.

This will only contain episodes, specials and DVDs/blu ray releases

If you've got any metadata or errors please create a [new issue](https://github.com/chikichikitube/metadata/issues/new/choose) and send a link to the data, then it will be incorporated into the data building pipeline

## `metadata.csv` and `metadata.json`
Japanese language metadata at the episode or segment level:

| field | description |
| ----- | ----------- |
| cct_id | tentative universal id |
| show_id | string of showname (matching CCT channel name) |
| show | string of showname in English |
| show_ja | string of showname in Japanese |
| date | air-date or release date |
| episode | episode number (or 'SP' if special) |
| segment | segment order within episode if available |
| name_ja |  Japanese episode name |
| name_en |  English episode name (some are low quality translations) |
| description_ja | Japanese description of episode |
| metadata | Additional data specific to the show (i.e. Knight Scoop detective names) |
| cct_permalink | immutable chikichiki.tube video name if available |
| cct_url | url to link to Chiki Chiki Tube video web page if available |


## `src`
The `src` folder contains a combination of completed metadata for shows that are no longer ongoing and metadata that will be updated by the scraping script.

The `src/metadata.iynb` scraping script is a Jupyter python notebook to scrape metadata from existing websites and sources, it requires the following python packages to run: `jupyterlab pandas bs4 requests`

## Sources

### Gaki no Tsukai
- Official NTV Website: https://www.ntv.co.jp/gaki/r_backnumber
- Ghiaccio Fanmade database (unmaintained): http://ghia.chu.jp/wiki/index.php https://web.archive.org/web/20220216073641/ghia.chu.jp/wiki/index.php
- Gaki no Tsukai Forum: https://gaki-no-tsukai.com

### Suberanai Hanashi
- Official Fuji TV Website: https://www.fujitv.co.jp/suberanai/

### Knight Scoop
- Braxen Fanmade database: https://knightscoop.yabai.moe/

### Gottsu A Kanji
- huh009 fanmade database: https://docs.google.com/spreadsheets/d/1iagP08wj7WMH8WCAks-NezdcBfMmJCC0EevcH_rZm5M/edit?usp=sharing

### Freeze, Documental, Joshimental, Ikemental, Documentary of Documental
- Amazon Prime Video JP Scrape

### MHK
- Official DVD Information

### Wednesday Downtown / Suiyoubi no Downtown
- The TV DB: https://thetvdb.com/series/wednesdays-downtown/
- gakidave fanmade database
