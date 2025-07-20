# Renovate reproduction repo: not poetry updates for `1.2.3.1, != 1.2.3.0`

```toml
[tool.poetry.dependencies]
python = "^3.11"
types-setuptools = "69.0.0.20240115, !=69.0.0.20240106"
types-pytz = ">= 2023.3.1.0"
```

Poetry allows ommiting `==` specifier according to
https://github.com/python-poetry/poetry/blob/427d922a9e74a068ba68f8927460ec28a2442c8a/docs/dependency-specification.md?plain=1#L129

Renovate only detects and provides updates for `types-pytz`.
