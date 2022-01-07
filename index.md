# Philippines Disaster Information System (PHIL-DIS) Project

```yaml remark
type: primary
text: PHIL-DIS is a continuous work in progress. The data provided by PHIL-DIS is only as accurate and precise as its sources—e.g. official government reports.
```

The Philippines Disaster Information System (PHIL-DIS) was developed to establish a database for disasters in the Philippines that explicitly includes spatial information. PHIL-DIS aims to gather data on disaster events from official government reports, map disaster events and their patterns in the country, produce a web-based platform that has a capacity to display textual, tabular, visual and spatial  information on disaster events, and formulate a template that can be used to systematically gather data on disaster events.

## Status
PHIL-DIS currently has information on: **350** disaster events from **1897** to **2017**. 

[Help us build a free, open, accurate, and comprehensive Philippine disaster database.](/pages/contrib-data.html)

## Disaster event timeline
Number of disaster event data per year in PHIL-DIS: 

```yaml chart
data:
    url: data/tabular/disasters_list_all.csv
height: 400
width: 800
mark:
    type: bar
    cornerRadiusEnd: 2
    tooltip: true
    width:
        band: 0.8
encoding:
    x:
        timeUnit: year
        field: date_year
        type: ordinal
        title: year
    y:
        aggregate: count
        title: disasters
    color:
        field: type
```

### Timeline of tropical cyclones
Number of tropical cyclone disaster event data per year in PHIL-DIS:  

```json chart
{% with type='Tropical Cyclone' %}
{% include 'blocks/charts/timeline-type.json' %}
{% endwith %}

```

## Disasters per type
Here are the total number of disasters per type in PHIL-DIS:

```yaml chart
data:
    url: data/tabular/disasters_list_all.csv
height: 600
width: 600
mark:
    type: bar
    cornerRadiusEnd: 2
    tooltip: true
    height:
        band: 0.8
encoding:
    x:
        aggregate: count
        title: disasters
        field: type
        type: quantitative
        axis:
            grid: false
            labelFontSize: 13
    y:
        field: type
        type: ordinal
        title: false
        sort: -x
        axis:
            labelFontSize: 13
```

## Contact us
<strong>DEPARTMENT OF GEOGRAPHY</strong><br>
College of Social Sciences and Philosophy<br>
University of the Philippines Diliman
