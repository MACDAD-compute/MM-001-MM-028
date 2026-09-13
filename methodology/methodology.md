Methodology

## Scope

**MM-001–MM-028** is an ongoing photographic and geographic record of encounters with human-form roadside giants in the United States.

The archive documents figures encountered and photographed by Mac Dad. It is not intended to be a comprehensive census of surviving Muffler Men or roadside giants.

The project includes Muffler Men, Uniroyal Gals, and related human-form fiberglass roadside giants. The Golden Driller is retained as an intentional taxonomy exception and classified as `Other Roadside Giant`.

## Encounter

An encounter is a documented instance in which the artist was physically present with and photographed a roadside giant.

Multiple photographs made at the same location during the same visit constitute one encounter.

A later return to the same figure constitutes a new encounter. For this reason, a single figure or location may appear more than once in the archive.

Each encounter receives a unique identifier in the form `MM-###`.

Identifiers are assigned according to chronological order of encounter, not geography, figure type, or date of construction.

## Photographs

The photographic archive consists primarily of photographs made with an iPhone.

The photographs function as records of encounter. Differences in camera model, orientation, framing, image quality, and number of photographs are retained as characteristics of the source archive rather than normalized.

Original image files are not included in this repository.

## Location

Coordinates are derived primarily from GPS metadata embedded in the original photographic files.

Where necessary, locations may be corroborated through independent research.

The coordinates describe the documented encounter location and should not be interpreted as a comprehensive geographic inventory of roadside giants.

## Chronology

The geographic visualization connects encounters in chronological order.

The connecting line represents sequence only.

It does not represent roads traveled, transportation routes, distance traveled, or a reconstructed itinerary.

## Taxonomy

`figure_class` provides a standardized classification for visualization and analysis.

`figure_type` preserves more specific descriptive information about an individual figure or group.

The taxonomy currently includes:

- Bunyan / Lumberjack
- Classic
- Cowboy
- Halfwit / Snerd
- Indian
- Modified / Contemporary
- Multi-Figure Collection
- Other Roadside Giant
- Uniroyal Gal

Taxonomic categories describe the archive and may change as the project develops.

## Multi-figure sites

Some encounters occur at sites containing more than one roadside giant.

Where several figures were encountered as part of a single visit to one site, the encounter may be represented as a `Multi-Figure Collection` rather than assigning a separate encounter number to every figure.

The encounter is the primary unit of the archive.

## Research and identification

Names, figure types, histories, and locations may be corroborated using independent published sources.

External sources are used to identify and contextualize an encounter; they do not determine whether an encounter belongs in the archive.

Research confidence and source information are retained in the encounter-level dataset where available.

Uncertainty is preserved rather than silently converted into certainty.

## Data structure

`data/encounters.csv` contains one record per encounter.

`data/photo-metadata.csv` contains photograph-level metadata derived from the source image files.

The encounter dataset is derived from the photographic record. The photographic record precedes the researched taxonomy.

## Versions

The archive is versioned so that changes in identification, taxonomy, methodology, and interpretation remain visible over time.

The dataset is therefore treated not as a fixed catalog, but as an evolving record.
