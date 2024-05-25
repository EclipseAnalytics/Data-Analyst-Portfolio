| Column Name | Data Type | Description | Example Value | Constraints | Relationship |
|---|---|---|---|---|---|
| Name | String | Name of the moon | Moon | Not unique, 286 unique names | None |
| Diameter (km) | Float | Diameter of the moon in kilometers | 3474.2 | Not unique, 83 unique diameters | None |
| Planet | String | Name of the planet that the moon orbits | Earth | Not unique, 7 unique planets | Connects to 'Name' in the Planets dataset |