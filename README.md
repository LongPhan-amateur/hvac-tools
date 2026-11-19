# HVAC tools

Free calculation tools for HVAC engineers, published at https://longphan-amateur.github.io/hvac-tools/

| Tool | Path | What it does |
|---|---|---|
| Room dew point & supply air temperature | `/` | Condensation check on cold surfaces; supply air temperature from sensible/latent load; room sensible heat ratio line and ADP on the psychrometric chart; ADP from coil bypass factor and chilled water temperature |
| Chilled water supply temperature (ASHRAE) | `/chw-temperature/` | Apparatus dew point (bypass factor, chart line, or direct) and coil entering water temperature t_w = 2·t_ad − t_wb (ASHRAE HVAC Systems & Equipment 2016, Ch. 13, Eq. 11) |

Each tool is a single self-contained HTML file. Inputs are saved in the browser (localStorage).

Website: https://hochvacsbs.wordpress.com/calculation/
