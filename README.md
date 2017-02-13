# gost

\*.csl files for *Mendeley*, *Zotero*, *Papers* (ГОСТ 2008).

## Styles
| Syle Name         | Inline Citation               | Bibliography Sort        |
| ----------------- | ----------------------------- | :----------------------: |
| `gost-2008-num`   | [number]                      | alphabetic               |
| `gost-2008-plain` | (Author, year)                | alphabetic               |
| `gost-2008-law`   | <sup>[\#]</sup>Footnotes      | source type & alphabetic |

>###Sorting by Source Type (\*.csl) in `gost-2008-law`
1<sup>st</sup> priority: `legislation` `bill` </br>
2<sup>nd</sup> priority: `book` `chapter`     </br>
3<sup>rd</sup> priority: `article-journal`    </br>
4<sup>th</sup> priority: `article-magazine`   </br>
5<sup>th</sup> priority: `article-newspaper`  </br>
6<sup>th</sup> priority: `thesis`             </br>
7<sup>th</sup> priority: `webpage`            </br>
8<sup>th</sup> priority: `report`             </br>
9<sup>th</sup> priority: the other


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
