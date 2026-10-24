# LA Civic Spaces

Unofficial civic demonstration built using the City of Los Angeles' [LAPARKS.ORG Recreation and Parks Facilities dataset](https://data.lacity.org/d/ukgg-rgf9) (dataset ID `ukgg-rgf9`). Snapshot retrieved October 24, 2026; 829 rows. The dataset is attributed to the City of Los Angeles Department of Recreation and Parks. Its catalog metadata did not specify a machine-readable license; no broader rights are claimed.

Search 829 recreation-facility records by name or address, category, or council district. No third-party JavaScript, analytics or visitor tracking. Facility links point to public source pages; verify details before visiting. This is not an official or endorsed City of Los Angeles service.

For standalone local testing open `offline-test.html` (not included in the published build). For hosting deploy `index.html` and `facilities.json` together at site root.

## Facility details and legacy external links

The official dataset contains 829 facility website values under the historical `www.laparks.org` domain. The City of Los Angeles Department of Recreation and Parks announced its transition to `recreation.parks.lacity.gov` on December 11, 2025. Both hosts returned HTTP 403 in the controlled browser during verification; simply changing the hostname would not provide reliable access.

Facility cards therefore open an accessible in-app detail view, populated exclusively from the government dataset snapshot. Each detail view includes an exact-record link to the City of Los Angeles' Socrata public JSON API and an OpenStreetMap location link. The JSON link is labeled as a **municipal data record**, not as a live departmental facility page. No assertion is made that every government website will accept all clients. Always confirm opening hours and facility availability with the responsible location.
