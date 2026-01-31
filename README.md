# SQL Tutorial

A hands-on SQL tutorial using Jupyter notebooks with real-world music data.

## Overview

This project provides an interactive introduction to SQL queries using Jupyter notebooks. It uses the **Chinook database**, a sample dataset that represents a digital media store. It includes the Track table and demonstrates fundamental SQL concepts and operations.

## Project Structure

```
├── read_sql.ipynb       # Interactive SQL tutorial notebook
├── data/
│   └── Track.csv        # Sample music track dataset
├── pyproject.toml       # Project configuration and dependencies
└── README.md            # This file
```

## Getting Started

### Prerequisites

- Python 3.x
- Poetry (for dependency management)

### Installation

1. Install dependencies using Poetry:

```bash
poetry install
```

2. Start the Jupyter notebook:

```bash
poetry run jupyter notebook read_sql.ipynb
```

## Contents

- **read_sql.ipynb**: Interactive notebook with SQL queries and explanations
- **Track.csv**: Sample dataset containing music track information

## Usage

Open `read_sql.ipynb` in Jupyter notebook to work through the interactive SQL tutorial. 