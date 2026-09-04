# Healthcare Facility Proximity Analysis in Kenya

**GIS screening analysis of health-facility distribution, 5 km proximity zones, and county-level facility counts in Kenya.**

![Health facility distribution across Kenya](healthcare-accessibility-kenya/Healthcare_Accessibility_Kenya_Map1_Distribution.png)

## Project at a glance

| | |
|---|---|
| **Planning question** | Where are mapped health facilities concentrated, and which locations fall within 5 km proximity zones? |
| **Study area** | Kenya |
| **Tools** | ArcMap, buffer analysis, spatial join, and thematic mapping |
| **Outputs** | Three national-scale maps |

## Workflow

1. Mapped health-facility locations across Kenya.
2. Created 5 km buffers around the mapped facilities as straight-line proximity zones.
3. Used a spatial join to calculate facility counts by county.
4. Designed thematic maps to communicate distribution and possible service gaps.

## Map gallery

### Health-facility distribution

![Health facility distribution map](healthcare-accessibility-kenya/Healthcare_Accessibility_Kenya_Map1_Distribution.png)

### Five-kilometre proximity zones

![Health facility buffer map](healthcare-accessibility-kenya/Healthcare_Accessibility_Kenya_Map2_Buffer.png)

### Facility counts by county

![Health facility counts by county](healthcare-accessibility-kenya/Healthcare_Accessibility_Kenya_Map3_Counts.png)

## Skills demonstrated

- Point-distribution mapping
- Buffer analysis
- Spatial joins and county-level aggregation
- Choropleth and thematic mapping
- Professional map layout design

## Limitations and responsible use

- A 5 km straight-line buffer is a proximity indicator, not a road-network or travel-time analysis.
- Proximity does not measure staffing, medicines, opening status, affordability, facility capacity, or quality of care.
- Results depend on the completeness and date of the source facility records.
- The maps identify areas for further investigation; they should not be treated as confirmed measures of health-care access.

## Related project

For a more detailed county-level analysis using population, facility, hospital-bed, Python, and GIS data, see [Kenya Health Service Accessibility Analysis](https://github.com/viviwammbachi/Kenya_Health_Service_Accessibility_Analysis).

## Repository contents

The map images and original project notes are available in the [project folder](healthcare-accessibility-kenya).

## Author

**Vivian Mbachi** — GIS & Data Analyst, Nairobi, Kenya  
[GitHub profile](https://github.com/viviwammbachi) · [LinkedIn](https://www.linkedin.com/in/vivianmbachi-gis)
