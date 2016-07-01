# address-point-schema
A really simple schema for address point data


| Attribute    | Data Type | Description                                                                       |
|--------------|-----------|-----------------------------------------------------------------------------------|
| number       | Number    | The number of of the address.                                                     |
| street       | Text      | The name of the street.                                                           |
| unit         | Text      | For addresses with multiple units or structures within a given address            |
| lon          | Number    | The longitude of the location of the address pont                                 |
| lat          | Number    | The latitude of the location address point                                        |
| city         | Text      | Name of the City or Municipality in which the address falls                       |
| postcode     | Text      | Postcode or zip-code field in which the address falls                             |
| state        | Text      | State in which the address falls                                                  |
| id           | Text      | Unique indentifier                                                                |
| locationtype | Text      | Where the address point is placed: Rooftop, driveway, front door, parcel centroid |
