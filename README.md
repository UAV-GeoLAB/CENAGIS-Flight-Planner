# CENAGIS - Flight Planner (User Guide)

This repository is dedicated to the "CENAGIS - Flight Planner" application user guide.

---

## Local development

The Documentation is served at `http://localhost:8000/`.

1. Clone the repository and navigate to the folder.

    ```bash
    git clone https://github.com/UAV-GeoLAB/CENAGIS-Flight-Planner
    cd CENAGIS-Flight-Planner
    ```

2. Create and run a virtual environment.

    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3. Install dependencies.

    ```bash
    pip install -r requirements.txt
    ```

4. Run the documentation.

    ```bash
    zensical serve
    ```