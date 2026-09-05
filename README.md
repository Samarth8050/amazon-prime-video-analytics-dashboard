# Amazon Prime Video Interactive Dashboard

An interactive **Amazon Prime Video catalog analytics dashboard** built from a cleaned dataset of **9,668 titles**. The project explores content distribution across genre, rating, decade, type, and country using interactive filters, KPI cards, charts, and a detailed data table.

## Project Workflow

1. **Data Preparation & Cleaning**
   - Used ChatGPT to help identify required fields and clean the dataset.
   - Standardized values and prepared the final data for dashboard use.

2. **Dashboard Development**
   - Used structured prompts in Claude AI to generate and refine the interactive dashboard.
   - Built as a standalone HTML dashboard using JavaScript and Chart.js.

## Dashboard Features

- KPI summary cards
- Filter by content type: Movie / TV Show
- Filter by rating
- Release-year range filter
- Title search
- Titles by genre
- Genre share donut chart
- Titles by decade
- Titles by rating
- Movie vs. TV Show comparison
- Interactive genre selection across the dashboard
- Sortable detail table with pagination
- Light / dark mode toggle
- Responsive layout

## Dataset

The dashboard contains **9,668 Amazon Prime Video titles** and includes fields such as:

- Title
- Type
- Release Year
- Rating
- Duration
- Country
- Genre

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Chart.js
- ChatGPT — data preparation support
- Claude AI — prompt-assisted dashboard development

## Project File

Main dashboard file:

```text
prime-catalog-dashboard.html
```

To run the project locally, download the repository and open `prime-catalog-dashboard.html` in any modern web browser.

## How to Run

```bash
git clone <your-repository-url>
cd <repository-folder>
```

Then open:

```text
prime-catalog-dashboard.html
```

No server installation is required.

## Key Learning

This project helped me practice an **AI-assisted data analytics workflow**, combining data preparation, prompt engineering, dashboard design, data visualization, and interactive front-end development.

It also helped me understand how AI tools can support analysts in converting cleaned datasets into usable analytical dashboards while still requiring clear problem definition, data validation, and interpretation.

## Screenshot

<img width="821" height="530" alt="image" src="https://github.com/user-attachments/assets/b6f7f504-ab11-4ab1-a6cb-00dea485a642" />

<img width="823" height="649" alt="image" src="https://github.com/user-attachments/assets/edfedf4d-1811-4484-9e92-ca7ebc05a517" />

```markdown
![Amazon Prime Dashboard](dashboard-preview.png)
```

## Author

**Samarth Mirajkar**

- GitHub: [Samarth8050](https://github.com/Samarth8050)
- LinkedIn: https://www.linkedin.com/in/samarth-mirajkar-34b595280/

## Disclaimer

This project is created for learning and portfolio purposes. The dataset and dashboard are not affiliated with or endorsed by Amazon Prime Video.
