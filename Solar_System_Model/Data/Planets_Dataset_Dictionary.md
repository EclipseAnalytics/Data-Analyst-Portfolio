| Column Name | Data Type | Description | Example Value | Constraints | Relationship |
|---|---|---|---|---|---|
| Name | String | Name of the planet | Mercury | Unique, 19 unique planets | Connects to 'Planet' in Moons dataset and 'Name' in Solar System XYZ Positions dataset |
| Mass (1024kg) | String | Mass of the planet in multiples of 10241024 kg | 0.33 | Not unique, 19 unique values | None |
| Diameter (km) | String | Diameter of the planet in kilometers | 4879 | Not unique, 19 unique values | None |
| Density (kg/m3) | Integer | Mean density of the planet in kg/m³ | 5427 | Not unique, 16 unique values | None |
| Gravity (m/s2) | Float | Surface gravity of the planet in m/s² | 3.7 | Not unique, 16 unique values | None |
| Escape Velocity (km/s) | Float | Escape velocity of the planet in km/s | 4.3 | Not unique, 15 unique values | None |
| Rotation Period (hours) | Float | Length of one rotation period of the planet in hours | 1407.6 | Not unique, 19 unique values | None |
| Length of Day (hours) | Float | Length of one day on the planet in hours | 4222.6 | Not unique, 19 unique values | None |
| Distance from Sun (106 km) | Float | Average distance from the sun in 106106 km | 57.9 | Not unique, 18 unique values | None |
| Perihelion (106 km) | Float | Closest distance to the sun in 106106 km | 46 | Not unique, 17 unique values | None |
| Aphelion (106 km) | Float | Farthest distance from the sun in 106106 km | 69.8 | Not unique, 17 unique values | None |
| Orbital Period (days) | Float | Orbital period around the sun in days | 88 | Not unique, 18 unique values | None |
| Orbital Velocity (km/s) | Float | Orbital velocity of the planet in km/s | 47.4 | Not unique, 16 unique values | None |
| Orbital Inclination (degrees) | Float | Orbital inclination with respect to the ecliptic plane | 7 | Not unique, 14 unique values | None |
| Orbital Eccentricity | Float | Eccentricity of the orbital path | 0.205 | Not unique, 13 unique values | None |
| Obliquity to Orbit (degrees) | Float | Tilt of the planet's axis in degrees | 0.034 | Not unique, 12 unique values | None |
| Mean Temperature (C) | Integer | Average surface temperature in Celsius | 167 | Not unique, 14 unique values | None |
| Surface Pressure (bars) | Float | Surface pressure on the planet in bars | 0 | Not unique, 5 unique values | None |
| Number of Moons | Integer | Total number of moons the planet has | 0 | Not unique, 9 unique values | None |
| Ring System? | String | Indicates if the planet has a ring system (Yes/No) | No | Not unique, 2 unique values | None |
| Global Magnetic Field? | String | Indicates if the planet has a global magnetic field (Yes/No) | Yes | Not unique, 2 unique values | None |
| Stellar ID | Integer | Identifier for the star the planet orbits | 101 | Not unique, 2 unique values | Connects to 'Stellar ID' in Solar dataset |