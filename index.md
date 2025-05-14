<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Juhi Shahi | Data Scientist Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body class="bg-gray-50 text-gray-800 font-sans leading-relaxed">

  <!-- Header -->
  <header class="bg-white shadow">
    <div class="container mx-auto px-6 py-6 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Juhi Shahi</h1>
      <nav class="space-x-4 text-sm">
        <a href="#projects" class="hover:text-blue-600">Projects</a>
        <a href="#experience" class="hover:text-blue-600">Experience</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="py-16 bg-gradient-to-br from-blue-100 to-blue-50 text-center">
    <h2 class="text-4xl font-bold mb-4">Hello, I'm Juhi 👋</h2>
    <p class="text-lg text-gray-700 max-w-xl mx-auto">
      Data Analyst | ML Enthusiast | Automating insights with Python, SQL & Power BI.
    </p>
    <div class="mt-6 flex justify-center space-x-4">
      <a href="https://linkedin.com/in/juhi-shahi-830719220" target="_blank" class="text-blue-600 text-xl"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/juhi-shahi" target="_blank" class="text-gray-700 text-xl"><i class="fab fa-github"></i></a>
      <a href="mailto:juhishahi321@gmail.com" class="text-red-600 text-xl"><i class="fas fa-envelope"></i></a>
    </div>
  </section>

  <!-- Skills -->
  <section class="py-12 bg-white">
    <div class="container mx-auto px-6 max-w-5xl">
      <h3 class="text-2xl font-semibold mb-6">🛠 Technical Skills</h3>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
        <div class="bg-blue-100 p-4 rounded text-center">Python</div>
        <div class="bg-blue-100 p-4 rounded text-center">SQL</div>
        <div class="bg-blue-100 p-4 rounded text-center">Power BI</div>
        <div class="bg-blue-100 p-4 rounded text-center">Scikit-learn</div>
        <div class="bg-blue-100 p-4 rounded text-center">Streamlit</div>
        <div class="bg-blue-100 p-4 rounded text-center">Selenium</div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-12 bg-gray-50">
    <div class="container mx-auto px-6 max-w-5xl">
      <h3 class="text-2xl font-semibold mb-6">📂 Projects</h3>

      <!-- Project 1 -->
      <div class="mb-6 p-4 bg-white rounded shadow">
        <h4 class="text-xl font-bold">Netflix Data Analysis</h4>
        <p>Visualized viewing patterns using Python, clustering viewer profiles from Netflix dataset.</p>
        <a href="https://github.com/juhi-shahi/Binge-Watch-Breakdown-Analyzing-Netflix-Content-Trends" class="text-blue-600 hover:underline">GitHub Repo</a>
      </div>

      <!-- Project 2 -->
      <div class="mb-6 p-4 bg-white rounded shadow">
        <h4 class="text-xl font-bold">Car Price Prediction</h4>
        <p>Built regression model with Scikit-learn and deployed via Streamlit for used car pricing.</p>
        <a href="https://github.com/juhi-shahi/car-price-prediction" class="text-blue-600 hover:underline">GitHub Repo</a>
      </div>

      <!-- Project 3 -->
      <div class="mb-6 p-4 bg-white rounded shadow">
        <h4 class="text-xl font-bold">Customer Churn Prediction</h4>
        <p>Identified at-risk telecom users using ML pipelines and GridSearchCV tuning.</p>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="py-12 bg-white">
    <div class="container mx-auto px-6 max-w-5xl">
      <h3 class="text-2xl font-semibold mb-6">💼 Experience</h3>
      <ul class="space-y-4">
        <li>
          <strong>SaiKet Systems</strong> – Data Science Intern (Jan–Feb 2025)<br/>
          Built ML models for customer churn; deployed analytics pipelines using Python.
        </li>
        <li>
          <strong>Insignia Consultancy</strong> – Web Automation Intern (May–Nov 2024)<br/>
          Automated dynamic scraping using Selenium + BeautifulSoup.
        </li>
        <li>
          <strong>SMNG Academy</strong> – Power BI Intern (Feb–Mar 2024)<br/>
          Created business dashboards for Sales and Global Terrorism datasets.
        </li>
      </ul>
    </div>
  </section>

  <!-- Education -->
  <section class="py-12 bg-gray-50">
    <div class="container mx-auto px-6 max-w-5xl">
      <h3 class="text-2xl font-semibold mb-6">🎓 Education</h3>
      <ul class="space-y-3">
        <li><strong>M.Sc., Data Science & Statistics</strong> – Graphic Era Hill University (2023–2025) – 91.9%</li>
        <li><strong>B.Sc., PCM</strong> – HNB Garhwal University (2018–2021) – 78.33%</li>
      </ul>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-12 bg-blue-600 text-white text-center">
    <h3 class="text-2xl font-bold mb-2">📬 Get in Touch</h3>
    <p>juhishahi321@gmail.com | Dehradun, India | +91-9027999350</p>
    <div class="mt-4 space-x-4 text-xl">
      <a href="https://linkedin.com/in/juhi-shahi-830719220" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/juhi-shahi" target="_blank"><i class="fab fa-github"></i></a>
      <a href="mailto:juhishahi321@gmail.com"><i class="fas fa-envelope"></i></a>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center py-4 text-gray-500 text-sm">
    © 2025 Juhi Shahi. All rights reserved.
  </footer>

</body>
</html>


