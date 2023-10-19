# [Most-Starred Python Projects on GitHub](https://hharpreetk.github.io/python-most-starred-repos-data-viz/)

This script makes an API call to GitHub's API to retrieve information about the most-starred Python projects. It then visualizes the data using Plotly, showing the number of stars each project has received.

## Requirements

- Python 3.x
- Requests library (`pip install requests`)
- Plotly library (`pip install plotly`)

## Usage

1. Make sure you have Python 3.x installed on your machine.

2. Install the required libraries by running the following commands in your terminal:

   ```bash
   pip install requests plotly
   ```

3. Run the script by executing the following command:

   ```bash
   python pop_repos.py
   ```

4. The script will make an API call to retrieve data about the most-starred Python projects on GitHub. It will then generate a bar chart using Plotly, showing the number of stars for each project.

## How It Works

- The script uses the `requests` library to make an API call to GitHub's search API. It queries for Python repositories with more than 10,000 stars and sorts the results by the number of stars.

- The retrieved repository data is processed, and active links to the GitHub repositories are generated.

- The data is visualized using Plotly's bar chart. Each bar represents a repository and displays the number of stars it has received. Hovering over a bar shows additional information, including the repository owner, a truncated description, and a link to the repository.

- The color of the bars is customized to yellow with reduced opacity for better visualization.

## License

This script is provided under the [MIT License](LICENSE).
