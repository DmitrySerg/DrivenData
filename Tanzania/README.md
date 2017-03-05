# DrivenData
###[Pump it Up: Data Mining the Water Table](https://www.drivendata.org/competitions/7/page/23/)

Data analysis competition


![](http://drivendata.materials.s3.amazonaws.com/pumps/pumping.jpg)


Predicting which pumps are functional, which need some repairs, and which don't work at all. 


### Data Preparation

*FIXED* - restored the values 

*REMADE* - created a new variable based on the original

*DROPPED* - excluded the variable from the dataset


- **DROPPED** `amount_tsh` - Total static head (amount water available to waterpoint)
- **REMADE** `date_recorded` - The date the row was entered
- **REMADE** `funder` - Who funded the well
- **FIXED** `gps_height` - Altitude of the well
- **REMADE** `installer` - Organization that installed the well
- **FIXED** `longitude` - GPS coordinate
- **FIXED** `latitude` - GPS coordinate
- **REMADE** `wpt_name` - Name of the waterpoint if there is one
- **DROPPED** `num_private` -
- **REMADE** `basin` - Geographic water basin
- **REMADE** `subvillage` - Geographic location
- **REMADE** `region` - Geographic location
- **DROPPED** `region_code` - Geographic location (coded)
- **DROPPED** `district_code` - Geographic location (coded)
- **REMADE** `lga` - Geographic location
- **REMADE** `ward` - Geographic location
- **FIXED** `population` - Population around the well
- **FIXED** `public_meeting` - True/False
- **DROPPED** `recorded_by` - Group entering this row of data
- **REMADE** `scheme_management` - Who operates the waterpoint
- **DROPPED** `scheme_name` - Who operates the waterpoint
- **FIXED** `permit` - If the waterpoint is permitted
- **REMADE** `construction_year` - Year the waterpoint was constructed
- **REMADE** `extraction_type` - The kind of extraction the waterpoint uses
- **DROPPED** `extraction_type_group` - The kind of extraction the waterpoint uses
- **REMADE** `extraction_type_class` - The kind of extraction the waterpoint uses
- **REMADE** `management` - How the waterpoint is managed
- **REMADE** `management_group` - How the waterpoint is managed
- **REMADE** `payment` - What the water costs
- **DROPPED** `payment_type` - What the water costs
- **REMADE** `water_quality` - The quality of the water
- **DROPPED** `quality_group` - The quality of the water
- **REMADE** `quantity` - The quantity of water
- **DROPPED** `quantity_group` - The quantity of water
- **REMADE** `source` - The source of the water
- **DROPPED** `source_type` - The source of the water
- **REMADE** `source_class` - The source of the water
- **REMADE** `waterpoint_type` - The kind of waterpoint
- **DROPPED** `waterpoint_type_group` - The kind of waterpoint


