TensegrityReplayFetcher

A tiny client-side prototype that accepts CSV/JSON/ZIP files, extracts per-module time-series, normalizes timestamps to ISO-8601 UTC, validates presence of timestamp and numeric pose/orientation fields, and produces canonical per-module JSON files plus a short provenance README. No network calls. Use the page to upload files and download results.

Limitations: heuristic parsing only, no heavy archive formats beyond ZIP, simple checks for sampling uniformity and unit-size heuristics. Intended as a starting point.