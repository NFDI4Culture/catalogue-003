# NextCloud MD Editor

::: success
Call outs? 

:::

![David_Teniers\_(II)\_-\_The_gallery_of_Archduke_Leopold_in_Brussels.jpg](6780765/David_Teniers_%28II%29_-_The_gallery_of_Archduke_Leopold_in_Brussels.jpg)

| Vegetables | Not vegetables | Bier | Wein |
|------------|----------------|------|------|
| Raddish | Mushroom |  |  |
| Leak |  |  |  |

::: info
Please edit here: hello here is nils

:::

![Flegel\_-\_Wein_und_Konfekt,\_Maus_und_Papagei.jpg](6780765/Papagei.jpg)  
**English:** *Still-life with Parrot*

**Deutsch:** *Stillleben mit Papagei*

*to do list* 

* [ ] *Activity 1*
* [ ] Activity 2
* [ ] Activity 3

::: success
Sucess

:::

::: warn
Warning

:::

::: error
Danger

:::

and this is paul, look I can make edits!!

SW: Ive tuurned on the colour marking for users, but this maybe only shows up for me and not all other users.

nils: at the moment i dont see any color marking => fixed by enable option

The colour thing must be user specific.

```
WHERE
{
  # find items which:
  # are instances of (wdt:P31) paintings (wd:Q3305213)
  # have the property (wdt:P195) of being in collection wd:Q812285 (Bavarian State Painting Collections https://www.wikidata.org/wiki/Wikidata:WikiProject_sum_of_all_paintings/Collection/Bavarian_State_Painting_Collections)
  ?item wdt:P31 wd:Q3305213 .
  ?item wdt:P195 wd:Q812285 .
  # get the item's creator property (wdt:P170)
  ?item wdt:P170 ?creator .
  # get the item's image property (wdt:P18)
  ?item wdt:P18 ?image .
  # get the item's copyright status (wdt:P6216)
  ?item wdt:P6216 ?copyright . 
    {
    ?item wdt:P571 ?inception.
    BIND(YEAR(?inception) AS ?inceptionyear)
  }
```

# END

---

# Baroque #AI

## Series: Baroque TOC

Publication: An exhibition catalogue

Project goal and activities:

The goal is to create a finished exhibition catalogue - like so: 

![Venus_und_Cupido](6780765/Heinrich_Bollandt_-_Venus_und_Cupido.jpg)Heinrich Bollandt - Venus und Cupido, between circa 1620 and circa 1630 <https://commons.wikimedia.org/wiki/File:Heinrich_Bollandt_-_Venus_und_Cupido.jpg>

## Activities

## Markup testing

Headers

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6