# Buddhist Countries Standard List

A standardized list of countries and regions significant to Buddhism, blending geopolitical standards with religious and historical context. This list is designed for use by Buddhist organizations, developers, researchers, and the community for applications, analytics, and documentation.

## Structure

The list is built upon the **ISO 3166-1 alpha-3** standard for country codes, ensuring international compatibility. Each entry is enriched with information relevant to the Buddhist context.

### Fields Explained

-   `isoCode`: The 3-letter country code as defined by ISO 3166-1.
-   `name`: The English short name of the country or region.
-   `tradition`: The primary Buddhist tradition(s) present (e.g., Theravada, Mahayana, Vajrayana). "Multi-Tradition" indicates significant presence of multiple schools. "Historical" denotes major historical importance with a small modern population.
-   `significance`: A brief note on the country's role, history, or current state within the Buddhist world.
-   `category`: Classifies the entry for filtering:
    -   `core`: Countries where Buddhism is the majority religion or a dominant cultural force.
    -   `significant_community`: Countries with a large, influential minority Buddhist population.
    -   `diaspora_hub`: Countries with significant and diverse Buddhist populations primarily from the diaspora.
    -   `historical`: Countries of major historical importance with a very small modern presence.

## Usage

This list is available in a machine-readable JSON format.

**JSON File:** [`buddhist-countries.json`](buddhist-countries.json)

The JSON structure is an array of objects:

```json
[
    {
        "isoCode": "MMR",
        "name": "Myanmar",
        "tradition": "Theravada",
        "significance": "One of the most predominantly Buddhist countries. Theravada Buddhism is deeply integrated into the culture. A major center for Vipassana meditation.",
        "category": "core"
    }
]