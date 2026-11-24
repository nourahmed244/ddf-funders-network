# DDF Funders Network

An interactive network of the funders that have pooled money with the Doris Duke Foundation (DDF), grouped by DDF program (Arts, Building Bridges, Child Well-being, Environment, Medical Research).

- **Nodes** are funders, sized by total assets (latest IRS 990-PF or audited statement, mostly 2024) and coloured by DDF program. Funders in more than one program are split pies.
- **Edges** link each funder to DDF and to the other funders of the same program. Width is the combined size of the programs they share, not what either funder gave. Dashed edges mean the program size was not disclosed.
- **Controls:** program filters, a grant-program picker, a year range with Play, zoom and reset. Click any funder for its programs and sources. Category colours can be changed from the legend.

## Run it

It is a single static page: open `index.html` in a browser, or serve the folder with GitHub Pages. It loads D3 v7.8.5 and the Inter font from public CDNs.

## Data notes

Programs, funders, amounts and years come from DDF's website and partners' announcements; each program in the page links its source. Asset figures mix book and market value, so treat node sizes as approximate. Coordinated pledges where money was not pooled (such as the 2020 five-foundation payout increase) are left out.
