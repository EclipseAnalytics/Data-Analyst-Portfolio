| Column Name | Data Type | Description | Example Value | Constraints | Relationship |
|---|---|---|---|---|---|
| Date | Date | Date of the position observation | 1800-01-01 | Not unique, 4812 unique dates | None |
| Name | String | Name of the celestial body | Sun | Not unique, 10 unique celestial bodies | Connects to 'Name' in Planets dataset. Multiple instances possible. |
| X | Spatial | X-coordinate in the solar system (in AU) | 0 | Not unique, 43309 unique values | None |
| Y | Spatial | Y-coordinate in the solar system (in AU) | 0 | Not unique, 43309 unique values | None |
| Z | Spatial | Z-coordinate in the solar system (in AU) | 0 | Not unique, 43309 unique values | None |