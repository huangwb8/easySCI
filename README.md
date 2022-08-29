# easySCI

#### A List of Core SCI Journals  For Academics

## Background

All researchers want to receive the latest studies with as less effort as possible. **easySCI** is an annually-updated project about easily tracing research updates in Pubmed SCI journals with RSS, where journals are stratified via Impact Factor (IF). Although it's controvertial using IF to profile the importance of articles, IF is a simple but effective strategy to acheive academic updates. Now only Biology & Medicine supported. 

## Usage

`*.Rmd` or `*.HTML` show the process of ISSN filtering with R programing. The RSS links could be input in an RSS reader such as Tiny Tiny RSS. **If you have no idea about RSS, you can visit [my blog](https://blognas.hwb0307.com/map) for help (Chinese)**.

### Biology & Medicine

> <a href="https://raw.githubusercontent.com/huangwb8/easySCI/main/BioMed.Rmd" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title=" and Rmd">Rmd</a>; <a href="http://htmlpreview.github.io/?https://github.com/huangwb8/easySCI/blob/main/BioMed.html" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title=" and HTML">HTML</a>

+ RSS-2022-Cancer: | <a href="https://pubmed.ncbi.nlm.nih.gov/rss/search/1PqbW6kGMDPf-yLHJMRvJKCULZQRJtMnk9CTYdZriokv096kHR/?limit=20&utm_campaign=pubmed-2&fc=20220829074127" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title="IF>=15">IF>=15</a> | <a href="https://pubmed.ncbi.nlm.nih.gov/rss/search/1j5cNbPuzU_61Tz-Qg1vnc_ZtX59BAoJsN_UB-eeozxW3wYsOZ/?limit=20&utm_campaign=pubmed-2&fc=20220829075717" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title="IF>=10">15>IF>=10</a> | [10>IF>=7](https://pubmed.ncbi.nlm.nih.gov/rss/search/1x1PPzbhojragl3O9VVpHGH2UtvKpI_JBCu-xgcWkI8ENbFsC0/?limit=20&utm_campaign=pubmed-2&fc=20220829075916) | [7>IF>=6](https://pubmed.ncbi.nlm.nih.gov/rss/search/1dSaW42H3lPR7KerD5oMt51ye6YU9HMXeJEaavnqqIdqZEJsMS/?limit=20&utm_campaign=pubmed-2&fc=20220829094956) | [6>IF>=5.5](https://pubmed.ncbi.nlm.nih.gov/rss/search/1pEhTjOZGNUCUlZMTljgEfx-VSRdyWmBVyPPOqvW1a2ElsykQZ/?limit=20&utm_campaign=pubmed-2&fc=20220829080345) | [5.5>IF>=5](https://pubmed.ncbi.nlm.nih.gov/rss/search/1zYrsILa0sOmmYxKvXOe_Nct0EGG0PHz2KQr2ch3bN_1vbGMLm/?limit=20&utm_campaign=pubmed-2&fc=20220829080606) |

## Demo

RSS links in Tiny Tiny RSS (one of RSS readers): 

![chrome_rci93YOgcp](https://chevereto.hwb0307.com/images/2022/08/29/chrome_rci93YOgcp.webp)

Open a record:

![chrome_N1wJ1emiua](https://chevereto.hwb0307.com/images/2022/08/29/chrome_N1wJ1emiua.webp)

## Maintainers

[@huangwb8](https://t.me/hwb0307)

## TODO

+ Support more and more areas

## How to contribute

Open an [issue](https://github.com/huangwb8/easySCI/issues) with Pubmed searching term like [here](https://github.com/huangwb8/easySCI/blob/main/Search%20Term.md). Take `Cancer` as an example:

```
("neoplasms"[MeSH]) OR ("neoplasm"[Title/Abstract]) OR ("neoplasms"[Title/Abstract]) OR ("cancer"[Title/Abstract]) OR ("cancers"[Title/Abstract]) OR ("carcinoma"[Title/Abstract]) OR ("carcinomas"[Title/Abstract])
```

Then search in Pubmed with the logical form like `(Searching terms) and (target journals)`. Create a RSS link and save it. Very simple, isn't it?

## Contributing

To be continued!

## License

[MIT](https://github.com/huangwb8/easySCI/blob/main/LICENSE) © Weibin Huang