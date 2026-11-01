# Nepal Flood Data Repository
## Organizing and Preserving Disaster-Related Information

### Introduction
Natural disasters have caused serious damage in Nepal, especially during the monsoon season. In September 2024, heavy rainfall caused floods and landslides that affected many communities, damaged infrastructure, and resulted in loss of life.

I created this digital repository to collect, organize, and preserve selected information about these disasters. The repository is intended for students, researchers, and people interested in disaster management and data analysis.

### Repository Objectives
- Organize flood and landslide information in one accessible location.
- Preserve selected disaster-related datasets and documentation.
- Provide metadata to explain the contents and origins of the files.
- Make the information easier to locate, understand, and reuse.

### Repository Organization
The repository is organized into the following folders:

- **data/incidents/** – Province-level incident statistics and district-level human impacts.
- **data/impacts/** – Infrastructure damage and estimated economic losses.
- **data/geographic/** – Geographic reference locations in selected affected districts.
- **documentation/** – Summary report and descriptive metadata.

### Digital Collection
The repository contains five primary digital items:

1. **flood_incidents.csv** – Selected province-level disaster incident statistics from 2024.
2. **affected_districts.csv** – Selected district-level deaths, injuries, missing persons, and rescue information.
3. **flood_damage.csv** – Selected infrastructure damage estimates.
4. **flood_locations.geojson** – Geographic reference points for cities in affected districts.
5. **flood_summary.md** – Summary of the collection, its purpose, and limitations.

### Metadata
The file **documentation/metadata.csv** describes all five digital items. Its fields include title, creator, date, coverage, format, description, source, and file path. These fields are based on Dublin Core descriptive metadata concepts.

### Data Sources
- National Disaster Risk Reduction and Management Authority (NDRRMA), Nepal: https://bipad.gov.np/
- Preliminary Loss and Damage Assessment of Flood and Landslide 2024: https://bipad.gov.np/uploads/publication_pdf/Loss_and_Damage_Assessment_of_Flood_and_Landslide_2024_Updated_compressed.pdf
- GeoNames: https://www.geonames.org/

### Data Quality and Limitations
The datasets contain selected information from preliminary reports and do not represent a complete record of all floods in Nepal. Some figures cover both floods and landslides. The geographic coordinates identify reference cities rather than the exact locations of disaster incidents.

The original organizations remain the sources of their reported information. I organized and documented selected records for this academic project.

### Access and Preservation
This repository is publicly accessible through GitHub. GitHub provides version history, helping track file changes. However, GitHub alone is not a complete long-term digital preservation solution. Maintaining additional backups would improve preservation.

### Conclusion
This project demonstrates how digital repositories can help organize disaster-related information and make it easier for users to discover and understand important records. The repository may be expanded with additional verified datasets and geographic information in the future.
