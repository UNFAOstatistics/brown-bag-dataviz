Case1


|                      |               bitmap              |                       vector                       |
| -------------------- | --------------------------------- | -------------------------------------------------- |
| file extensions      | .jpg, .png, .gif                  | .eps, .pdf, .svg, .ai                              |
| common example       | digital photo                     | google maps                                        |
| consists of          | millions of pixels                | points, lines and polygons                         |
| file size            | large                             | small                                              |
| usage                |                                   |                                                    |
| software for editing | [Gimp](www.gimp.org/) (Photoshop) | [Inkscape](https://inkscape.org/en/) (Illustrator) |
| good for             | web, printing (in high-res)       | print, post-processing, web (with limitations)     |
| missing              | user interactivity                | user interactivity                                 |
| exclusively used     | digital photography               | detailed maps and graphs                           |

- statistical software can export both formats, only vector files can be properly post-processed
- You can make vector graphics into bitmap graphics, but not the other way around


Case2


|                 |            interactive graphics            |    interactive web applications    |
| --------------- | ------------------------------------------ | ---------------------------------- |
| typical example | javascript plot                            | Trade data explorer                |
| look and feel   | amazing but limited                        | amazing and unlimited              |
| depends         | online libraries, shipped with data        | Needs a full R instance            |
| R               | [htmlwidgets](http://www.htmlwidgets.org/) | [shiny](http://shiny.rstudio.com/) |
| good for        | showing off &                              | showing off & explorative wiz      |
|                 |                                            |                                    |
