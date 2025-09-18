<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://platform.simplicite.io//logos/logo250.png)
* * *

`OpenDataSoft` module definition
================================

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=simplicite-modules-OpenDataSoft&metric=alert_status)](https://sonarcloud.io/dashboard?id=simplicite-modules-OpenDataSoft)

### Introduction

**OpenDataSoft** remote business objects examples.

### Import

To import this module:

- Create a module named `OpenDataSoft`
- Set the settings as:

```json
{
	"type": "git",
	"origin": {
		"uri": "https://github.com/simplicitesoftware/module-opendatasoft.git"
	}
}
```

- Click on the _Import module_ button

`OdsCommunesFrance` business object definition
----------------------------------------------

OpenDataSoft _cities of France_ object.

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      |
|--------------------------------------------------------------|------------------------------------------|----------|-----------|----------|----------------------------------------------------------------------------------|
| `odsComComCode`                                              | char(10)                                 | yes*     | yes       |          | City code                                                                        |
| `odsComComName`                                              | char(255)                                | yes      | yes       |          | City name                                                                        |
| `odsComComNameUpper`                                         | char(255)                                |          | yes       |          | City name (uppercase)                                                            |
| `odsComCoords`                                               | geocoords                                |          | yes       |          | Geographical coordinates                                                         |
| `odsComRegCode`                                              | char(10)                                 |          | yes       |          | Region code                                                                      |
| `odsComRegName`                                              | char(255)                                |          | yes       |          | Region name                                                                      |
| `odsComDepCode`                                              | char(10)                                 |          | yes       |          | Area code                                                                        |
| `odsComDepName`                                              | char(255)                                |          | yes       |          | Area name                                                                        |

`OdsJCDecauxBikeStations` business object definition
----------------------------------------------------

OpenDataSoft _Remarquable trees in Paris_ object.

**Note**: the fields are retreived from OpenDataSoft metadata

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      |
|--------------------------------------------------------------|------------------------------------------|----------|-----------|----------|----------------------------------------------------------------------------------|

