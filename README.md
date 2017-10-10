# gost

\*.csl files for *Mendeley*, *Zotero*, *Papers* (ГОСТ 2008).

## Styles
| Syle Name         | Inline Citation               | Bibliography Sort        |
| ----------------- | ----------------------------- | :----------------------: |
| [:arrow_down:](https://raw.githubusercontent.com/ternikov/gost/master/gost-2008-num.csl "gost-2008-num.csl") `gost-2008-num`   | [number]                      | alphabetic               |
| [:arrow_down:](https://raw.githubusercontent.com/ternikov/gost/master/gost-2008-plain.csl "gost-2008-plain.csl") `gost-2008-plain` | (Author, year)                | alphabetic               |
| [:arrow_down:](https://raw.githubusercontent.com/ternikov/gost/master/gost-2008-law.csl "gost-2008-law.csl") `gost-2008-law`   | <sup>[\#]</sup>Footnotes      | source type & alphabetic |

## Examples
`gost-2008-law` </br>

#### Inline Citations (in Russian)
<sup>1</sup>  Hazledine&nbsp;T. Price discrimination in Cournot–Nash oligopoly&nbsp;// Economics Letters. 2006. Т.&nbsp;93. №&nbsp;3. </br>
<sup>2</sup>  Ситуационный центр региона [Электронный ресурс]. Режим доступа: http&#58;//www<i></i>.prognoz.<i></i>ru/products/line/situation-center. </br>
<sup>3</sup>  Гражданский кодекс Российской Федерации (ГК РФ). </br>
<sup>4</sup>  Иванов&nbsp;А.&nbsp;А. Продюсер в отношениях с субъектами авторских и смежных прав&nbsp;// Вестник Поволжского института управления. 2015. №&nbsp;4 (49). </br>
<sup>5</sup>  Yuan&nbsp;F., Gao&nbsp;J., Wang&nbsp;L. и&nbsp;др. Co-location of manufacturing and producer services in Nanjing, China&nbsp;// Cities. 2017. Т.&nbsp;63. </br>
<sup>6</sup>  `suppress author` Эконометрика. Начальный курс. М.: Дело, 2004.&nbsp;`С. 5–10.`

#### Bibliography (in Russian)
1.  Гражданский кодекс Российской Федерации (ГК РФ) `statute`
2.  Катышев П.&nbsp;К., Пересецкий А.&nbsp;А. Эконометрика. Начальный курс. М.: Дело, 2004. 576&nbsp;с. `book`
3.  Yuan&nbsp;F., Gao&nbsp;J., Wang&nbsp;L. и&nbsp;др. Co-location of manufacturing and producer services in Nanjing, China&nbsp;// Cities. 2017. Т.&nbsp;63. С.&nbsp;81&ndash;91. `chapter`
4.  Иванов&nbsp;А.&nbsp;А. Продюсер в отношениях с субъектами авторских и смежных прав&nbsp;// Вестник Поволжского института управления. 2015. №&nbsp;4 (49). С.&nbsp;1&ndash;20. `article-journal`
5.  Hazledine&nbsp;T. Price discrimination in Cournot–Nash oligopoly&nbsp;// Economics Letters. 2006. Т.&nbsp;93. №&nbsp;3. С.&nbsp;413&ndash;420. `article-journal`
6.  Ситуационный центр региона [Электронный ресурс]. Режим доступа: http&#58;//www<i></i>.prognoz.<i></i>ru/products/line/situation-center. (дата обращения:&nbsp;08.02.2017). `webpage`

</br></br>

> Main Destinctions in English: </br>
> `c.` --- `p.` </br>
> `№` --- `No.` </br>
> `Т.` --- `Vol.` </br>
> `и др.` --- `et al.` </br>

>### Sorting by Source Type (\*.csl) in `gost-2008-law`
>1<sup>st</sup> priority: `legislation` `bill` </br>
>2<sup>nd</sup> priority: `book` `chapter`     </br>
>3<sup>rd</sup> priority: `article-journal`    </br>
>4<sup>th</sup> priority: `article-magazine`   </br>
>5<sup>th</sup> priority: `article-newspaper`  </br>
>6<sup>th</sup> priority: `thesis`             </br>
>7<sup>th</sup> priority: `webpage`            </br>
>8<sup>th</sup> priority: `report`             </br>
>9<sup>th</sup> priority: the other


### Mendeley vs. CSL types
| Mendeley              | CSL                  |     | Mendeley             | CSL                 |
| --------------------- | -------------------- | --- | -------------------- | ------------------- |
|Generic                | `article`            |     | Journal Article      | `article-journal`   |
|Bill                   | `bill`               |     | Magazine Article     | `article-magazine`  |
|Book                   | `book`               |     | Newspaper Article    | `article-newspaper` |
|Book Section           | `chapter`            |     | Patent               | `patent`            |
|Case                   | `article`            |     | Report               | `report`            |
|Computer Program       | `article`            |     | Statute              | `legislation`       |
|Conference Proceedings | `paper-conference`   |     | Thesis               | `thesis`            |
|Encyclopedia Article   | `entry-encyclopedia` |     | Television Broadcast | `broadcast`         |
|Film                   | `motion_picture`     |     | Web Page             | `webpage`           |
|Hearing                | `speech`             |     | Working Paper        | `article`           |

## Markdown

```
---
title: "Sample Document"
bibliography: references.bib
csl: gost-2008-plain.csl 
---

[@article_code]

# References
```
