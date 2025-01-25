## Prerequisites 

- Requires [DVLA-Vehicle-Enquiry-Service](https://github.com/jampez77/DVLA-Vehicle-Enquiry-Service/)
- Template a sensor like below to show the MOT date as (DD/MM/YYYY)

```yaml

{{ states('sensor.dvla_REGPLATE_motexpirydate') | regex_replace('(\\d{4})-(\\d{2})-(\\d{2})', '\\3/\\2/\\1') }}

```


- Template a sensor like below to show the TAX date as (DD/MM/YYYY)

```yaml

{{ states('sensor.REGPLATE_taxduedate') | regex_replace('(\\d{4})-(\\d{2})-(\\d{2})', '\\3/\\2/\\1') }}

```

## Prerequisites 

This checks every 7/15/30 days for both TAX & MOT

