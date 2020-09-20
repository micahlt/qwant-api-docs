# `GET /search`

## `GET /search/[category]`

#### Sub-requests (categories)

You can search `web`, `images`, `news`, `social`, `videos`, or `music`.

#### Parameters

|                     | **count**                  | **q**        | **t**        | **f**                         | **offset**  | **locale**                | **uiv** |
|---------------------|----------------------------|--------------|--------------|-------------------------------|-------------|---------------------------|---------|
| **Accepted values** | any integer greater than 0 | search query | search terms | _offset_, _locale_, and _uiv_ | any integer | see [locales](locales.md) | 4       |

Example request URL: 

```
https://api.qwant.com/api/search/web?count=10&q=searchtext&t=searchtext&f=&offset=0&locale=en_us&uiv=4
```
