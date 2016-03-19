---
layout:     post
title:      "Whale Sharks Rule So Hard"
subtitle:   "Dio can't even express their awesomeness"
date:       2016-03-11 12:00:00
author:     "Dylan Meagher"
header-img: "img/post-head-whale.jpg"
---

<p>Holy shit! Whale sharks are so awesome, but Steve kept on insisting that he would not snorkely with them. I don't to stop being suck a pussy, but he persisted.  This is an excellent example on Steve doubling down on being weak.</p>

<p>Eveyone should see whale sharks, especially after a couple od nights out in Manila.</p>


<a href="#">
    <img src="{{ site.baseurl }}/img/post-body-whale.jpg" alt="Post Sample Image">
</a>


<div id='highcharts-edupib'><script src='//cloud.highcharts.com/inject/edupib' defer='defer'></script></div>
<br><br>

<iframe width="100%" height="520" frameborder="0" src="https://dymeagher.cartodb.com/viz/7614ffc4-afce-11e5-a5ba-0e787de82d45/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>



<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js">
</script>
<script type="text/javascript" src="http://code.highcharts.com/highcharts.js">
</script>
<script type="text/javascript" src="http://code.highcharts.com/modules/exporting.js">
</script></p>

<!---<div id="container" style="min-width: 310px; height: 400px; margin: 0 auto">-->
<div id="container" style="width: 600px; height: 400px; margin: 0 auto">
</div>
<script type="text/javascript">

//$(function () {
        $('#container').highcharts({
            title: {
                text: 'Monthly Average Temperature',
                x: -20 //center
            },
            subtitle: {
                text: 'Source: WorldClimate.com',
                x: -20
            },
            xAxis: {
                categories: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun',
                    'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec']
            },
            yAxis: {
                title: {
                    text: 'Temperature (°C)'
                },
                plotLines: [{
                    value: 0,
                    width: 1,
                    color: '#808080'
                }]
            },
            tooltip: {
                valueSuffix: '°C'
            },
            legend: {
                layout: 'vertical',
                align: 'right',
                verticalAlign: 'middle',
                borderWidth: 0
            },
            series: [{
                name: 'Tokyo',
                data: [7.0, 6.9, 9.5, 14.5, 18.2, 21.5, 25.2, 26.5, 23.3, 18.3, 13.9, 9.6]
            }, {
                name: 'New York',
                data: [-0.2, 0.8, 5.7, 11.3, 17.0, 22.0, 24.8, 24.1, 20.1, 14.1, 8.6, 2.5]
            }, {
                name: 'Berlin',
                data: [-0.9, 0.6, 3.5, 8.4, 13.5, 17.0, 18.6, 17.9, 14.3, 9.0, 3.9, 1.0]
            }, {
                name: 'London',
                data: [3.9, 4.2, 5.7, 8.5, 11.9, 15.2, 17.0, 16.6, 14.2, 10.3, 6.6, 4.8]
            }]
        });
//    });

</script>

<p>Finally, get it working now!</p>