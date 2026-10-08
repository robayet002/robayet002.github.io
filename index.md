<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Mohammad Robaitul Islam Bhuiyan – graduate researcher in medical image analysis and multimodal clinical AI. Research, publications, teaching, projects and skills.">
  <title>Mohammad Robaitul Islam Bhuiyan – Medical Image Analysis &amp; Clinical AI</title>

  <!-- Favicon -->
  <link rel="icon" href="favicon.ico">

  <!-- Open Graph / Twitter Card -->
  <meta property="og:title" content="Mohammad Robaitul Islam Bhuiyan – M.Sc. Data Science (FAU) | Medical Image Analysis &amp; Clinical AI">
  <meta property="og:description" content="Graduate researcher in medical image analysis and multimodal clinical AI. Explore my research, publications, teaching, projects and skills.">
  <meta property="og:image" content="https://robayet002.github.io/image/profile-pic.jpg">
  <meta property="og:url" content="https://robayet002.github.io/">
  <meta name="twitter:card" content="summary_large_image">

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap" rel="stylesheet">
  <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
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
      --color-muted: #6c757d;
      --color-text: #343a40;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Roboto', sans-serif; background: var(--color-bg); color: var(--color-text); line-height: 1.6; }
    a { color: var(--color-accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .container { max-width: 960px; margin: 2rem auto; padding: 0 1rem; }
    ul { padding-left: 1.25rem; }
    li { margin-bottom: 0.35rem; }

    /* Header & Nav */
    header { background: var(--color-primary); color: var(--color-white); padding: 2rem 0; border-bottom: 4px solid var(--color-accent); }
    header .container { margin: 0 auto; }
    .header-main { display: flex; align-items: center; gap: 1.5rem; flex-wrap: wrap; }
    .profile-pic { width: 150px; height: 150px; border-radius: 50%; object-fit: cover; border: 4px solid var(--color-accent); }
    header h1 { font-size: 1.5rem; margin: 0; }
    header .subtitle { font-size: 1rem; font-weight: 300; margin-top: 0.25rem; }
    header .tagline { font-size: 0.95rem; margin-top: 0.5rem; color: var(--color-secondary); }
    nav { margin-top: 1.5rem; text-align: center; }
    nav a { display: inline-block; margin: 0.25rem 0.75rem; font-weight: 500; color: var(--color-white); transition: color 0.3s; }
    nav a:hover { color: var(--color-secondary); }

    /* Section Titles */
    section { margin-bottom: 3rem; }
    section h2 { font-size: 1.8rem; margin-bottom: 1rem; position: relative; padding-bottom: 0.5rem; }
    section h2::after { content: ''; position: absolute; bottom: 0; left: 0; width: 60px; height: 4px; background: var(--color-accent); border-radius: 2px; }

    /* Cards */
    .card { background: var(--color-white); border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 1.5rem; margin-bottom: 1.5rem; transition: transform 0.3s; }
    .card:hover { transform: translateY(-5px); }
    .card h3 { margin-bottom: 0.25rem; }
    .meta { display: flex; justify-content: space-between; flex-wrap: wrap; gap: 0.5rem; color: var(--color-muted); font-size: 0.95rem; margin-bottom: 0.75rem; }
    .badge { display: inline-block; background: var(--color-secondary); color: var(--color-primary); font-size: 0.8rem; font-weight: 500; padding: 0.1rem 0.6rem; border-radius: 999px; margin-left: 0.5rem; vertical-align: middle; }
    .tech { color: var(--color-muted); font-size: 0.9rem; margin-top: 0.5rem; }

    /* Projects Grid */
    .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px,1fr)); gap:1.5rem; }

    /* Certificates Grid */
    .cert-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; }
    .cert-card img, .cert-card i { display: block; margin: 0 auto 0.5rem; color: var(--color-primary); }
    .cert-card h4 { font-weight: 500; text-align: center; }
    .cert-card p { text-align: center; }

    /* Skills */
    .skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.5rem; }
    .skill-group h4 { color: var(--color-primary); margin-bottom: 0.5rem; }
    .tags { display: flex; flex-wrap: wrap; gap: 0.5rem; }
    .tag { background: var(--color-gray-light); border-left: 3px solid var(--color-accent); padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.9rem; }

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
             class="profile-pic">
        <div>
          <h1>Mohammad Robaitul Islam Bhuiyan</h1>
          <p class="subtitle">M.Sc. in Data Science (FAU) &nbsp;||&nbsp; B.Sc. in CSE (CUET)</p>
          <p class="tagline">Medical Image Analysis &middot; Multimodal Clinical AI &middot; Foundation Models for Healthcare</p>
        </div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#research">Research</a>
        <a href="#publications">Publications</a>
        <a href="#teaching">Teaching</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#certificates">Certificates</a>
        <a href="#more">Awards &amp; Service</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="about">
      <h2>About Me</h2>
      <div class="card">
        <p>I am a graduate researcher in medical image analysis and multimodal clinical AI. I completed my M.Sc. in Data Science at Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU), where I carried out my Master's thesis at the Pattern Recognition Lab on speech-driven brain-tumor segmentation with medical foundation models. Before that, I earned my B.Sc. in Computer Science and Engineering from Chittagong University of Engineering and Technology (CUET) and have experience of working as Teaching assistant at FAU and  as a lecturer in Bangladesh.</p>
        <p style="margin-top:0.75rem;">I am seeking a Ph.D. position on adapting and evaluating foundation models for healthcare, with a focus on vision-language models, large language models, and clinical AI agents.</p>
      </div>
    </section>

    <section id="education">
      <h2>Education</h2>
      <div class="card">
        <h3>M.Sc. in Data Science</h3>
        <div class="meta">
          <span>Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU)</span>
          <span>Erlangen, Germany</span>
        </div>
        <p>Grade: <strong>1.8</strong> (German scale)</p>
      </div>
      <div class="card">
        <h3>B.Sc. in Computer Science and Engineering</h3>
        <div class="meta">
          <span>Chittagong University of Engineering and Technology (CUET)</span>
          <span>Chittagong, Bangladesh</span>
        </div>
        <p>CGPA: <strong>3.52 / 4.00</strong> (equivalent to 1.7 on the German scale)</p>
      </div>
    </section>

    <section id="research">
      <h2>Research Experience</h2>
      <div class="card">
        <h3>Master's Thesis – Pattern Recognition Lab, FAU</h3>
        <div class="meta">
          <span>Erlangen, Germany</span>
          <span>Nov 2025 – Apr 2026</span>
        </div>
        <ul>
          <li>Developed <strong>LoGSAM</strong>, a speech-to-segmentation framework for brain-tumor segmentation in MRI, grounding spoken and text prompts in medical foundation models.</li>
          <li>Designed low-rank adaptation (LoRA) strategies for parameter-efficient fine-tuning of large-scale segmentation foundation models.</li>
        </ul>
      </div>
    </section>

    <section id="publications">
      <h2>Publications</h2>
      <div class="card">
        <h3>LoGSAM: Parameter-Efficient Cross-Modal Grounding for MRI Segmentation <span class="badge">New</span></h3>
        <p><strong>M. R. I. Bhuiyan</strong>, S. Bhat et al.</p>
        <p><em>Medical Image Computing and Computer Assisted Intervention – MICCAI 2026 Workshops and Challenges, LNCS vol. 17261, Springer Nature Switzerland &middot; 2026</em></p>
        <p><strong>Summary:</strong> An efficient framework that converts radiologist dictation into tumor class cues and uses them to drive detection-to-segmentation of brain tumors in MRI with medical foundation models, using LoRA-based parameter-efficient fine-tuning.</p>
        <p><a href="https://papers.miccai.org/miccai-2026-sat/MI4MedFM_024.html" target="_blank" rel="noopener">Read paper</a></p>
      </div>
      <div class="card">
        <h3>A Secured Blockchain Based Integrated Framework for National Identity and Passport</h3>
        <p><strong>M. R. I. Bhuiyan</strong> et al.</p>
        <p><em>BAIUST Academic Journal, vol. 2, no. 1, pp. 19–32 &middot; 2021</em></p>
        <p><strong>Abstract:</strong> This system will help simplify the process of validating and issuing National Identity (NID) cards and passports along with preventing unauthorized issuance.</p>
        <p><a href="https://journal.baiust.ac.bd/wp-content/uploads/2022/08/2.pdf" target="_blank" rel="noopener">Read paper</a></p>
      </div>
      <div class="card">
        <h3>Facilitating Hard-to-Defeat Car AI Using Flood-Fill Algorithm</h3>
        <p>M. Sabir Hossain, <strong>M. R. I. Bhuiyan</strong> et al.</p>
        <p><em>Proc. Int. Joint Conf. on Computational Intelligence (IJCCI), Algorithms for Intelligent Systems, Springer, pp. 541–553 &middot; 2020</em></p>
        <p><strong>Abstract:</strong> The most vital element in making a non-playable car AI in racing games is finding the shortest path between two locations (the start and the finish lines) by making an efficient algorithm for the car to follow it. Usually, both the lines are predetermined for each race in most of the popular games. However, there has not been any game where the player gets the option to select those.</p>
        <p><a href="https://doi.org/10.1007/978-981-15-3607-6_43" target="_blank" rel="noopener">Read chapter</a></p>
      </div>
      <div class="card">
        <h3>Implementation of Private Blockchain in Smart Card Management System</h3>
        <p>M. Saha Reno, <strong>M. R. I. Bhuiyan</strong> et al.</p>
        <p><em>BAIUST Academic Journal, vol. 1, no. 1, pp. 12–20 &middot; Dec. 2020</em></p>
        <p><strong>Abstract:</strong> Nowadays Blockchain technology is adopted for various services by a good number of global companies. Blockchain technology ensures integrity of ledgers, privacy of transaction and authenticity of transactions without a centralized control actor. In this paper, we are focused on using this technology in citizen identification system of Bangladesh. A Certification Authority ensures that the information which is not genuine and tempered is not added in our proposed decentralized network.</p>
        <p><a href="https://journal.baiust.ac.bd/implementation-of-private-blockchain-in-smart-card-management-system/" target="_blank" rel="noopener">Read paper</a></p>
      </div>
    </section>

    <section id="teaching">
      <h2>Teaching Experience</h2>
      <div class="card">
        <h3>Student Assistant, Pattern Analysis</h3>
        <div class="meta">
          <span>Friedrich-Alexander-Universität Erlangen-Nürnberg · Erlangen, Germany</span>
          <span>Apr 2026 – Jul 2026</span>
        </div>
        <ul>
          <li>Prepared and delivered exercise materials for the graduate course <em>Pattern Analysis</em>; supported students in tutorials.</li>
        </ul>
      </div>
      <div class="card">
        <h3>Lecturer, Dept. of Computer Science and Engineering</h3>
        <div class="meta">
          <span>Bangladesh Army International University of Science and Technology · Cumilla, Bangladesh</span>
          <span>Nov 2021 – Sep 2023</span>
        </div>
        <ul>
          <li>Designed and taught undergraduate courses in machine learning, data structures, and database systems, including lectures, assignments, labs, and examinations.</li>
          <li>Supervised undergraduate capstone and thesis projects.</li>
        </ul>
      </div>
    </section>

    <section id="projects">
      <h2>Selected Projects</h2>
      <div class="projects">
        <div class="card">
          <h3> <a href="https://github.com/robayet002/LoGSAM" target="_blank" rel="noopener">LoGSAM implementation</a></h3>
          <p>Official implementation of LoGSAM, an efficient framework that converts radiologist dictation into tumor class cues and uses them to drive detection-to-segmentation with foundation models.</p>
          <p class="tech">PyTorch · mmdetection · MONAI</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/Seeding-QDArchive" target="_blank" rel="noopener">
            Seeding QDArchive
            </a>
            </h3>
          <p>A research tool that discovers, downloads, and catalogues Qualitative Data Analysis (QDA) project files from target repositories.</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/Credit-Risk-Prediction-using-supervised-machine-learning" target="_blank" rel="noopener">
              Credit Risk Prediction Using Supervised ML
            </a>
          </h3>
          <p>Trained and compared logistic regression and random forest models for loan-default prediction, evaluating performance with confusion matrix analysis on imbalanced classes.</p>
          <p class="tech">Python · BeautifulSoup · openpyxl · Matplotlib</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/made-robayet" target="_blank" rel="noopener">
              Analyzing Patterns and Outcomes of Crimes and Arrests in Urban Los Angeles
            </a>
          </h3>
          <p>Data exploration, pipeline development, preprocessing, and visualization of crime and arrest data.</p>
          <p class="tech">Python · Pandas</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/Predictive-Analytics-for-Hotel-Booking-Patterns" target="_blank" rel="noopener">
              Predictive Analytics for Hotel Booking Patterns
            </a>
          </h3>
          <p>Data cleaning, exploratory analysis, and visualization of hotel booking data to identify cancellation and seasonality patterns.</p>
          <p class="tech">Python · Pandas</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/Improving-Breast-Cancer-Diagnosis-Accuracy-Using-SVM-and-GridSearch" target="_blank" rel="noopener">
              Improving Breast Cancer Diagnosis Accuracy Using SVM and GridSearch
            </a>
          </h3>
          <p>Machine learning model tuning with SVM, feature scaling, and GridSearch.</p>
          <p class="tech">Python · scikit-learn</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/Enhancing-Sales-Strategies-with-Power-BI-A-Visual-Analytics-Approach" target="_blank" rel="noopener">
              Enhancing Sales Strategies with Power BI
            </a>
          </h3>
          <p>Interactive dashboard creation and visual analytics.</p>
          <p class="tech">Power BI</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/From-Raw-Data-to-Sales-Insights-A-Comprehensive-Python-Analysis" target="_blank" rel="noopener">
              From Raw Data to Sales Insights
            </a>
          </h3>
          <p>End-to-end EDA including data cleaning and visualization.</p>
          <p class="tech">Python</p>
        </div>
        <div class="card">
          <h3>
            <a href="https://github.com/robayet002/Excel-Based-Interactive-Dashboard-for-Annual-Sales-Report" target="_blank" rel="noopener">
              Excel-Based Interactive Dashboard for Annual Sales Report
            </a>
          </h3>
          <p>Interactive Excel dashboard design for annual sales reporting and visualization.</p>
          <p class="tech">Excel</p>
        </div>
      </div>
    </section>

    <section id="skills">
      <h2>Technical Skills</h2>
      <div class="card skills-grid">
        <div class="skill-group">
          <h4><i class="fas fa-brain"></i> Deep Learning</h4>
          <div class="tags">
            <span class="tag">PyTorch</span>
            <span class="tag">Hugging Face Transformers</span>
            <span class="tag">MONAI</span>
            <span class="tag">OpenMMLab</span>
          </div>
        </div>
        <div class="skill-group">
          <h4><i class="fas fa-code"></i> Programming</h4>
          <div class="tags">
            <span class="tag">Python</span>
            <span class="tag">R</span>
            <span class="tag">C++</span>
          </div>
        </div>
        <div class="skill-group">
          <h4><i class="fas fa-database"></i> Data</h4>
          <div class="tags">
            <span class="tag">Pandas</span>
            <span class="tag">NumPy</span>
            <span class="tag">MySQL</span>
            <span class="tag">PostgreSQL</span>
          </div>
        </div>
        <div class="skill-group">
          <h4><i class="fas fa-tools"></i> Tools</h4>
          <div class="tags">
            <span class="tag">Git</span>
            <span class="tag">Linux</span>
            <span class="tag">LaTeX</span>
            <span class="tag">Power BI</span>
          </div>
        </div>
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

    <section id="more">
      <h2>Awards, Service &amp; Languages</h2>
      <div class="card">
        <h3><i class="fas fa-award"></i> Awards &amp; Fellowships</h3>
        <ul>
          <li>Science and Technology Fellowship, Government of Bangladesh (2023–2025)</li>
        </ul>
      </div>
      <div class="card">
        <h3><i class="fas fa-users"></i> Service &amp; Leadership</h3>
        <ul>
          <li>Co-advisor, BAIUST Computer Club (2020–2022)</li>
          <li>Vice President, CUET Computer Club (2016–2017)</li>
        </ul>
      </div>
      <div class="card">
        <h3><i class="fas fa-language"></i> Languages</h3>
        <ul>
          <li>English — C1 (IELTS 7.0)</li>
        </ul>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="contact-grid">
        <div class="contact-item">
          <i class="fas fa-map-marker-alt"></i>
          <div>
            <h4>Location</h4>
            <p>Erlangen, Germany</p>
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
            <p><a href="https://github.com/robayet002" target="_blank" rel="noopener">robayet002</a></p>
          </div>
        </div>
        <div class="contact-item">
          <i class="fab fa-linkedin"></i>
          <div>
            <h4>LinkedIn</h4>
            <p><a href="https://linkedin.com/in/robayet" target="_blank" rel="noopener">/robayet</a></p>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>&copy; 2026 Mohammad Robaitul Islam Bhuiyan</footer>
</body>
</html>
