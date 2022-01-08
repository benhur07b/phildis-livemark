# Get Data

## List of disaster events

```yaml remark
type: primary
text: A list of disaster events in the Philippines. Digitized from Office of Civil Defense reports
```
### Get it here: [CSV](../data/tabular/disasters_list_all.csv), .ODS, .XLSX

The dataset contains the following information:

 - **disaster_id** - unique disaster identifier in PHIL-DIS
 - **name_int** - international name of the disaster
 - **name_local** - local name of the disaster
 - **type** - main type of the disaster
 - **subtype** - subtype of the disaster
 - **date_start** - start date of the disaster
 - **date_end** - end date of the disaster
 

## Disaster events in Metro Manila

```yaml remark
type: primary
text: A dataset of disaster events that contains information regarding affected areas in Metro Manila. Digitized from Office of Civil Defense reports.
```
### Get it here: [CSV](../data/tabular/disasters_events_ncr.csv), .ODS, .XLSX

The dataset contains the following information:
- All the primary disaster information found in the disaster list dataset
- **psgc** - Philippine Standard Geographic Code of the affected city or municipality
- **psgc_ph** - same as psgc but with a "PH" prefix
- **municity** - name of the city or municipality
- **affected_families**	- number of affected families
- **affected_persons** - number of affected persons
- **dead** - number of people who died
- **injured** - number of people who were injured
- **missing** - number of people who went missing
- **damaged_houses_full** - number of completely damaged/destroyed houses
- **damaged_houses_partial** - number of partially damaged houses
- **damaged_properties_agri** - estimated damage to agricultural properties (in Millions)
- **damaged_properties_infra** - estimated damage to infrastructure properties (in Millions)	
- **damaged_properties_private** - estimated damage to private properties (in Millions)
- **damage_total** - estimated total damage (in Millions)


## Disaster events in the provinces

```yaml remark
type: primary
text: A dataset of disaster events that contains information regarding affected provinces. Digitized from Office of Civil Defense reports.
```
### Get it here: [CSV](../data/tabular/disasters_events_provinces.csv), .ODS, .XLSX

The dataset contains the following information:
- All the primary disaster information found in the disaster list dataset
- **psgc** - Philippine Standard Geographic Code of the affected province
- **psgc_ph** - same as psgc but with a "PH" prefix
- **province** - name of the province
- **affected_families**	- number of affected families
- **affected_persons** - number of affected persons
- **dead** - number of people who died
- **injured** - number of people who were injured
- **missing** - number of people who went missing
- **damaged_houses_full** - number of completely damaged/destroyed houses
- **damaged_houses_partial** - number of partially damaged houses
- **damaged_properties_agri** - estimated damage to agricultural properties (in Millions)
- **damaged_properties_infra** - estimated damage to infrastructure properties (in Millions)	
- **damaged_properties_private** - estimated damage to private properties (in Millions)
- **damage_total** - estimated total damage (in Millions)


## Disaster events in the Philippines

```yaml remark
type: primary
text: A dataset of disaster events that contains both the disaster_events_provinces and disaster_events_ncr data. Digitized from Office of Civil Defense reports.
```
### Get it here: [CSV](../data/tabular/disasters_events_all.csv), .ODS, .XLSX

The dataset contains the following information:
- All the primary disaster information found in the disaster list dataset
- **psgc** - Philippine Standard Geographic Code of the affected area
- **psgc_ph** - same as psgc but with a "PH" prefix
- **province_municity** - name of the province, city, or municipality
- **affected_families**	- number of affected families
- **affected_persons** - number of affected persons
- **dead** - number of people who died
- **injured** - number of people who were injured
- **missing** - number of people who went missing
- **damaged_houses_full** - number of completely damaged/destroyed houses
- **damaged_houses_partial** - number of partially damaged houses
- **damaged_properties_agri** - estimated damage to agricultural properties (in Millions)
- **damaged_properties_infra** - estimated damage to infrastructure properties (in Millions)	
- **damaged_properties_private** - estimated damage to private properties (in Millions)
- **damage_total** - estimated total damage (in Millions)


## Summary of disasters in Metro Manila

```yaml remark
type: primary
text: A summary of disaster events for cities and municipalities in Metro Manila. Summarized from disaster_events_ncr data.
```
```yaml remark
type: warning
text: Administrative boundaries in the GeoJSON are simplified and indicative. You can use the CSV file to join the data to your own vector files.
```

### Get it here: [GEOJSON](../data/spatial/phildis_ncr.geojson), [CSV](../data/tabular/disasters_summary_ncr.csv)

The dataset contains the following information:
- **psgc_ph** - Philippine Standard Geographic Code with a "PH" prefix
- **municity** - name of the city or municipality
- **affected_families**	- number of affected families
- **affected_persons** - number of affected persons
- **dead** - number of people who died
- **injured** - number of people who were injured
- **missing** - number of people who went missing
- **damaged_houses_full** - number of completely damaged/destroyed houses
- **damaged_houses_partial** - number of partially damaged houses
- **damaged_properties_agri** - estimated damage to agricultural properties (in Millions)
- **damaged_properties_infra** - estimated damage to infrastructure properties (in Millions)	
- **damaged_properties_private** - estimated damage to private properties (in Millions)
- **damage_total** - estimated total damage (in Millions)


## Summary of disasters in the provinces

```yaml remark
type: primary
text: A summary of disaster events for provinces of the Philippines. Summarized from disaster_events_provinces data.
```
```yaml remark
type: warning
text: Administrative boundaries in the GeoJSON are simplified and indicative. You can use the CSV file to join the data to your own vector files.
```

### Get it here: [GEOJSON](../data/spatial/phildis_provinces.geojson), [CSV](../data/tabular/disasters_summary_provinces.csv)

The dataset contains the following information:
- **psgc_ph** - Philippine Standard Geographic Code with a "PH" prefix
- **province** - name of the province
- **affected_families**	- number of affected families
- **affected_persons** - number of affected persons
- **dead** - number of people who died
- **injured** - number of people who were injured
- **missing** - number of people who went missing
- **damaged_houses_full** - number of completely damaged/destroyed houses
- **damaged_houses_partial** - number of partially damaged houses
- **damaged_properties_agri** - estimated damage to agricultural properties (in Millions)
- **damaged_properties_infra** - estimated damage to infrastructure properties (in Millions)	
- **damaged_properties_private** - estimated damage to private properties (in Millions)
- **damage_total** - estimated total damage (in Millions)
