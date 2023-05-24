# The window.location property

***

## Anatomy
|protocol|origin|host|hostname|port|href|pathname|search|hash|
|-|-|-|-|-|-|-|-|-|
|https:|https://localhost:8000|localhost:8000|localhost|8000|https://localhost:8000/topics?id=123#title|/topics|?id=123|#title|

## Methods

### replace()

Description:

It will replace the current location keeping the origin, navigating the browser
to the new location and removing the current one frome the window.history.

Parameters:
- url: string | URL
