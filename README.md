# A based broswer homepage 
### No more bloat on search engine landing page

## Description
It is just a clean homepage for your broswer, so you can submit your search query by bypassing the landing page that contains 20+ js files. All it has just a plain html and some css. The form will redirect user to SearX instance searx.be (the default search engine) after submitting the query.

## Modification
To modify the default search engine, you can change the action attribute in the form tag
```html
<form class="search-bar" 
      action="Your favorite NON-GOOGLE/NON-BING/NON-YAHOO SEARCH ENGINE goes here!!!"
      target="_blank"
>
	<input type="text" name="q" id="" placeholder="Search on SearX..." />
</form>
```

Example to change the default search engine to DuckDuckGo.
```html
<form class="search-bar" 
	action="https://www.duckduckgo.com/"
    target="_blank"
>
	<input type="text" name="q" id="" placeholder="Search on SearX..." />
</form>
```
