1. To see memory leak just clone this repo and serve it using a static server like apache or `python -m SimpleHTTPServer 8080`
2. Then go to the URL with the correct port in IE11 and the page will keep refreshing every second.
3. Open `Windows Task Manager` and see the memory increase by ~2-3MB on every page refresh.
