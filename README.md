# Gene Venn Diagram Tool
 
An interactive, self-contained web tool for visualising overlaps between gene sets with on-hover protein function summaries and one-click enrichment analysis links.
 
**Live tool:** [https://leurwu.github.io/venn/venn_diagram_tool.html](https://ntmytran.github.io/venn/)
 
---
 
## Features
 
- **2–6 gene sets** — paste gene symbols in any delimiter (space, comma, newline, semicolon)
- **Rename sets** — click the name field to label sets (e.g. "WT 24h", "K219N mut")
- **Venn diagram** — SVG-based, interactive; hover intersection numbers to preview genes, click to jump to results
- **Gene function popups** — hover any gene pill to see its full name and RefSeq/Alliance of Genome Resources summary paragraph; click to open NCBI Gene page
- **Enrichment links** per region — STRING-db, Reactome, g:Profiler (GO), KEGG
- **Colour customisation** — preset palettes (default, pastel, bold, earth, colorblind-safe, grayscale), per-set colour pickers, and a **Meh** button that randomises a set of contrasting pastels from a curated hue-family pool
- **PNG export** — tight crop (no excess white border), 600 dpi default (4800 px wide), auto-calculated height
- **CSV export** — one column per region (intersections first, then exclusives), gene count in header
- **Offline gene DB** — gene names and summaries are embedded directly in the HTML from NCBI; no API calls at runtime
