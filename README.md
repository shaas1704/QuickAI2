# QuickAI 🤖

An AutoML system that enables developers to quickly build and deploy machine learning models without extensive knowledge of underlying algorithms.

## Overview

QuickAI simplifies the end-to-end ML workflow — from data ingestion to model training and deployment — through an intuitive interface powered by Flask, TensorFlow, and OpenAI GPT.

## Tech Stack

- **Backend:** Flask, TensorFlow, OpenAI GPT
- **ML:** AutoML pipeline with async job handling
- **UI:** 3-panel analytics dashboard
- **Infrastructure:** Built on fastai for high-level model components

## Key Features

- Automated model selection and training
- Async job handling for long-running training tasks
- 3-panel analytics dashboard for model performance tracking
- GPT-powered model recommendations

## Prerequisites

- Python 3.10+
- pip or conda

## Installation

Clone the repository:

```bash
git clone https://github.com/shaas1704/QuickAI2
cd QuickAI2
```

Install dependencies using conda (recommended):

```bash
conda env create -f environment.yml
conda activate quickai
```

Or using pip:

```bash
pip install -e ".[dev]"
```

## Running the App

```bash
flask run
```

Open [http://localhost:5000](http://localhost:5000) in your browser.

## Running Tests

```bash
nbdev_test
```

## Project Structure

```
QuickAI2/
├── nbs/          # Core notebooks and model logic
├── dev_nbs/      # Development notebooks
├── fastai/       # High-level ML components
├── images/       # Assets
└── setup.py      # Package configuration
```

## Contributing

After cloning, run:

```bash
nbdev_install_hooks
```

After making changes, run:

```bash
nbdev_prepare
```
