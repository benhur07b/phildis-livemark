# Metro Manila

## Disaster events

Here are the number of disaster events in NCR cities and municipalities according to data in PHIL-DIS:

```yaml table
{% with area='ncr' %}
{% include 'blocks/tables/disasters_summary_events.yaml' %}
{% endwith %}

```

## Affected families and persons

Here are the total number of affected families and persons by disaster events in NCR according to data in PHIL-DIS:

```yaml table
{% with area='ncr' %}
{% include 'blocks/tables/disasters_summary_afp.yaml' %}
{% endwith %}

```

## Deaths, injuries, and missing persons

Here are the total number of deaths, injuries, and missing persons because of disaster events in NCR according to data in PHIL-DIS:

```yaml table
{% with area='ncr' %}
{% include 'blocks/tables/disasters_summary_dim.yaml' %}
{% endwith %}

```

## Damaged houses

Here are the total number of damaged houses because of disaster events in NCR according to data in PHIL-DIS:

```yaml table
{% with area='ncr' %}
{% include 'blocks/tables/disasters_summary_dh.yaml' %}
{% endwith %}

```

## Damage to agricultural, infrastructure, and private property

Here are the estimated damage to properties because of disaster events in NCR according to data in PHIL-DIS:

```yaml table
{% with area='ncr' %}
{% include 'blocks/tables/disasters_summary_aip.yaml' %}
{% endwith %}

```