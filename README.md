# Environment

- Python 3.8.10
- Poetry 1.2.0b1


# Version 1

```toml
[tool.poetry]
name = "poetry-optional-no-extra"
version = "0.1.0"
description = ""
authors = ["charbonnierg <guillaume.charbonnier@araymond.com>"]
readme = "README.md"
packages = [{include = "pkg", from="src"}]

[tool.poetry.dependencies]
python = "^3.8"
click = {version = "^8.1.2", optional = true}


[build-system]
requires = ["poetry-core"]
build-backend = "poetry.core.masonry.api"
```

Associated wheel metadata:

```
Metadata-Version: 2.1
Name: poetry-optional-no-extra
Version: 0.1.0
Summary: 
Author: charbonnierg
Author-email: guillaume.charbonnier@araymond.com
Requires-Python: >=3.8,<4.0
Classifier: Programming Language :: Python :: 3
Classifier: Programming Language :: Python :: 3.8
Classifier: Programming Language :: Python :: 3.9
Classifier: Programming Language :: Python :: 3.10
Requires-Dist: click (>=8.1.2,<9.0.0)
Description-Content-Type: text/markdown
```


# Version 2

Dependency is no longer optional.

```toml
[tool.poetry]
name = "poetry-optional-no-extra"
version = "0.2.0"
description = ""
authors = ["charbonnierg <guillaume.charbonnier@araymond.com>"]
readme = "README.md"
packages = [{include = "pkg", from="src"}]

[tool.poetry.dependencies]
python = "^3.8"
click = "^8.1.2"


[build-system]
requires = ["poetry-core"]
build-backend = "poetry.core.masonry.api"
```

Associated wheel metadata:

```
Metadata-Version: 2.1
Name: poetry-optional-no-extra
Version: 0.2.0
Summary: 
Author: charbonnierg
Author-email: guillaume.charbonnier@araymond.com
Requires-Python: >=3.8,<4.0
Classifier: Programming Language :: Python :: 3
Classifier: Programming Language :: Python :: 3.8
Classifier: Programming Language :: Python :: 3.9
Classifier: Programming Language :: Python :: 3.10
Requires-Dist: click (>=8.1.2,<9.0.0)
Description-Content-Type: text/markdown
```


