# Nigeria – Lassa fever outbreak

## Contents

This repository contains data extracted from the [Nigeria Centre for Disease Control and Prevention (NCDC)](https://ncdc.gov.ng/diseases/sitreps/?cat=5&name=An%20update%20of%20Lassa%20fever%20outbreak%20in%20Nigeria) bulletins. 

## Getting the data

**Direct download (CSV)**: https://raw.githubusercontent.com/fbranda/lassa-fever/main/surveillance/Surveillance_data_Lassa_Fever_outbreak_latest.csv

**Python** (requires `pandas`):
```python
import pandas as pd
df = pd.read_csv("https://raw.githubusercontent.com/fbranda/lassa-fever/main/surveillance/Surveillance_data_Lassa_Fever_outbreak_latest.csv")
```

**R** (requires `httr`):
```r
library(httr)
df <- read.csv(text=content(GET("https://raw.githubusercontent.com/fbranda/lassa-fever/main/surveillance/Surveillance_data_Lassa_Fever_outbreak_latest.csv")))
```

## License and attribution

This repository and data exports are published under the CC BY 4.0 license.
