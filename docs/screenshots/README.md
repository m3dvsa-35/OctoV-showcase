# Screenshots

All captures come from a local build running on synthetic, harmless test files and a stock Windows system binary (Notepad), in a 1600×900 window with the night theme.

## Already included

| File | Shows | Notes |
|---|---|---|
| `triage.png` | Risk score and the findings behind it | Cropped to the score card; point values and the internal processing list are hidden |
| `overview.png` | File identity, binary details, top findings | An internal rule ID is covered; the findings table below is cropped off |
| `strings-iocs.png` | Strings with IOC categories and filters | Synthetic strings with `example.com` / `example.net` domains only |
| `disassembly.png` | Disassembly next to the graph view | Notepad |
| `control-flow-graph.png` | Control-flow graph | Notepad |
| `relations.png` | Callers and callees around the entry point | Notepad |
| `compare.png` | Two builds compared function by function | Two synthetic builds |
| `azerbaijani-ui.png` | The same overview in Azerbaijani | Internal rule ID covered |

In every screenshot, the bottom "Findings" panel is cropped off because it lists internal rule IDs.

## Still worth capturing

Use only synthetic samples or stock Windows binaries. Before every capture, check that no username, machine name, local path, internal rule ID, score points or real sample is visible.

1. `pseudo-c.png`: the decompiled Pseudo-C view next to the disassembly (needs the optional decompiler installed)
2. `compare-detail.png`: a changed function opened side by side, instruction by instruction
3. `ai-preview.png`: the AI analyst's "this is exactly what will be sent" preview, with no endpoint name or key visible
4. `export.png`: the Export menu with YARA / Sigma / IOC options open
5. `normal-mode.png`: any view in the light "Normal" display mode
6. `command-palette.png`: the Ctrl+K command palette open

Save each one in this folder under the file name above. Then add it to the screenshot table in the main `README.md` and to the gallery in `docs/index.html`.
