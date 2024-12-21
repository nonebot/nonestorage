# NoneStorage

Simple library that provides local storage folder detect

## Usage

```python
from pathlib import Path

from nonestorage import user_data_dir, user_config_dir, user_cache_dir

data_dir: Path = user_data_dir("appname")
config_dir: Path = user_config_dir("appname", roaming=True)
cache_dir: Path = user_cache_dir("appname", roaming=False)
```
