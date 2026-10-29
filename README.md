# MkDocs Material Setup Guide

This guide covers how to set up your local documentation environment using MkDocs and the Material theme. This is useful for documenting your personal studies, K8S/MLOps projects, and language learning notes in both English and Korean.

## Prerequisites

Make sure you have Python 3 installed on your system.

## Installation & Environment Setup

Create and activate a virtual environment, then install the required dependencies:
```
python3 -m venv .venv
source .venv/bin/activate

pip3 install "mkdocs-material==9.*"

pip3 install -r requirements.txt
mkdocs new .
```

## Saving Dependencies

Saving your installed package versions makes it easy to reproduce the same environment later on another computer.
```
pip3 freeze > requirements.txt
```

## Running the Development Server

To preview your documentation locally:
```
# running the blog
mkdocs serve
```

Open your browser and navigate to http://127.0.0.1:8000 to see your live-updating site.

## blog reference
- [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)
- [quartz](https://github.com/jackyzha0/quartz/tree/v5)