# International Demand Forecasting for Moroccan Local Products

## Project Overview

This project aims to forecast the demand for Moroccan local products, focusing primarily on international markets. Our goal is to develop effective strategies for the development and commercialization of these products. 

### Objectives:
- Forecast demand for Moroccan local products in international markets.
- Develop data-driven strategies for product development and commercialization.
- Use official website data, ensuring thorough data cleaning and preprocessing.
- Apply deep data analysis and machine learning techniques to identify the best forecasting models.
- Present performance metrics and insights through data visualization.
- Provide actionable strategies to enhance market presence and competitiveness.

## Project Structure

The project is organized into the following directories:

- **Data/Raw**: Contains raw data collected from official websites.
- **Data/Pre-processed**: Contains pre-processed and cleaned data ready for analysis.
- **Img**: Stores images of visualizations generated during the analysis.
- **Models**: Contains trained machine learning models.
- **Notebooks**: Jupyter notebooks documenting various stages of the project:
  - `Pre-processing.ipynb`: Data cleaning and preprocessing steps.
  - `Exploratory Data Analysis.ipynb`: Exploratory Data Analysis (EDA) to understand data characteristics.
  - `Models Training.ipynb`: Training of machine learning models.
  - `Model_Predicting.ipynb`: Making predictions using the trained models.

## Data Collection and Preprocessing

- **Data Sources**: Data was collected from TradeMap website that takes its data from Office des Changes.
- **Cleaning**: Data went thorough cleaning to identify relevant products and key characteristics for strategy formulation.
- **Preprocessing**: Data was preprocessed to ensure it is suitable for deep analysis and model training.

## Analysis and Modeling

- **Exploratory Data Analysis (EDA)**: We performed EDA to understand the data, identify trends, and detect patterns.
- **Machine Learning Techniques**: We explored the use of LinearRegression, XGBRegressor and LSTM to determine the best possible model for demand forecasting. The choice of algorithms will be justified based on performance metrics.
- **Model Evaluation**: Models are evaluated using relevant performance metrics, and the results are visualized to provide insights.

## Visualization and Insights

- **Data Visualization**: Visualization is used to present performance metrics and insights. This includes representations of data trends, model performance, and other relevant analyses.
- **Actionable Strategies**: Based on the data-driven analysis, we will provide actionable strategies to enhance the market presence and competitiveness of Moroccan local products.

## Deliverables

- Cleaned and preprocessed datasets.
- Jupyter notebooks documenting the analysis, modeling, and predictions.
- Trained machine learning models.
- Visualizations and performance metrics.
- Actionable strategies for market development and commercialization.

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```
2. **Navigate to the project directory**:
    ```bash
    cd <project-directory>
    ```
3. **Install required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Run the notebooks**:
    Open Jupyter Lab or Notebook and run the notebooks in the `Notebooks` directory to reproduce the analysis and results.

## Contributing

We welcome contributions to improve this project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any questions or suggestions, please contact us at [zakariabaou2002@gmail.com] or [nour.nouramellouk@gmail.com].

