# README

Height profiles for the Moon crater Cyrillus.

## Codebook

### Input file "input/profile_000-180.txt"

Height profile from North to South.

- **position** (Numeric) [km] Distance from profile start point.
- **GLD100** (Numeric) [m] Height of point.
- **lon** (NUmeric) [°] Longitude of point.
- **lat** (NUmeric) [°] Latitude of point.

### Input file "input/profile_090-270.txt"

Height profile from West to East.

- **position** (Numeric) [km] Distance from profile start point.
- **GLD100** (Numeric) [m] Height of point.
- **lon** (NUmeric) [°] Longitude of point.
- **lat** (NUmeric) [°] Latitude of point.

### Input file "input/profile_135-315.txt"

Height profile from Southwest to Northeast.

- **position** (Numeric) [km] Distance from profile start point.
- **GLD100** (Numeric) [m] Height of point.
- **lon** (NUmeric) [°] Longitude of point.
- **lat** (NUmeric) [°] Latitude of point.

### Output file "output/profiles.csv"

- **dr** (Numeric) [km] Distance from crater center.
- **dh** (Numeric) [m] Height above lowest point within crater.
- **h** (Numeric) [m] Height of point.
- **direction** (String) Either "000-180" , "090-270", or "135-315".