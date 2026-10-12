# BBA Land Surveying project map

Client map page for BBA Land Surveying. GitHub Pages serves this repo at [map.bbasurveying.com](https://map.bbasurveying.com).

`index.html` loads an ArcGIS web map in the browser with the ArcGIS Maps SDK for JavaScript. Access is anonymous: there is no API key in this repo. From the link in a BBA email, a client can mark a spot, line, or area on their site and leave a note.

Both query parameters are required:

```
https://map.bbasurveying.com/?webmap=<web-map-id>&job=<job-id>
```

- `webmap` is the ArcGIS web map item id.
- `job` is the BBA job number.

If `webmap` or `job` is missing, the page shows: "This map link looks incomplete — please use the link from your BBA email."
