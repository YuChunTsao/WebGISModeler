# WebGIS Modeler

WebGIS Modeler是一個基於JavaScript的GIS建模工具，希望能在瀏覽器完成如同ArcGIS Model Builder或是QGIS Graphical Model功能，方便讓使用者簡易且方便的處理空間資料，並不局限於軟體及作業系統，使用者均能透過瀏覽器來開啟。

透過[turf.js](https://leafletjs.com/), [Leaflet](https://turfjs.org/)來進行空間處理與展示，以互動式界面提供使用者進行繪製流程圖([GoJS](https://gojs.net/latest/learn/index.html)，仍在尋找相關工具中)。並希望能以JSON, XML, YAML...等適合的格式匯出Model，讓使用者能分享自己建立的模型，提昇模型的流通行，資料也可以一併匯出(geojson, xml or shp? (binary?))。

## 想像中的功能

* 可以透過拖曳或上傳的方式將檔案(csv, json, shp)添加至模型中(Javascript)
* 互動式界面可以連結各個空間分析工具(參考ArcGIS ModelBuilder or QGIS Graphical Model)
* 可以匯出模型定義檔案(json, xml, yaml...)
* 此專案可由使用者於本地端自行架設(turf.js可以在nodejs執行，待思考確認如何進行)
* 平台可以整合資料庫，作為資料來源或是儲存的空間。
* ...

## TODO

* GoJS如何建立互動式流程圖編輯界面([example1](https://gojs.net/latest/samples/systemDynamics.html), [example2](https://gojs.net/latest/samples/draggableLink.html))
* GoJS 圖形與 turf.js 空間分析功能整合，各功能參數及條件。
* 拖曳的方式上傳檔案([Using files from web applications](https://developer.mozilla.org/en-US/docs/Web/API/File/Using_files_from_web_applications))，shp上傳([shapefile-js](https://github.com/calvinmetcalf/shapefile-js/tree/gh-pages/files))
* 界面設計及前端框架選用
* ...


## References

* [leaflet](https://leafletjs.com/)
* [turf.js](https://turfjs.org/)
* [GoJS](https://gojs.net/latest/learn/index.html)
* [HTML5 canvas](https://developer.mozilla.org/zh-TW/docs/Web/API/Canvas_API)
* [Using files from web applications](https://developer.mozilla.org/en-US/docs/Web/API/File/Using_files_from_web_applications)
* [shapefile-js](https://github.com/calvinmetcalf/shapefile-js/tree/gh-pages/files)