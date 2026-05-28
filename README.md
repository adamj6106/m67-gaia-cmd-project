# Estimating M67's Age Using Gaia Data and a Color-Magnitude Diagram

This project uses Gaia data to create a color-magnitude diagram of the M67 star cluster. The goal was to identify the main sequence turnoff region and use it to estimate whether M67 is an older open cluster.

## Tools Used
- Python
- pandas
- matplotlib
- Gaia DR3 data

## Project Steps
1. Queried Gaia data near M67
2. Loaded the data into Python
3. Created an unfiltered CMD
4. Filtered stars using parallax and proper motion
5. Identified the main sequence and turnoff region
6. Compared the result to M67's commonly reported age of about 4 billion years

## Limitations
This project used Gaia apparent G magnitude rather than fully corrected absolute magnitude. The turnoff region was estimated visually, so the age estimate should be treated as approximate. A stronger future version would use isochrone fitting.
