# easySCI

#### A List of Core SCI Journals  For Academics

## Background

All researchers want to receive the latest studies with as less effort as possible. **<font color="#dd0000">easySCI</font>** is an annually-updated project about **<font color="#dd0000">easily tracing research updates in PubMed SCI journals with RSS</font>**, where journals are stratified via Impact Factor (IF). Although it's controvertial using IF to profile the importance of articles, IF is a simple but effective strategy to weight academic updates. Now only Biology & Medicine are supported, but more areas would be supported as soon as possible.

## Usage

`*.Rmd` or `*.HTML` show the process of ISSN filtering with R programing. The RSS links could be input in an RSS reader such as Tiny Tiny RSS. **If you have no idea about RSS, you can visit [my blog](https://blognas.hwb0307.com/map) for help (Chinese)**.

### CNS

The OPML file for `Cell`, `Nature`, and `Science` is [here](https://github.com/huangwb8/easySCI/blob/main/%40opml/RSS-%40-CNS.opml).

### Biology & Medicine

> <a href="https://raw.githubusercontent.com/huangwb8/easySCI/main/BioMed.Rmd" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title=" and Rmd">Rmd</a>; <a href="http://htmlpreview.github.io/?https://github.com/huangwb8/easySCI/blob/main/BioMed.html" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title=" and HTML">HTML</a>

+ RSS-2022-Cancer:| [OPML For RSS](https://raw.githubusercontent.com/huangwb8/easySCI/main/%40opml/RSS-2022-Cancer.opml) | <a href="https://pubmed.ncbi.nlm.nih.gov/rss/search/1PqbW6kGMDPf-yLHJMRvJKCULZQRJtMnk9CTYdZriokv096kHR/?limit=20&utm_campaign=pubmed-2&fc=20220829074127" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title="IF>=15">IF>=15</a> | <a href="https://pubmed.ncbi.nlm.nih.gov/rss/search/1j5cNbPuzU_61Tz-Qg1vnc_ZtX59BAoJsN_UB-eeozxW3wYsOZ/?limit=20&utm_campaign=pubmed-2&fc=20220829075717" data-wpel-link="external" target="_blank" rel="nofollow external noopener noreferrer" title="IF>=10">15>IF>=10</a> | [10>IF>=7](https://pubmed.ncbi.nlm.nih.gov/rss/search/1x1PPzbhojragl3O9VVpHGH2UtvKpI_JBCu-xgcWkI8ENbFsC0/?limit=20&utm_campaign=pubmed-2&fc=20220829075916) | [7>IF>=6](https://pubmed.ncbi.nlm.nih.gov/rss/search/1dSaW42H3lPR7KerD5oMt51ye6YU9HMXeJEaavnqqIdqZEJsMS/?limit=20&utm_campaign=pubmed-2&fc=20220829094956) | [6>IF>=5.5](https://pubmed.ncbi.nlm.nih.gov/rss/search/1pEhTjOZGNUCUlZMTljgEfx-VSRdyWmBVyPPOqvW1a2ElsykQZ/?limit=20&utm_campaign=pubmed-2&fc=20220829080345) | [5.5>IF>=5](https://pubmed.ncbi.nlm.nih.gov/rss/search/1zYrsILa0sOmmYxKvXOe_Nct0EGG0PHz2KQr2ch3bN_1vbGMLm/?limit=20&utm_campaign=pubmed-2&fc=20220829080606) | [IF<5](https://pubmed.ncbi.nlm.nih.gov/rss/search/1zSVwQViw4hkk0p7LLiebjWRxtjin29VO1t49N4USbVyqxhMJ8/?limit=20&utm_campaign=pubmed-2&fc=20220829184532) |

## Demo

> The RSS reader showed here is [Tiny Tiny RSS](https://blognas.hwb0307.com/linux/docker/788).

![chrome_5u4uGWjgqh.gif](https://chevereto.hwb0307.com/images/2022/09/01/chrome_5u4uGWjgqh.gif)

## Maintainers

[@huangwb8](https://t.me/hwb0307)

## TODO

+ Support more and more areas
+ More contributors

## How to contribute

Open an [issue](https://github.com/huangwb8/easySCI/issues) with Pubmed searching term like [here](https://github.com/huangwb8/easySCI/blob/main/Search%20Term.md). Take `Cancer` as an example:

```
("neoplasms"[MeSH]) OR ("neoplasm"[Title/Abstract]) OR ("neoplasms"[Title/Abstract]) OR ("cancer"[Title/Abstract]) OR ("cancers"[Title/Abstract]) OR ("carcinoma"[Title/Abstract]) OR ("carcinomas"[Title/Abstract])
```

Then search in PubMed with the logical form like `(Searching terms) and (target journals)`. Create a RSS link and save it. Very simple, isn't it?

## Contributing

Welcome to be a contributor of this project!

## License

[MIT](https://github.com/huangwb8/easySCI/blob/main/LICENSE) © Weibin Huang