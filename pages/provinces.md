# Provinces

## Disaster events

```html markup
<iframe title="Number of disasters in Philippine provinces based on PHIL-DIS data" aria-label="Map" id="datawrapper-chart-OEvXh" src="https://datawrapper.dwcdn.net/OEvXh/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="776"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();
</script>
```

<br><br>
Here are the number of disaster events in the Philippine provinces according to data in PHIL-DIS:

```yaml table
{% with area='provinces', name='Province', namefield='province' %}
{% include 'blocks/tables/disasters_summary_events.yaml' %}
{% endwith %}

```

## Affected families and persons

```html markup
<iframe title="Number of disasters in Philippine provinces based on PHIL-DIS data (Copy)" aria-label="Map" id="datawrapper-chart-rftij" src="https://datawrapper.dwcdn.net/rftij/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="776"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();
</script>
```

<br><br>
Here are the total number of affected families and persons by disaster events in the Philippine provinces according to data in PHIL-DIS:

```yaml table
{% with area='provinces', name='Province', namefield='province' %}
{% include 'blocks/tables/disasters_summary_afp.yaml' %}
{% endwith %}

```

## Deaths, injuries, and missing persons


<br><br>
Here are the total number of deaths, injuries, and missing persons because of disaster events in the Philippine provinces according to data in PHIL-DIS:

```yaml table
{% with area='provinces', name='Province', namefield='province' %}
{% include 'blocks/tables/disasters_summary_dim.yaml' %}
{% endwith %}

```

## Damaged houses


<br><br>
Here are the total number of damaged houses because of disaster events in the Philippine provinces according to data in PHIL-DIS:

```yaml table
{% with area='provinces', name='Province', namefield='province' %}
{% include 'blocks/tables/disasters_summary_dh.yaml' %}
{% endwith %}

```

## Damage to agricultural, infrastructure, and private property


<br><br>
Here are the estimated damage to properties because of disaster events in the Philippine provinces according to data in PHIL-DIS:

```yaml table
{% with area='provinces', name='Province', namefield='province' %}
{% include 'blocks/tables/disasters_summary_aip.yaml' %}
{% endwith %}

```