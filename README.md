London Council Meetings Data
This repository publishes council meeting information collected from publicly available council RSS feeds.
Files
`meetings.csv` — meeting-level records identified through the feeds, with links to council sources where available.
`source_status.csv` — collection status and last successful check for each council.
Coverage and limitations
The collector currently has 30 enabled London authority feeds. Havering, Lambeth and Newham are not automatically collected due to access restrictions or technical errors observed in GitHub Actions.
This is a publication-monitoring dataset, not a comprehensive calendar. An absent meeting does not mean no meeting is scheduled. Agenda and minutes fields marked `unknown` have not been verified as absent. Consult the relevant council website for confirmation.
Records may be incomplete or delayed, and council meeting URLs should be checked against the original sources. `source_status.csv` should be checked before relying on a council's coverage.
Data updates
The private collector publishes these CSV files after a successful collection run. This repository contains only the published data, not the collector's scripts or credentials.
