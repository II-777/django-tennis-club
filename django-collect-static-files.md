---
title: django-collect-static-files
date: 2023-12-05 01:49
author: II-777
tags: #python #django #collect-static
---

## Django Collect Static Files

In settings.py:

DEBUG = False
STATIC_ROOT = BASE_DIR / 'productionfiles' 

```bash
py manage.py collectstatic 
```
