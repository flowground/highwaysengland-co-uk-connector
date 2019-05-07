# ![LOGO](logo.png) Highways England API **flow**ground Connector

## Description

A generated **flow**ground connector for the Highways England API API (version v1).

Generated from: https://api.apis.guru/v2/specs/highwaysengland.co.uk/v1/swagger.json<br/>
Generated at: 2019-05-07T17:42:19+03:00

## API Description



## Authorization

This API does not require authorization.

## Actions

### Returns list of areas

*Tags:* `Areas`

#### Input Parameters
* `version` - _required_

### Returns details of selected area

*Tags:* `Areas`

#### Input Parameters
* `area_Ids` - _required_
* `version` - _required_

### Get Site DailyQuality

*Tags:* `Quality`

#### Input Parameters
* `siteId` - _required_
* `start_date` - _required_ - The start date of the report in the format ddmmyyyy (i.e 31012016)
* `end_date` - _required_ - The end date of the report in the format ddmmyyyy (i.e 31012016)
* `version` - _required_

### Get Site OverallQuality

*Tags:* `Quality`

#### Input Parameters
* `sites` - _required_ - Get site quality by site id delimited by ,
* `start_date` - _required_ - The start date of the report in the format ddmmyyyy (i.e 31012016)
* `end_date` - _required_ - The end date of the report in the format ddmmyyyy (i.e 31012016)
* `version` - _required_

### Gets the daily report.

> Get's the report.

*Tags:* `Reports`

#### Input Parameters
* `report_type` - _required_ - Report Type Id (i.e Daily, Monthly, Annual)
* `sites` - _required_ - Comma separated list of site Ids.
* `start_date` - _required_ - The start date of the report in the format ddmmyyyy (i.e 31012016)
* `end_date` - _required_ - The end date of the report in the format ddmmyyyy (i.e 31012016)
* `page` - _required_ - The page offset to return.
* `page_size` - _required_ - The number of rows to return.
* `reportSubTypeId` - _optional_
* `version` - _required_

### Gets the daily report.

> Get's the report.

*Tags:* `Reports`

#### Input Parameters
* `report_type` - _required_ - Report Type Id (i.e Daily, Monthly, Annual)
* `sites` - _required_ - Comma separated list of site Ids.
* `start_date` - _required_ - The start date of the report in the format ddmmyyyy (i.e 31012016)
* `end_date` - _required_ - The end date of the report in the format ddmmyyyy (i.e 31012016)
* `page` - _required_ - The page offset to return.
* `page_size` - _required_ - The number of rows to return.
* `reportSubTypeId` - _optional_
* `version` - _required_

### Get a list of sites

*Tags:* `Sites`

#### Input Parameters
* `version` - _required_

### Get selected sites

*Tags:* `Sites`

#### Input Parameters
* `site_Ids` - _required_ - site id
* `version` - _required_

### Return list of site types

*Tags:* `SiteTypes`

#### Input Parameters
* `version` - _required_

### Returns the layer metadata for the LayerId specified.

*Tags:* `SiteTypes`

#### Input Parameters
* `siteType_Id` - _required_ - 1 = MIDAS, 2 = TAME, 3 = TMU, 4 = TRADS Legacy
* `version` - _required_

## License

**flow**ground :- Telekom iPaaS / highwaysengland-co-uk-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
