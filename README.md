# Syberia OS official device repo
## A-Only device config file format:
+ Device config file must be valid JSON
+ Required fields:
    + Some 'about ROM' fields:
        + **developer** - device maintainer name
        + **developer_url** - link to contact with maintainer (telegram, xda, etc.)
        + **website_url** - must be 'https://syberiaos.com'
        + **news_url** - must be 'http://github.com/syberia-project'
        + **forum_url** - link to thread on XDA
        + **donate_url** - must be 'https://syberiaos.com/links#Donate'
    + OTA fields:
        + **filename** - *.zip
        + **filesize** - *.zip size in bytes
        + **md5** - *.zip md5 hash
        + **build_date** - *.zip build date
        + **url** - SourceForge direct link to download latest *.zip
        + **changelog** - changelog
        + **addons** - some useful downloads, like magisk, etc.
    + Download portal fields:
        + **device_brand** - Xiaomi, OnePlus, etc.
        + **device_model** - Mi5, Redmi 4X, etc.
        
### Example for A-only devices you can find in 'a-only/gemini.json'
### Example for A/B devices you can find in 'ab/enchilada.json'
