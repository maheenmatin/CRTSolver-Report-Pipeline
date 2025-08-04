# CRTSolver-Report-Pipeline
Automated end-to-end data pipeline for generating quantitative performance reports for CRTSolver

**🧰 Installation**

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

5. **Add Jupyter Notebook functionality:**
   ```bash
   poetry add jupyter ipykernel
   ```

6. **Create kernel:**
   ```bash
   poetry run python -m ipykernel install --user --name=crtsolver-report-pipeline
   ```

7. **Run the notebook:**
   ```bash
   poetry run jupyter notebook
   ```

8. **Navigate to the comparative analysis:**
   - `src/` -> `crtsolver_report_pipeline` -> `comparative_analysis.ipynb`

9. **Set the kernel:**
   - `crtsolver-report-pipeline`

10. **Run the cells**
