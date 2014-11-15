lastviz
=======

5 Nov 2014. A project to:
* Learn how to put the Intertoobs together - i.e. feed live/API data into a `d3.js` chart.
* Make it user-interactive, because hooray!
* Learn a new `d3.js` visualization type (donut/pie). 

### To Do
1. ~~Style the ugly buttons.~~
2. ~~Clean up general file, which is a mess.~~ (Clean enough for now.)
3. Figure out if there's a reason and way to hide (?) the API key. Or does no one care?
4. ~~Can I pull two JSONs at once? Nested `d3.json` pulls?~~ (Yes.)
5. ~~Merging artist tags with track/artists (ringed donut).~~ (Ballaaaa.)
6. Second level (outer ring) tooltip on artists: medium pics.
7. Transitions between users.
8. `Enter` keystroke = clicking on `Update`?
9. `click` to bring out the second ring (of topArtists).
10. ~~Drop-down form of how many results (10, 20, etc?). Or text box?~~ 
11. ~~Colors?! COLORS!~~
12. ~~`lowerCase` `tags`, remove hyphens and replace with spaces, etc.~~
13. ~~Rollup data (`d3.nest`), with `tag` being the `key`.~~ 
14. ~~Use [queue.js](http://bl.ocks.org/mbostock/1696080) to deal with asynchronous JSON calls.~~ (Awww yeah.)
15. ~~How to give the user an `error` message if anything is `undefined`? This becomes especially important when users call lots of `topArtist` data (e.g. >30 artists). Or when users enter text into the number box.~~ (Figured out a way to skip this and just give "none" `tags`.)
16. ~~Clean up the `d3.rollup` to count leaves and so on.~~ (Don't need this. It's similar to `collapse` in Stata.)
17. ~~Style the `<h4>` a bit more...~~
18. ~~Change mouse icon when hovering over `Update` button.~~
19. ~~The actual sunburst/`pie` layout! Specifically, how to get `d.playcount` in my `pie`.~~
20. Style: make 2nd (+3rd?) column of `<p>`, in the style of [Shay Howe tutorial on multiple columns](http://learn.shayhowe.com/html-css/positioning-content/).
21. A background pic, a color, something to brighten things up.
22. Meaningful colors - &exist; a color-wheel for music?
23. "Loading..." thinking wheel. 
24. Tooltips on hover.



### Resources

* API info: [last.fm - user.getTopArtists](http://www.last.fm/api/show/user.getTopArtists)
* Example: [Mike Bostock - Sunburst](http://bl.ocks.org/mbostock/4063423)
* Example: [Mike Bostock - Pie chart update, II](https://gist.github.com/mbostock/1346410)
* Example: [Random JSFiddle - Pie chart](http://jsfiddle.net/ragingsquirrel3/qkHK6/)
* Example: [NVD3.js - Pie/Ring charts](http://nvd3.org/examples/pie.html)
* Q&A: [StackOverflow - Update pie chart with new data.json](https://stackoverflow.com/questions/19717519/update-d3-pie-chart-with-new-data-json)
* Q&A: [StackOverflow - Dynamic defers in queue.js](https://stackoverflow.com/questions/21687230/dynamically-change-the-number-of-defer-calls-in-queue-js)
* Q&A: [StackOverflow - Donut chart with multiple rings](https://stackoverflow.com/questions/17507728/d3-js-donut-charts-with-multiple-rings)
* Oh wow useful: [Logic symbols in HTML](https://en.wikipedia.org/wiki/List_of_logic_symbols)


