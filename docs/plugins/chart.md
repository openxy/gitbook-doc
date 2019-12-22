#chart(图表)

#说明

在Gitbook中使用C3.js或Highcharts图表库。

#demo
[参考网站](https://github.com/csbun/gitbook-plugin-chart)

{% chart format="yaml" %}
data:
    type: highcharts
    columns:
        - [data1, 30, 200, 100, 400, 150, 250]
        - [data2, 50, 20, 10, 40, 15, 25]
    axes:
        data2: y2
axis:
    y2:
        show: true
{% endchart %}