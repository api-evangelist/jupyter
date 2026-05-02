# Jupyter (jupyter)

Project Jupyter is an open-source initiative that develops the software, open standards, and services for interactive computing across dozens of programming languages. The Jupyter ecosystem includes Jupyter Notebook, JupyterLab, Jupyter Server, JupyterHub, the Jupyter messaging protocol, and supporting client libraries.

**APIs.yml:** [https://raw.githubusercontent.com/api-evangelist/jupyter/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jupyter/refs/heads/main/apis.yml)

## Tags

- Interactive Computing
- Notebooks
- Data Science
- Python
- Scientific Computing
- Education

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Jupyter Notebook

Original Jupyter web application and REST API for creating, editing, and running notebooks. Includes the kernel messaging protocol and supporting OpenAPI, JSON Schema, and AsyncAPI artifacts.

**Human URL:** https://jupyter-notebook.readthedocs.io/

**Base URL:** http://localhost:8888

#### Properties

- [APIsYAML](https://raw.githubusercontent.com/api-evangelist/jupyter-notebook/refs/heads/main/apis.yml)
- [Documentation](https://jupyter-notebook.readthedocs.io/en/stable/rest_api.html)
- [Repository](https://github.com/jupyter/notebook)

### Jupyter Server

Backend that powers Jupyter Notebook, JupyterLab, and other Jupyter web applications. Exposes the core REST API and WebSocket messaging endpoints used to communicate with kernels.

**Human URL:** https://jupyter-server.readthedocs.io/en/latest/developers/index.html

**Base URL:** http://localhost:8888/api

#### Properties

- [APIsYAML](https://raw.githubusercontent.com/api-evangelist/jupyter-server/refs/heads/main/apis.yml)
- [Documentation](https://jupyter-server.readthedocs.io/en/latest/developers/rest-api.html)
- [Repository](https://github.com/jupyter-server/jupyter_server)

### JupyterHub

Multi-user server for Jupyter notebooks. Manages authentication, spawns and proxies multiple instances of the single-user Jupyter notebook server, and exposes a REST API for users, groups, services, tokens, and OAuth2.

**Human URL:** https://jupyterhub.readthedocs.io/

**Base URL:** http://localhost:8000/hub/api

#### Properties

- [APIsYAML](https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/apis.yml)
- [Documentation](https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html)
- [Repository](https://github.com/jupyterhub/jupyterhub)

### JupyterLab

Next-generation web-based interactive development environment for notebooks, code, and data, with a JupyterLab Server REST API for settings, workspaces, themes, translations, and licenses.

**Human URL:** https://jupyterlab.readthedocs.io/

**Base URL:** http://localhost:8888/lab/api

#### Properties

- [APIsYAML](https://raw.githubusercontent.com/api-evangelist/jupyterlab/refs/heads/main/apis.yml)
- [Documentation](https://jupyterlab.readthedocs.io/en/stable/)
- [Repository](https://github.com/jupyterlab/jupyterlab)

## Common Properties

- [Website](https://jupyter.org)
- [Documentation](https://docs.jupyter.org/)
- [Blog](https://blog.jupyter.org/)
- [GitHub Organization](https://github.com/jupyter)
- [Community](https://jupyter.org/community)
- [Support](https://discourse.jupyter.org/)
- [Security](https://jupyter.org/security)
- [YouTube](https://www.youtube.com/@ProjectJupyter)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
