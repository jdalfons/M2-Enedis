# M2-Enedis

<p align="center">
    <img src="assets/logo.png" alt="M2-Enedis Logo" width="200">
</p>

## Application Status

| Status                | Description                          |
|-----------------------|--------------------------------------|
| **Current Version**   | 1.0.0                                |
| **Python Version**    | 3.11                                 |

## Overview

M2-Enedis is a dashboard application built using Dash and Plotly. It provides various functionalities including data visualization, machine learning predictions, and interactive maps. The application is designed to help users understand and analyze energy consumption data.


## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/greentech_dashboard.git
    cd greentech_dashboard
    ```

2. **Create a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

## Running the Application

1. **Start the Dash application:**
    ```sh
    python app.py
    ```

2. **Open your web browser and navigate to:**
    ```
    http://127.0.0.1:8050/
    ```

## Running API

1. **Run API**
```sh
    uvicorn main:app --reload
```

## Example API Request

To send a request to the API, you can use the following example with `curl`:

```sh
curl -X POST "http://127.0.0.1:8000/your-endpoint" -H "Content-Type: application/json" -d '{
    "Type_batiment": "Residential",
    "Annee_construction": 1990,
    "Classe_inertie_batiment": "High",
    "Hauteur_sous_plafond": 2.5,
    "Surface_habitable_logement": 100.0,
    "Type_energie_principale_chauffage": "Electric",
    "Isolation_toiture": 1,
    "Code_INSEE": "75001"
}'
```

Replace `"http://127.0.0.1:8000/your-endpoint"` with the actual endpoint of your API.

## Usage

- **Home Page:** Provides an introduction and key performance indicators (KPIs).
- **Prediction Page:** Allows users to make predictions using the trained machine learning model.
- **Context Page:** Displays various statistics and graphs.
- **Map Page:** Shows interactive maps for data visualization.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

| Nom                        | GitHub Profile                     |
|----------------------------|------------------------------------|
| SOURAYA AHMED ABDEREMANE   | [Sahm269](https://github.com/Sahm269) |
| BERTRAND KLEIN             | [bertrandklein](https://github.com/bertrandklein) |
| JUAN DIEGO ALFONSO OCAMPO  | [jdalfons](https://github.com/jdalfons) |
| PIERRE BOURBON             | [pbrbn](https://github.com/pbrbn)  |

## Contact

For any questions or inquiries, please contact Juan Diego A. at [jalfonsooc@univ-lyon2.fr](mailto:jalfonsooc@univ-lyon2.fr).

