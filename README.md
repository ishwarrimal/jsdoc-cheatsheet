# jsdoc-cheatsheet

## Types

1. @param {string} name - String type but optional
2. @param {number} age - number type optional
3. @param {string|number} phone - string or number optional
4. @param {\*} n - any type
5.

## Function definition (example taken from my own project)

```javascript
\/**
 *
 * @param {string} url - The url of domain
 * @param {Object} config - The config object
 * @param {boolean} [config.disabled] -> Whether the popup is disabled on this site
 * @param {boolean} [config.minimized] -> whehter the pupup is minimized on this site
 * @param {Object} [config.position] -> {x,y} cordinates of the popup
 * @returns {promise} -> Returns true when the config is updataed
 \*/
 async function updateDomainConfig(url, config) {}
```
