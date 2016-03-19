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


<iframe width="100%" height="520" frameborder="0" src="https://dymeagher.cartodb.com/viz/7614ffc4-afce-11e5-a5ba-0e787de82d45/embed_map" allowfullscreen webkitallowfullscreen mozallowfullscreen oallowfullscreen msallowfullscreen></iframe>

<br>

<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js">
</script>
<script type="text/javascript" src="http://code.highcharts.com/highcharts.js">
</script>
<script type="text/javascript" src="http://code.highcharts.com/modules/exporting.js">
</script>

<!---<div id="container" style="min-width: 310px; height: 400px; margin: 0 auto">-->
<div id="container" style="width: 600px; height: 400px; margin: 0 auto">
</div>
<script type="text/javascript">


// $(function() {
  Highcharts.setOptions({
    lang: {
      thousandsSep: ','
    }
  });
  $('#container').highcharts({
    chart: {
      type: 'line'
    },
    title: {
      text: 'Median Household Income With and W/out Stations'
    },
    xAxis: {
      categories: ['Without Stns', 'With Stns']
    },
    yAxis: {
      title: {
        text: 'Median Income'
      }
    },
    plotOptions: {
      line: {
        dataLabels: {
          enabled: true,
        },
        enableMouseTracking: false
      }
    },
    series: [{
      name: 'NYC',
      data: [63470, 91420],
      color: '#ff9900'
    }, {
      name: 'DC',
      data: [89820, 86820],
      color: '#0066ff'
    }, {
      name: 'Chi',
      data: [52060, 58500],
      color: '#339933'
    }]
  });
//});

</script>

<br>


<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.2/jquery.min.js">
</script>
<script type="text/javascript" src="http://code.highcharts.com/highcharts.js">
</script>
<script type="text/javascript" src="http://code.highcharts.com/modules/exporting.js">
</script>

<!---<div id="container" style="min-width: 310px; height: 400px; margin: 0 auto">-->
<div id="container" style="width: 600px; height: 400px; margin: 0 auto">
</div>
<script type="text/javascript">


//$(function() {
  $('#container').highcharts({

    chart: {
      type: 'column'
    },
    title: {
      text: 'Zip Codes With and Without Bike Stations'
    },
    legend: {
      width: 300
    },
    xAxis: {
      categories: ['$0-35k', '$35-70k', '$70-105k', '$105k+']
    },

    yAxis: {
      allowDecimals: false,
      min: 0,
      max: 60,
      tickInterval: 10,
      title: {
        text: 'Percent of Total Zip Codes'
      },
      labels: {
        format: '{value}%'
      }
    },

    tooltip: {
      formatter: function() {
        return '<b>' + this.x + '</b><br/>' +
          this.series.name + ': ' + this.y + "%" + '<br/>' +
          'Total: ' + this.point.stackTotal + "%";
      }
    },


    plotOptions: {
      column: {
        stacking: 'normal',
        pointPadding: 0,
        groupPadding: 0.1
      }
    },

    series: [{
      name: 'NYC w/out Stns',
      data: [10, 41, 19, 6],
      color: '#ffcc80',
      stack: 'nyc'
    }, {
      name: 'NYC with Stns',
      data: [2, 6, 8, 8],
      color: '#ff9900',
      stack: 'nyc'
    }, {
      name: 'DC w/out Stns',
      data: [4, 4, 24, 9],
      color: '#80b3ff',
      stack: 'dc'
    }, {
      name: 'DC with Stns',
      data: [6, 6, 29, 17],
      color: '#0066ff',
      stack: 'dc'

    }, {
      name: 'Chi w/out Stns',
      data: [5, 20, 7, 0],
      color: '#66cc66',
      stack: 'chi'
    }, {
      name: 'Chi with Stns',
      data: [15, 31, 17, 5],
      color: '#339933',
      stack: 'chi'
    }]
  });
//});