# CRTSolver-Report-Pipeline
Automated end-to-end data pipeline for generating quantitative performance reports for CRTSolver

**### 🧰 Installation**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/maheenmatin/CRTSolver-Report-Pipeline
   cd CRTSolver-Report-Pipeline
   ```

2. **Optional: Install Poetry** (if not already installed):
   ```bash
   pipx install poetry
   ```

3. **Install dependencies:**
   ```bash
   poetry install
   ```

4. **Activate the environment:**
   ```bash
   poetry env activate
   ```

5. **Run the solver:**
   ```bash
   poetry run python -m crtsolver_report_pipeline.comparative_analysis.ipynb
   ```

6. poetry add ipykernel notebook

7. poetry run python -m ipykernel install --user --name=crtsolver-report-pipeline

8. poetry run jupyter notebook
