<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Juhi Shahi | Data Scientist Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans leading-relaxed">

  <!-- Header -->
  <header class="bg-white shadow sticky top-0 z-50">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Juhi Shahi</h1>
      <nav class="space-x-4 text-sm">
        <a href="#projects" class="hover:text-blue-600">Projects</a>
        <a href="#experience" class="hover:text-blue-600">Experience</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="py-20 bg-gradient-to-r from-blue-200 to-indigo-300 text-center" data-aos="zoom-in">
    <h2 class="text-5xl font-bold mb-4 text-white">Hello, I'm Juhi 👋</h2>
    <p class="text-lg text-white max-w-2xl mx-auto">
      Data Analyst | ML Enthusiast | Automating insights with Python, SQL & Power BI.
    </p>
    <div class="mt-6 flex justify-center space-x-4 text-2xl">
      <a href="https://linkedin.com/in/juhi-shahi-830719220" target="_blank" class="text-white hover:text-gray-200"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/juhi-shahi" target="_blank" class="text-white hover:text-gray-200"><i class="fab fa-github"></i></a>
      <a href="mailto:juhishahi321@gmail.com" class="text-white hover:text-gray-200"><i class="fas fa-envelope"></i></a>
    </div>
  </section>

  <!-- Skills -->
  <section class="py-12 bg-white" data-aos="fade-up">
    <div class="container mx-auto px-6 max-w-5xl">
      <h3 class="text-2xl font-semibold mb-6">🛠 Technical Skills</h3>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
        <div class="bg-blue-100 p-4 rounded text-center hover:bg-blue-200 transition-transform duration-300 transform hover:scale-105">Python</div>
        <div class="bg-blue-100 p-4 rounded text-center hover:bg-blue-200 transition-transform duration-300 transform hover:scale-105">SQL</div>
        <div class="bg-blue-100 p-4 rounded text-center hover:bg-blue-200 transition-transform duration-300 transform hover:scale-105">Power BI</div>
        <div class="bg-blue-100 p-4 rounded text-center hover:bg-blue-200 transition-transform duration-300 transform hover:scale-105">Scikit-learn</div>
        <div class="bg-blue-100 p-4 rounded text-center hover:bg-blue-200 transition-transform duration-300 transform hover:scale-105">Streamlit</div>
        <div class="bg-blue-100 p-4 rounded text-center hover:bg-blue-200 transition-transform duration-300 transform hover:scale-105">Selenium</div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-12 bg-gray-100" data-aos="fade-up">
    <div class="container mx-auto px-6 max-w-5xl">
      <h3 class="text-2xl font-semibold mb-6">📂 Projects</h3>

      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-white p-6 rounded shadow hover:shadow-xl transition-shadow" data-aos="fade-up">
          <h4 class="text-xl font-bold mb-2">Netflix Data Analysis</h4>
          <p class="mb-2">Visualized viewer behavior and clustered profiles using Python & Seaborn.</p>
          <a href="https://github.com/juhi-shahi/Binge-Watch-Breakdown-Analyzing-Netflix-Content-Trends" class="text-blue-600 hover:underline">View on GitHub</a>
        </div>

        <div class="bg-white p-6 rounded shadow hover:shadow-xl transition-shadow" data-aos="fade-up" data-aos-delay="100">
          <h4 class="text-xl font-bold mb-2">Car Price Prediction</h4>
          <p class="mb-2">Used regression models to estimate car prices; deployed with Streamlit.</p>
          <a href="https://github.com/juhi-shahi/car-price-prediction" class="text-blue-600 hover:underline">View on GitHub</a>
        </div>

        <div class="bg-white p-6 rounded shadow hover:shadow-xl transition-shadow" data-aos="fade-up" data-aos-delay="200">
          <h4 class="text-xl font-bold mb-2">Customer Churn Prediction</h4>
          <p class="mb-2">Identified telecom churn risks with ML pipelines and cohort segmentation.</p>
        </div>

        <div class="bg-white p-6 rounded shadow hover:shadow-xl transition-shadow" data-aos="fade-up" data-aos-delay="300">
          <h4 class="text-xl font-bold mb-2">Power BI Dashboards</h4>
          <p class="mb-2">Created interactive dashboards for Sales, Global Terrorism & more.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="py-12 bg-white" data-aos="fade-up">
    <div class="container mx-auto px-6 max-w-5xl">
      <h3 class="text-2xl font-semibold mb-6">💼 Experience</h3>
      <ul class="space-y-4">
        <li><strong>SaiKet Systems</strong> – Data Science Intern (Jan–Feb 2025)<br/>Built ML models for customer churn; deployed analytics pipelines using Python.</li>
        <li><strong>Insignia Consultancy</strong> – Web Automation Intern (May–Nov 2024)<br/>Automated dynamic scraping using Selenium + BeautifulSoup.</li>
        <li><strong>SMNG Academy</strong> – Power BI Intern (Feb–Mar 2024)<br/>Created business dashboards for Sales and Global Terrorism datasets.</li>
      </ul>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-12 bg-blue-600 text-white text-center" data-aos="fade-up">
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

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>

</body>
</html>

     

  

    
          

 

   



