
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Mohammad Robaitul Islam Bhuiyan –Showcasing professional experience, projects, publications, certificates, and skills.">
  <title></title>

  <!-- Favicon -->
  <link rel="icon" href="favicon.ico">

  <!-- Open Graph / Twitter Card -->
  <meta property="og:title" content="Mohammad Robaitul Islam Bhuiyan – B.Sc. in CSE | M.Sc. in Data Science(On-going)">
  <meta property="og:description" content="Explore my portfolio: experience, projects, publications, certificates, and skills.">
  <meta property="og:image" content="https://robayet002.github.io/image/profile-pic.jpg">
  <meta property="og:url" content="https://robayet002.github.io/">
  <meta name="twitter:card" content="summary_large_image">

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap" rel="stylesheet">
  <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KyZXEAg3QhqLMpG8r+Knujsl5+5hb7U6E1f9D8Lr6+uHrQfI0dNH0zIhzVpVod1Pvj+KcO9Bx48Y8V9W1yP+kw=="
        crossorigin="anonymous"
        referrerpolicy="no-referrer" />

  <!-- Styles -->
  <style>
    :root {
      --color-bg: #f8f9fa;
      --color-primary: #0d3b66;
      --color-secondary: #faf0ca;
      --color-accent: #ee964b;
      --color-white: #ffffff;
      --color-gray-light: #e9ecef;
      --color-text: #343a40;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Roboto', sans-serif; background: var(--color-bg); color: var(--color-text); line-height: 1.6; }
    a { color: var(--color-accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .container { max-width: 960px; margin: 2rem auto; padding: 0 1rem; }

    /* Header & Nav */
    header { background: var(--color-primary); color: var(--color-white); padding: 2rem 0; border-bottom: 4px solid var(--color-accent); }
    .header-main { display: flex; align-items: center; gap: 1.5rem; }
    .profile-pic { width: 150px; height: 150px; border-radius: 50%; object-fit: cover; border: 4px solid var(--color-accent); }
    header h1 { font-size: 1.5rem; margin: 0; }
    header .subtitle { font-size: 1rem; font-weight: 300; margin-top: 0.25rem; }
    nav { margin-top: 1.5rem; text-align: center; }
    nav a { margin: 0 1rem; font-weight: 500; color: var(--color-white); transition: color 0.3s; }
    nav a:hover { color: var(--color-secondary); }

    /* Section Titles */
    section { margin-bottom: 3rem; }
    section h2 { font-size: 1.8rem; margin-bottom: 1rem; position: relative; padding-bottom: 0.5rem; }
    section h2::after { content: ''; position: absolute; bottom: 0; left: 0; width: 60px; height: 4px; background: var(--color-accent); border-radius: 2px; }

    /* Cards */
    .card { background: var(--color-white); border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 1.5rem; margin-bottom: 1.5rem; transition: transform 0.3s; }
    .card:hover { transform: translateY(-5px); }

    /* Projects Grid */
    .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px,1fr)); gap:1.5rem; }

    /* Certificates Grid */
    .cert-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; }
    .cert-card img, .cert-card i { display: block; margin: 0 auto 0.5rem; }
    .cert-card h4 { font-weight: 500; text-align: center; }

    /* Skills Visualization */
    .skills-chart { display: grid; gap:1rem; }
    .skill { display: flex; flex-direction: column; }
    .skill span { font-weight: 500; margin-bottom: 0.25rem; color: var(--color-primary); }
    .bar { background: var(--color-gray-light); border-radius: 4px; overflow: hidden; }
    .progress { height: 8px; background: var(--color-accent); }

    /* Contact Grid */
    .contact-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px,1fr)); gap:1rem; }
    .contact-item { background: var(--color-white); border-radius:8px; box-shadow:0 4px 10px rgba(0,0,0,0.1); padding:1rem; display:flex; align-items:center; transition: background 0.3s; }
    .contact-item:hover { background: var(--color-secondary); }
    .contact-item i { font-size:1.5rem; margin-right:0.75rem; color: var(--color-primary); }
    .contact-item a { color: var(--color-text); }

    /* Footer */
    footer { text-align: center; font-size: 0.9rem; color: var(--color-text); margin-top: 4rem; padding: 1rem 0; border-top: 1px solid var(--color-gray-light); }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <div class="header-main">
        <img src="image/photo3.jpg"
             alt="Profile picture of Mohammad Robaitul Islam Bhuiyan"
             class="profile-pic"
             loading="lazy">
        <div>
          <h1>Mohammad Robaitul Islam Bhuiya</h1>
          <p class="subtitle">B.Sc. in CSE (CUET)| M.Sc. in Data Science (On-going) (FAU)</p>
        </div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#publications">Publications</a>
        <a href="#certificates">Certificates</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>
  <main class="container">
    <section id="about">
      <h2>About Me</h2>
      <div class="card">
        <p>I am a graduate data science student and educator with a strong background in computer science and engineering. Currently, I am pursuing an M.Sc. in Data Science at Friedrich-Alexander-Universität Erlangen-Nürnberg, building upon my B.Sc. from Chittagong University of Engineering and Technology. My academic and professional journey has equipped me with a robust set of skills in data analysis, machine learning, and software development.</p>
      </div>
    </section>

    <section id="experience">
      <h2>Professional Experience</h2>
      <div class="card">
        <h3>Lecturer</h3>
        <p><em>Bangladesh Army International University of Science and Technology</em> &middot; Nov 2017 – Sep 2023</p>
        <ul>
          <li>Delivered undergraduate courses in Machine Learning, Data Structures, and DBMS.Developed lectures, assignments and supervised stdent project and research.</li>
        </ul>
      </div>
    </section>

    <section id="projects">
      <h2>Selected Projects</h2>
      
  <div class="projects">
    <div class="card">
      <h3>
        <a href="https://github.com/robayet002/Predictive-Analytics-for-Hotel-Booking-Patterns" target="_blank">
          Predictive Analytics for Hotel Booking Patterns
        </a>
      </h3>
      <p>Explanatory Data Analysis, cleaning, and visualization using Python.</p>
    </div>
    <div class="card">
      <h3>
        <a href="https://github.com/robayet002/made-robayet" target="_blank">
          Analyzing Patterns and Outcomes of Crimes and Arrests in Urban Areas of Los Angeles in USA
        </a>
      </h3>
      <p>Data exploration, pipeline development, preprocessing, and visualization using Python.</p>
    </div>
    <div class="card">
      <h3>
        <a href="https://github.com/robayet002/Enhancing-Sales-Strategies-with-Power-BI-A-Visual-Analytics-Approach" target="_blank">
          Enhancing Sales Strategies with Power BI: A Visual Analytics Approach
        </a>
      </h3>
      <p>Interactive dashboard creation and visual analytics using Power BI.</p>
    </div>
    <div class="card">
      <h3>
        <a href="https://github.com/robayet002/Improving-Breast-Cancer-Diagnosis-Accuracy-Using-SVM-and-GridSearch" target="_blank">
          Improving Breast Cancer Diagnosis Accuracy Using SVM and GridSearch
        </a>
      </h3>
      <p>Machine learning model tuning with SVM, feature scaling, and GridSearch in Python.</p>
    </div>
    <div class="card">
      <h3>
        <a href="https://github.com/robayet002/Credit-Risk-Prediction-using-supervised-machine-learning.git" target="_blank">
          Credit Risk Prediction using Supervised ML
        </a>
      </h3>
      <p>Logistic Regression & Random Forest classifier implementation with confusion matrix analysis in Python.</p>
    </div>
    <div class="card">
      <h3>
        <a href="https://github.com/robayet002/From-Raw-Data-to-Sales-Insights-A-Comprehensive-Python-Analysis" target="_blank">
          From Raw Data to Sales Insights: A Comprehensive Python Analysis
        </a>
      </h3>
      <p>End-to-end EDA including data cleaning and visualization using Python.</p>
    </div>
    <div class="card">
      <h3>
        <a href="https://github.com/robayet002/Excel-Based-Interactive-Dashboard-for-Annual-Sales-Report" target="_blank">
          Excel-Based Interactive Dashboard for Annual Sales Report
        </a>
      </h3>
      <p>Interactive Excel dashboard design for annual sales reporting and visualization.</p>
    </div>
  </div>
    </section>

    <section id="publications">
      <h2>Publications</h2>
      <div class="card">
        <h3>A Secured Blockchain Based Integrated Framework for National Identity and Passport</h3>
        <p><em>BAIUST Academic Journal &middot; 2021</em></p>
        <p><strong>Abstract:</strong> This system will help simplify the process of validating and issuing National Identity (NID) cards and passports along with preventing unauthorized issuance.</p>
        <p><a href="https://journal.baiust.ac.bd/wp-content/uploads/2022/08/2.pdf" target="_blank">Read paper</a></p>
      </div>
      <div class="card">
        <h3>Facilitating Hard-to-Defeat Car AI Using Flood-Fill Algorithm</h3>
        <p><em>IJCCI Springer &middot; 2020</em></p>
        <p><strong>Abstract:</strong> The most vital element in making a non-playable car AI in racing games is finding the shortest path between two locations (the start and the finish lines) by making an efficient algorithm for the car to follow it. Usually, both the lines are predetermined for each race in most of the popular games. However, there has not been any game where the player gets the option to select those.</p>
        <p><a href="https://link.springer.com/chapter/10.1007/978-981-15-3607-6_43" target="_blank">Read chapter</a></p>
      </div>
      <div class="card">
        <h3>Implementation of Private Blockchain in Smart Card Management System</h3>
        <p><em>BAIUST Academic Journal &middot; 2020</em></p>
        <p><strong>Abstract:</strong> Nowadays Blockchain technology is adopted for various services by a good number of global companies. Blockchain technology ensures integrity of ledgers, privacy of transaction and authenticity of transactions without a centralized control actor. In this paper, we are focused on using this technology in citizen identification system of Bangladesh. A Certification Authority ensures that the information which is not genuine and tempered is not added in our proposed decentralized network.</p>
        <p><a href="https://journal.baiust.ac.bd/implementation-of-private-blockchain-in-smart-card-management-system/" target="_blank">Read paper</a></p>
      </div>
    </section>
   <section id="certificates">
      <h2>Certificates</h2>
      <div class="cert-grid">
        <div class="cert-card card">
          <i class="fas fa-file-pdf fa-3x"></i>
          <div>
            <h4>Data Analyst with R</h4>
            <p><a href="image/certificate_data Analyst with R.pdf" target="_blank">View PDF Certificate</a></p>
          </div>
        </div>
        <div class="cert-card card">
          <i class="fas fa-file-pdf fa-3x"></i>
          <div>
            <h4>Data Science Certificate Program</h4>
            <p><a href="image/Ostad-Data Science 23-C5254.pdf" target="_blank">View PDF Certificate</a></p>
          </div>
        </div>
        <div class="cert-card card">
          <i class="fas fa-file-pdf fa-3x"></i>
          <div>
            <h4>Business Analysis via Power BI</h4>
            <p><a href="image/Power bi certificate.pdf" target="_blank">View PDF Certificate</a></p>
          </div>
        </div>
        <div class="cert-card card">
          <i class="fas fa-file-pdf fa-3x"></i>
          <div>
            <h4>Python for Data Science and AI</h4>
            <p><a href="image/PythonforDataScienceandAI_Badge20220822-46-34qr15.pdf" target="_blank">View PDF Certificate</a></p>
          </div>
        </div>
        <div class="cert-card card">
          <i class="fas fa-file-pdf fa-3x"></i>
          <div>
            <h4>Excel Power Tools for Data Analysis</h4>
            <p><a href="image/Excel power tools for data analysis.pdf" target="_blank">View PDF Certificate</a></p>
          </div>
        </div>
      </div>
    </section>


    <section id="skills">
      <h2>Skills</h2>
      <div class="card skills-chart">
        <div class="skill">
          <span>Python</span>
          <div class="bar"><div class="progress" style="width: 90%;"></div></div>
        </div>
        <div class="skill">
          <span>R</span>
          <div class="bar"><div class="progress" style="width: 80%;"></div></div>
        </div>
        <div class="skill">
          <span>C++</span>
          <div class="bar"><div class="progress" style="width: 75%;"></div></div>
        </div>
        <div class="skill">
          <span>Power BI</span>
          <div class="bar"><div class="progress" style="width: 85%;"></div></div>
        </div>
        <div class="skill">
          <span>MS SQL & MS Access</span>
          <div class="bar"><div class="progress" style="width: 70%;"></div></div>
        </div>
        <div class="skill">
          <span>LaTeX & Office 365</span>
          <div class="bar"><div class="progress" style="width: 80%;"></div></div>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="contact-grid">
        <div class="contact-item">
          <i class="fas fa-map-marker-alt"></i>
          <div>
            <h4>Location</h4>
            <p>91054 Erlangen, Germany</p>
          </div>
        </div>
        <div class="contact-item">
          <i class="fas fa-envelope"></i>
          <div>
            <h4>Email</h4>
            <p><a href="mailto:robayetcuet11@gmail.com">robayetcuet11@gmail.com</a></p>
          </div>
        </div>
        <div class="contact-item">
          <i class="fas fa-phone-alt"></i>
          <div>
            <h4>Phone</h4>
            <p><a href="tel:+4917674126760">+49 176 7412 6760</a></p>
          </div>
        </div>
        <div class="contact-item">
          <i class="fab fa-github"></i>
          <div>
            <h4>GitHub</h4>
            <p><a href="https://github.com/robayet002" target="_blank">robayet002</a></p>
          </div>
        </div>
        <div class="contact-item">
          <i class="fab fa-linkedin"></i>
          <div>
            <h4>LinkedIn</h4>
            <p><a href="https://linkedin.com/in/robayet" target="_blank">/robayet</a></p>
          </div>
        </div>
      </div>
    </section>

    <footer>&copy; 2025 Mohammad Robaitul Islam Bhuiyan</footer>
  </div>
</body>
</html>
