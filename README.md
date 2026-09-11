# RemoteOps QC prototype

A browser-based prototype for remote drilling / MWD operations.

Included:
- Current jobs board and map
- Survey CSV upload + QC
- MD monotonicity, duplicates, ranges, spacing and DLS checks
- Optional gravity and magnetic-dip QC
- Well-plan CSV upload
- Plan-vs-actual inclination / azimuth / TVD / position comparison
- Final-log / bottom-line QC against job metadata and deepest survey
- WebSocket prototype for live operations
- Sample CSV files

## Important
Do not put proprietary customer well data on a public GitHub Pages site.

This version processes CSV files locally in the browser. A production version should have authentication, encrypted storage, role-based permissions, audit logs and a private backend.

For true real-time operations, connect your WITS/WITSML/vendor data source to a backend normalization/QC service, then push approved data to this dashboard over authenticated WebSockets or an API.
