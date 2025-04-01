# Slides from ZHB Luzern

This respository contains different markdown-based presentations created by people affiliated to ZHB Luzern (https://www.zhbluzern.ch).

## Presentation Index

* 2025-04 [Goobi pyCLI-Metadateneditor](2025_04_AG_Goobi)
* 2024-02 [ZHB Luzern - KI-Impuls der Library IT](2024_02_ZHB_LIT_KI-Impuls)
* 2023-10 [Presentation &#34;GLAM-Wiki&#34;, Wien Geschichte Wiki Workshop, Wienbibliothek, 10. Oktober 2023](2023_10_WGW_Workshop)
* 2023-03 [Presentation about ZentralGut. AG Goobi, Universität Wien, 20. März 2023](2023_03_AG_Goobi)
* 2022-09 [Use Wikidata in Intranda Goobi. Goobi Dommunity Days 2022, Online](2022_09_Goobi_Days_Wikidata)

## Build your own ZHB-presetnation

* Create a new directory for your presentation
* Create an `img/` Directory in your presentation directory
* Build your presentation in a slides*.md file
* run pandoc `pandoc -s -i -t revealjs --variable revealjs-url=../build/reveal.js --variable theme="zhbluzern_2024" yourSlidesDirectory/yoursSlideshow.md -o yourSlidesDirectory/yoursSlideshow.html`
