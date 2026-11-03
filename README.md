# lecture-glossary-packs

Course glossary packs for the OfflineLecture app. The app fetches
`index.json`, matches a course name (中文 / English / русский),
and downloads the pack TSV into its local glossary-packs dir;
after that the pack works fully offline in the correction
pipeline.

Pack format (TSV): `term|variant<TAB>correct translation<TAB>wrong variants,comma separated`
