# mws-restaurant-stage-2-kew
-----------------------------
Project Blog Article: https://portfolio.katiegirl.net/2018/09/03/restaurant-reviews-app-stage-2/

Stage 2 Notes:

Project Overview

For the Restaurant Reviews projects, I incrementally converted a static webpage to a mobile-ready web application. In Stage Two, I took the responsive, accessible design I built in Stage One and connect it to an external server. I used asynchronous JavaScript to request JSON data from the server. I also stored data received from the server in an offline database using IndexedDB, which created an app shell architecture. Finally, I optimized my site to meet performance benchmarks, which I tested using Lighthouse.

LightHouse Performance: My Lightout score screen capture is available in the demo folder: lighthousescores.png
Demo Folder: Shows the screen captures of the responsive design implementation and application features.

-------------------------------------
Stage 1 Notes:
Responsive Images were designed for a DPR setting of 1.0. When testing under Google Chrome Tools make sure your DPR setting is set to 1.0.
-------------------------------------
Accessibility: Google Maps was hidden the Accessibility Tree but I added the application role per guidance of my mentor. 
-------------------------------------
Maps API

I switched from Google to Leaflet with MapBox for free. Get your own access token for free here: https://www.mapbox.com
Since then, life has been so much better with no errors in the log on offline caching or service quotas.


