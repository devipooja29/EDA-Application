# EDA-Application Error Solved

If you are using the following code

`import numpy as np
import pandas as pd
import streamlit as st
import seaborn as sns
from pandas_profiling import ProfileReport
from streamlit_pandas_profiling import st_profile_report`

You will get following error
PydanticImportError: `BaseSettings` has been moved to the `pydantic-settings` package. See https://docs.pydantic.dev/2.5/migration/#basesettings-has-moved-to-pydantic-settings for more details. For further information visit https://errors.pydantic.dev/2.5/u/import-error

Use the following code for successful run of code:
import numpy as np
import pandas as pd
import streamlit as st
import seaborn as sns
from ydata_profiling import ProfileReport
from streamlit_pandas_profiling import st_profile_report
