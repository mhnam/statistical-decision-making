# Statistical Decision Making (45-752)

Tepper School of Business, Carnegie Mellon University

## Getting Started

### Google Colab (Recommended)
1. Open any notebook in Google Colab.
2. Run the first two code cells — they will automatically:
   - Install `tprstats` from GitHub
   - Download required data files from this repository
3. No Google Drive mounting needed!

### Local Setup (Optional)
1. Clone this repository:
   ```bash
   git clone https://github.com/mhnam/statistical-decision-making.git
   cd statistical-decision-making
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # macOS/Linux
   # .venv\Scripts\activate    # Windows
   pip install -r requirements.txt
   ```
3. Open any notebook in the `notebooks/` or `assignments/` folder.

## Folder Structure

```
├── data/                  # All course datasets (.xlsx)
├── notebooks/             # Lecture notebooks (01_notebook.ipynb, 02_notebook.ipynb, ...)
├── assignments/           # Assignment starter notebooks and solutions
├── guides/                # Setup guides (e.g., install_tprstats.ipynb)
└── */legacy/s25/          # Previous semester (Spring 2025) materials
```

## Data Loading

Each notebook includes a setup cell that handles data loading automatically. The cell detects whether you are running in Google Colab or locally. If data files are not found locally, they will be downloaded from this GitHub repository automatically.
