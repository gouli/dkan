# DKAN Dataset Fields

Full list of default DKAN Dataset fields, their Drupal machine name, and equivalent fields in [http://www.w3.org/TR/vocab-dcat/](DCAT) and [http://project-open-data.github.io/](Project Open Data)

Label|Machine name|DCAT field|POD Field
------|-----------------|------------|------
Title              |title                    |[title](http://www.w3.org/TR/vocab-dcat/#Property:dataset_title)|[title](http://project-open-data.github.io/schema/#title)
Description        |body                     |[description](http://www.w3.org/TR/vocab-dcat/#Property:dataset_description)|[description](http://project-open-data.github.io/schema/#description)
Tags               |field_tags               |[keyword](http://www.w3.org/TR/vocab-dcat/#Property:dataset_keyword)|[keyword](http://project-open-data.github.io/schema/#keyword)
License            |field_license            ||[license](http://project-open-data.github.io/schema/#license)
Author             |field_author             ||
Spatial / Geographical Coverage Area         |field_spatial_geographical_area||
Spatial / Geographical Coverage Location     |field_spatial_geographical_cover|[spatial/geographical coverage](http://www.w3.org/TR/vocab-dcat/#Property:dataset_spatial)|[spatial](http://project-open-data.github.io/schema/#spatial)
Frequency          |field_frequency          |[frequency](http://www.w3.org/TR/vocab-dcat/#Property:dataset_frequency)|[accrualPeriodicity](http://project-open-data.github.io/schema/#accrualPeriodicity)
Publisher          |og_group_ref             |[publisher](http://www.w3.org/TR/vocab-dcat/#Property:dataset_publisher)|[publisher](http://project-open-data.github.io/schema/#publisher)
Temporal Coverage  |field_temporal_coverage  |[temporal coverage](http://www.w3.org/TR/vocab-dcat/#Property:dataset_temporal)|[temporal](http://project-open-data.github.io/schema/#temporal)
Granularity        |field_granularity        ||
Data Dictionary    |field_data_dictionary    ||[dataDictionary](http://project-open-data.github.io/schema/#dataDictionary)
Contact Name       |field_contact_name       ||[contactPoint](http://project-open-data.github.io/schema/#contactPoint)
Contact Email      |field_contact_email      ||[mbox](http://project-open-data.github.io/schema/#mbox)
Public Access Level|field_public_access_level||[accessLevel](http://project-open-data.github.io/schema/#accessLevel)
Additional Info    |field_additional_info    ||
Resources          |field_resources          |[distribution](http://www.w3.org/TR/vocab-dcat/#Property:dataset_distribution)|[distribution](http://project-open-data.github.io/schema/#distribution)
Related Content    |field_related_content    ||[references](http://project-open-data.github.io/schema/#references)
Identifier         |identifier               |[identifier](http://www.w3.org/TR/vocab-dcat/#Property:dataset_identifier)|[identifier](http://project-open-data.github.io/schema/#identifier)
Modified Date      |modified_date            |[modified data](http://www.w3.org/TR/vocab-dcat/#Property:dataset_modified_date)|[modified](http://project-open-data.github.io/schema/#modified)
Release Date       |release_date             |[release data](http://www.w3.org/TR/vocab-dcat/#Property:dataset_release_date)|[issued](http://project-open-data.github.io/schema/#issued)