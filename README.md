---
title: Get tag
emoji: 🏷️
colorFrom: gray
colorTo: yellow
sdk: streamlit
sdk_version: 1.31.1
app_file: api.py
pinned: false
license: mit
URL: get-tag.streamlit.app
---

[![Build, install, lint, test and format](https://github.com/sycod/get_tag/actions/workflows/main.yaml/badge.svg)](https://github.com/sycod/get_tag/actions/workflows/main.yaml)


# [➡️ App available in production here ⬅️](https://get-tag.streamlit.app)

# Purpose

# 




- FIRST, in folder: `python -m venv .venv`
- in venv: make install
- streamlit run local api : `make run_api_local` (which runs `streamlit run api.py` in console)
- Chrome = no reload (session-state available), for full experience
- display folder tree

```bash
├── LICENSE
├── Makefile
├── README.md
├── api.py
├── config
│   ├── exclude_set.pkl
│   └── keep_set.pkl
├── favicon.ico
├── models
│   ├── w2v_cbow_lrovr_classifier.pkl
│   └── w2v_cbow_vectorizer
├── requirements.txt
├── src
│   ├── __pycache__
│   │   └── utils.cpython-311.pyc
│   └── utils.py
└── tests
    ├── __pycache__
    │   ├── test_eda.cpython-311-pytest-8.2.2.pyc
    │   ├── test_models.cpython-311-pytest-8.2.2.pyc
    │   ├── test_scrap_and_clean.cpython-311-pytest-8.2.2.pyc
    │   └── test_utils.cpython-311-pytest-8.2.2.pyc
    └── test_utils.py
```