# Brightcon 2023 - LLM talk by Selim Youssry from Sapiologie

Jupyter notebook of the presentation at Brightcon 2023 on LLMs applied to LCAs

Setup:

- You need an `OPENAI_API_KEY`, so grab one and set it as an environment variable.
- You need to download ELCD from OpenLCA Nexus, import it in OpenLCA 2, then export as JSON-LD, and put the data under `datasets/elcd/`, where the path to `datasets` should be filled in the notebook under `DSROOT`.

Install and run:

- Get Python 3.11
- Get Poetry
- Run `poetry env use python3.11`
- Run `poetry install`
- Run `poetry run jupyter lab`
- Play with the notebook!

