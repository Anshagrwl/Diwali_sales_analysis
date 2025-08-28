<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Diwali Sales Analysis - README</title>
  <style>
    :root {
      --bg: #0f1724;
      --card: #0b1220;
      --muted: #94a3b8;
      --accent: #facc15;
    }
    body {
      font-family: Inter, ui-sans-serif, system-ui, Segoe UI, Roboto, Helvetica, Arial;
      margin: 0;
      background: linear-gradient(180deg,#071021 0%, #07162a 100%);
      color: #e6eef6;
    }
    .container {
      max-width: 980px;
      margin: 48px auto;
      padding: 28px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius: 14px;
      box-shadow: 0 10px 30px rgba(2,6,23,0.7);
    }
    header {
      display: flex;
      gap: 20px;
      align-items: center;
      margin-top: 20px;
    }
    .logo {
      width: 84px;
      height: 84px;
      border-radius: 12px;
      flex: 0 0 84px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg,var(--accent),#ef4444);
      font-weight: 700;
      color: #000;
      font-size: 22px;
    }
    h1 { margin: 0; font-size: 28px; }
    p.lead { color: var(--muted); margin: 6px 0 0; }
    .badges { margin-top: 12px; }
    .badges img { height: 20px; margin-right: 8px; }
    .grid {
      display: grid;
      grid-template-columns: 1fr 300px;
      gap: 20px;
      margin-top: 26px;
    }
    .card {
      background: rgba(255,255,255,0.02);
      padding: 18px;
      border-radius: 12px;
    }
    pre {
      background: #041225;
      padding: 12px;
      border-radius: 8px;
      overflow: auto;
    }
    img.screenshot {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 6px 20px rgba(2,6,23,0.6);
      border: 1px solid rgba(255,255,255,0.03);
    }
    footer {
      margin-top: 20px;
      color: var(--muted);
      font-size: 13px;
    }
    .banner {
      width: 100%;
      border-radius: 12px;
      margin-bottom: 20px;
      box-shadow: 0 8px 25px rgba(2,6,23,0.8);
    }
    @media (max-width:880px) {
      .grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- Banner Image -->
    <img src="assets/Diwali_Sales_Analysis_Banner.png" alt="Diwali Sales Analysis Banner" class="banner" />

    <header>
      <div class="logo">DSA</div>
      <div>
        <h1>Diwali Sales Analysis</h1>
        <p class="lead">An in-depth analysis of Diwali sales data to uncover business insights and improve marketing strategies.</p>
        <div class="badges">
          <img src="https://img.shields.io/badge/python-3.9+-blue.svg" alt="python" />
          <img src="https://img.shields.io/badge/pandas-1.5+-green" alt="pandas" />
          <img src="https://img.shields.io/badge/numpy-1.23+-yellow" alt="numpy" />
          <img src="https://img.shields.io/badge/matplotlib-visualization-orange" alt="matplotlib" />
        </div>
      </div>
    </header>

    <div class="grid">
      <main class="card">
        <h2>About the Project</h2>
        <p>This project analyzes Diwali sales data to understand customer purchasing behavior, improve marketing strategies, and boost overall sales performance. The dataset includes customer demographics, purchase history, and product categories.</p>

        <h2>Dataset</h2>
        <p>The dataset used in this analysis contains details about customers, their demographics, purchase amounts, and product categories.</p>

        <h2>Installation</h2>
        <ol>
          <li>Clone the repository:
            <pre><code>git clone https://github.com/USERNAME/diwali-sales-analysis.git</code></pre>
          </li>
          <li>Install dependencies:
            <pre><code>pip install -r requirements.txt</code></pre>
          </li>
          <li>Run the Jupyter Notebook:
            <pre><code>jupyter notebook Diwali_Sales_Analysis.ipynb</code></pre>
          </li>
        </ol>

        <h2>Analysis Performed</h2>
        <ul>
          <li>Data Cleaning & Preprocessing</li>
          <li>Exploratory Data Analysis (EDA)</li>
          <li>Customer Demographic Insights</li>
          <li>Top Product Categories & Purchase Trends</li>
          <li>Visualization of Key Findings</li>
        </ul>

        <h2>Technologies Used</h2>
        <ul>
          <li>Python</li>
          <li>Pandas</li>
          <li>Numpy</li>
          <li>Matplotlib / Seaborn</li>
          <li>Jupyter Notebook</li>
        </ul>

        <h2>Usage</h2>
        <p>After running the notebook, you can view interactive visualizations and insights about the sales trends, customer behavior, and product demand during Diwali.</p>

        <h2>License</h2>
        <p>This project is licensed under the MIT License — see the <code>LICENSE</code> file for details.</p>
      </main>

      <aside class="card">
        <h3>Project Screenshot</h3>
        <img class="screenshot" src="assets/Diwali_Sales_Analysis_Banner.png" alt="Diwali Sales Analysis Screenshot" />

        <h3 style="margin-top:14px">Dataset Size</h3>
        <p class="muted">~5000 rows | CSV format</p>

        <h3 style="margin-top:14px">Support</h3>
        <p class="muted">Open an issue or contact <a href="mailto:anshaggarwalll123.com">anshaggarwalll123.com</a>.</p>

        <h3 style="margin-top:14px">Author</h3>
        <p class="muted">Ansh Aggarwal — <a href="https://github.com/USERNAME">Anshagrwl</a></p>
      </aside>
    </div>

    <footer>
      <p>Update <code>README.html</code> with your repository URL and screenshot path before pushing it to GitHub.</p>
    </footer>
  </div>
</body>
</html>
