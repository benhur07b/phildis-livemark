# Provinces

## Disaster events


<br><br>
Here are the number of disaster events in the Philippine provinces according to data in PHIL-DIS:

```yaml table
{% with area='provinces', name='Province', namefield='province' %}
{% include 'blocks/tables/disasters_summary_events.yaml' %}
{% endwith %}

```

## Affected families and persons


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