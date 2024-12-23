| Column Name | Data Type | Description | Example Value | Constraints | Relationship |
|---|---|---|---|---|---|
| Name | String | Name of the star | Sun | Unique, 8 unique stars | None |
| Stellar ID | Integer | Unique identifier for the star | 101 | Not unique, 8 unique IDs | Connects to 'Stellar ID' in Planets dataset |
| Mass (1024 kg) | String | Mass of the star in multiples of 10241024 kg | 1988500 | Not unique, 8 unique values | None |
| GM (x 106 km3/s2) | String | Standard gravitational parameter in 106106 km³/s² | 1.32712E+11 | Not unique, 8 unique values | None |
| Volume (1012 km3) | String | Volume of the star in 10121012 km³ | 1408000 | Not unique, 8 unique values | None |
| Diameter (km) | String | Diameter of the star in kilometers | 1392700 | Not unique, 8 unique values | None |
| Mean density (kg/m3) | Integer | Mean density of the star in kg/m³ | 1408 | Not unique, 8 unique values | None |
| Surface gravity (eq.) (m/s2) | Integer | Surface gravity of the star in m/s² | 274 | Not unique, 8 unique values | None |
| Escape velocity (km/s) | Float | Escape velocity of the star in km/s | 617.7 | Not unique, 8 unique values | None |
| Ellipticity | Float | Ellipticity of the star | 0.00005 | Not unique, 1 unique value | None |
| Moment of inertia (I/MR2) | Float | Moment of inertia ratio I/MR² | 0.07 | Not unique, 2 unique values | None |
| Visual magnitude V(1,0) | Float | Visual magnitude from 1 AU | -26.74 | Not unique, 8 unique values | None |
| Absolute magnitude | Float | Absolute magnitude of the star | 4.83 | Not unique, 8 unique values | None |
| Luminosity (1024 J/s) | Float | Luminosity of the star in 10241024 J/s | 382.8 | Not unique, 8 unique values | None |
| Mass conversion rate (106 kg/s) | Integer | Mass conversion rate in 106106 kg/s | 4300 | Not unique, 8 unique values | None |
| Mean energy production (10-3 J/kg s) | Float | Mean energy production rate in 10−310−3 J/kg s | 192.3 | Not unique, 8 unique values | None |
| Surface emission (106 J/m2s) | Float | Surface emission rate in 106106 J/m²s | 63.3 | Not unique, 8 unique values | None |
| Spectral type | String | Spectral type of the star | G2V | Not unique, 5 unique types | None |