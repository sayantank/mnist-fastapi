# mnist-fastapi

A simple web app to identify numerical digits, using **fastai** and **FastAPI**.

Training notebook can be found at `nbs` folder.

## Run locally
* Make sure you have PyTorch and fastai in your system.
* `pip install requirements.txt`
* `uvicorn main:app --host 0.0.0.0 --port 8000`
