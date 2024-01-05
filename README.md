# EDA-Application Error Solved

**ERROR:**
PydanticImportError: `BaseSettings` has been moved to the `pydantic-settings` package. See [migration guide](https://docs.pydantic.dev/2.5/migration/#basesettings-has-moved-to-pydantic-settings) for more details. For further information visit [Pydantic Errors](https://errors.pydantic.dev/2.5/u/import-error)

Use following code:
```python
import numpy as np  
import pandas as pd  
import streamlit as st  
import seaborn as sns  
from ydata_profiling import ProfileReport  
from streamlit_pandas_profiling import st_profile_report
```

Instead of 
```python
import numpy as np  
import pandas as pd  
import streamlit as st  
import seaborn as sns  
from pandas_profiling import ProfileReport  
from streamlit_pandas_profiling import st_profile_report
```

