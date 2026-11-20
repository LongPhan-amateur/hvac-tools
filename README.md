# HVAC tools

Free calculation tools for HVAC engineers, published at https://longphan-amateur.github.io/hvac-tools/

| Tool | Path | What it does |
|---|---|---|
| Room dew point & supply air temperature | `/` | Condensation check on cold surfaces; supply air temperature from sensible/latent load; room sensible heat ratio line and ADP on the psychrometric chart; ADP from coil bypass factor and chilled water temperature |
| AHU process, selection & schedule | `/ahu/` | AHU sections with diagram (return/100% fresh air, energy recovery wheel, plate HX, run-around coil, heat pipe, desiccant wheel, pre/reheat coils, humidifier, fans), process on the psychrometric chart, coil/fan/size/weight estimate, AHU schedule and coordination tables |
| Chilled water supply temperature (ASHRAE) | `/chw-temperature/` | Apparatus dew point (bypass factor, chart line, or direct) and coil entering water temperature t_w = 2·t_ad − t_wb (ASHRAE HVAC Systems & Equipment 2016, Ch. 13, Eq. 11) |

Each tool is a single self-contained HTML file. Inputs and room summaries are saved in the browser (localStorage) and shared between the tools: the chilled water and AHU tools can link data from the dew point tool (all / by Room ID / by AC equipment). Summaries export to Excel (.xlsx) and PDF.

Website: https://hochvacsbs.wordpress.com/calculation/
