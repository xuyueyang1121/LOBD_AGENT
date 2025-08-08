# LOBD_AGENT
> This repository contains the official code implementation for the paper **"XXXXXXXXXXXXX"**.
##  Environment Setup

To install all dependencies, run:

```bash
pip install -r requirements.txt
```

## Pretrained Model and Agent Configuration
cph_2025.6.22.pkl: This is the pretrained classification model.
Please replace it with the correct local path to your own model file if needed.

LOBD-team-config.json: This is the AutogenStudio agent configuration file.
You must update the model API key and base URL with your own credentials.

Example snippet from LOBD-team-config.json:
```bash
{
  "config": {
    "model": "your-model-name",
    "api_key": "your-api-key",
    "base_url": "https://your-base-url"
  }
}
```
## Getting Started
To run the pipeline, use the following command:

```bash
autogenstudio ui --port 8081 --appdir /your_cph_2025.6.22.pkl_file
```
