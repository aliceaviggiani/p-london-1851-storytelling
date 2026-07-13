## Same place, same time
## London, 1851: who and where in the Great Exhibition year

An interactive timeline-map and scrollytelling piece locating thirty historical
figures in London during the year of the Great Exhibition, where each one
lived, worked, or simply visited, and, above all, what they were thinking at
the time.

**Live site:** *https://aliceaviggiani.github.io/p-london-1851-storytelling/index.html*

## How we built it

The interactive timeline-map and its storytelling are the result of a
systematic analysis of the eighty-five assigned readings from the syllabus of
the class *Pratt in London: Design and Museums on Site*. The material was
programmatically converted to plain text and analyzed, cross-referencing the
data in search of insights: names, places, years, and recurring expressions
were identified, extracted, and counted across the corpus. William Morris was
the most quoted name, appearing in sixteen of the readings; the V&A and the
British Museum were the most cited places; and 1851 caught the attention,
flagged as a key date by fourteen readings, more than any other year, with
fifty-two mentions in all. Nineteen of the thirty figures on the map are named
at least once in the readings.

The insights from this analysis set the topic that conducts the narrative: a
photograph of one time and one place, and everything that was happening inside
it — narratives that occasionally cross, and stories with no direct connection
at all. After being designed in Figma, the website was built with the support
of Claude and Claude Code. Every location was verified against a primary or
documentary source: the 1851 census, English Heritage blue plaques, diaries,
or letters. Figures without a confirmable London address in 1851 appear as
visitors at documented locations or were left off entirely. No approximate
addresses were accepted.

The final product is a single HTML file (plus the Leaflet library and map
tiles, loaded at runtime), published with GitHub Pages. The map runs on
Leaflet, with a custom base style built in Mapbox Studio on OpenStreetMap
data. The timeline is drawn as SVG from the same dataset, and the portraits
are period images sourced from Wikimedia Commons and embedded in the file. The
AI assisted with corpus analysis, research retrieval, drafting, and code. The
topic, the argument, the design, and the writing are the author's.

## Credits

Alice Viggiani  
June 2026

Project created as a final assignment for the class *Pratt in London: Design
and Museums on Site*, taught by Professor Sarah Lichtman.

Base map © Mapbox © OpenStreetMap, custom style by the author.
Pictures via Wikimedia.

Full references are listed in the Credits panel of the site.
