# Agent guidance

- Add new manifests to `bucket/` using lowercase kebab-case filenames. Validate each manifest against Scoop's JSON schema.
- Inspect archive contents before setting `bin`, `shortcuts`, or `extract_dir`.
- For new manifests, run the app and verify its data locations before configuring `persist`.
