# Canadian Student Intake & PR Analysis

[![License](https://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=plastic&logo=appveyor)](https://opensource.org/licenses/MIT)

## Table Of Contents

- [Description](#description)
- [Deployed Project Link](#deployed-project-link)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [GitHub](#github)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)
- [Tests](#tests)
- [License](#license)

![GitHub repo size](https://img.shields.io/github/repo-size/brij0/Power-BI-Canada-Study-Permit-analysis?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/brij0/Power-BI-Canada-Study-Permit-analysis?style=plastic)

## Description

This project is a **Power BI data analysis** that evaluates **student intake data** over the past 10 years across all Canadian provinces. The project correlates **student intake trends** with **Permanent Residency (PR) assignments** and provides insights into the **countries of origin** for PRs. The project uses various analytical techniques to visualize the data, explore trends by province, and break down the different PR streams based on the points required for eligibility.

Key features include:
- **Trend analysis** of student permits issued over a 10-year span.
- **Correlation between student intake and PRs** assigned.
- **Drill-down by province** to identify regions with the highest student intake.
- **Breakdown of PR streams**, including the points required for eligibility.
- **Visualizations of PR origins** and **student permit distributions** using the Google Maps API for geographical insights.

### Tools & Technologies:
- **Power BI** for data visualization and dashboard creation.
- **Python (Numpy, Pandas)** and **Jupyter Notebook** for data cleaning and manipulation.
- **Google Maps API** for visual representation of PR and student data by country and province.

## Deployed Project Link

Currently, the project is not deployed online. For further details, please contact the project maintainer.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/brij0/Power-BI-Canada-Study-Permit-analysis.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Power-BI-Canada-Study-Permit-analysis
    ```

3. **Install necessary dependencies** (if using Python scripts for data cleaning):
    ```bash
    pip install -r requirements.txt
    ```

4. **Download the necessary datasets** and save them in the `/datasets` folder.

5. **Run the Python data cleaning scripts**:
    ```bash
    python data_cleaning.py
    ```

6. **Open Power BI Desktop** and load the `.pbix` file to explore the dashboard.

## Usage

1. Open the **Power BI dashboard** to explore trends in student intake across Canada.
2. **Drill-down functionality** allows you to see detailed data by province or country of origin for PR assignments.
3. Use **Google Maps visualizations** to see a geographical representation of PR origin countries and student permit distributions.
4. Analyze the **points required for PR eligibility** for various streams, such as the Master’s Graduate stream, PhD stream, and more.

### Key Analytical Insights:
- **Student Intake**: A 10-year trend of student intake data, broken down by province and country of origin.
- **PR Assignment Correlation**: Analysis of how student intakes correlate with PR assignments across different provinces.
- **Top Countries for PR**: Drill down by country to see the countries contributing most to PR assignments.
- **PR Stream Breakdown**: Compare eligibility points across different PR streams, such as the Foreign Worker stream, International Student stream, and more.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make changes and commit: `git commit -m 'Added a new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

Please ensure your contributions follow best practices and are well-documented.

## Github

You can find this repository and more projects at my GitHub profile:

- [GitHub Profile](https://github.com/brij0)

## Contact

Feel free to reach out for any questions, feedback, or collaborations:

- Email: bthakrar@uoguelph.ca

## Acknowledgements

Special thanks to the following individuals and resources for their help and support during this project:

- **YouTube Tutorials**: The following YouTube tutorials were instrumental in guiding the use of Python and Power BI:
  - [Make EVERY Power BI Report Look GREAT! by Bas Dohmen](https://www.youtube.com/watch?v=v6fP8gyCLLc)
  - [Microsoft Power BI for Visualization by Alex The Analyst](https://www.youtube.com/watch?v=g0m5sEHPU-s)
  
- **OpenAI GPT**: For support in providing insights and generating clear explanations.

## Tests

Currently, there are no tests available for this project. If you would like to contribute, please create a test plan.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
