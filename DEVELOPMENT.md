## ⚙️ Environment Setup

To maintain this project, you need to set up the local development environment.

### 1. Prerequisites
* **Python 3.x**: Ensure Python is installed and added to your PATH.
* **Pip**: The Python package installer.

### 2. Dependency Installation
Run the following command from the root directory to install all required libraries (including `segno` for QR generation):

```powershell
pip install -r requirements.txt
```

## 🛠 Automation

To regenerate the entire physical mission deck (including Easter Egg clues), run this one-liner from the project root:

```powershell
python -c "import segno; base='[https://clover-da-rabbits-website.vercel.app/?clue=](https://clover-da-rabbits-website.vercel.app/?clue=)'; [segno.make(f'{base}{i}').save(f'{i}.png', scale=10, border=2) for i in [0] + list(range(1, 12)) + [99, 42069]]; print('--- All Mission Assets Generated! ---')"

