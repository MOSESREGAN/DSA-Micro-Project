# Smart Network Flow and Resource Allocation System

A single-file, offline web app for modelling supply, transport capacity and demand as a flow network.

## How to run
Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari). No installation or internet connection is needed (fonts fall back to system fonts).

## Features
- Max flow (Edmonds-Karp, Dinic) and min-cost flow (successive shortest paths)
- Step-by-step augmenting path playback and solution verification checks
- Editable edges and nodes, drag-to-rearrange graph, preset scenarios and random generator
- Analysis: algorithm benchmark, cost against flow, capacity upgrade sensitivity, link failure impact
- Dashboard: KPI strip, executive summary, cost drivers, failure risk, utilization heatmap
- Undo / redo, edge filter, keyboard shortcuts (1-5 tabs, Ctrl+Z, Ctrl+Y)
- Four themes (Navy, Slate, Teal, Dark)
- Export: JSON, Python (NetworkX) script, text report, graph PNG, flows CSV, print report
