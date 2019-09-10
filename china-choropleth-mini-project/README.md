## China Choropleth Map Project

Given the API endpoint: http://api-t.udty.tech/api/event/223/stats that returns the number of viewers from certain provinces in China for a livestream event, create a choropleth map to display number of viewers in each province. An example using d3.js can be found here: https://observablehq.com/@d3/state-choropleth and GeoJSON data for Chinese provinces can be found here: https://github.com/yezongyang/china-geojson


现有如下接口: http://api-t.udty.tech/api/event/223/stats 提供不同地域的直播观看用户人数数据以及美国分区地图：https://observablehq.com/@d3/state-choropleth ，试根据接口提供的数据画出类似的中国分省地图，颜色的深浅代表人数的多少。

附加题：将中国以外其他国家的数据以表格形式列出。