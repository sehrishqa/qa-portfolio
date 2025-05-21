<script type="text/javascript">
        var gk_isXlsx = false;
        var gk_xlsxFileLookup = {};
        var gk_fileData = {};
        function filledCell(cell) {
          return cell !== '' && cell != null;
        }
        function loadFileData(filename) {
        if (gk_isXlsx && gk_xlsxFileLookup[filename]) {
            try {
                var workbook = XLSX.read(gk_fileData[filename], { type: 'base64' });
                var firstSheetName = workbook.SheetNames[0];
                var worksheet = workbook.Sheets[firstSheetName];

                // Convert sheet to JSON to filter blank rows
                var jsonData = XLSX.utils.sheet_to_json(worksheet, { header: 1, blankrows: false, defval: '' });
                // Filter out blank rows (rows where all cells are empty, null, or undefined)
                var filteredData = jsonData.filter(row => row.some(filledCell));

                // Heuristic to find the header row by ignoring rows with fewer filled cells than the next row
                var headerRowIndex = filteredData.findIndex((row, index) =>
                  row.filter(filledCell).length >= filteredData[index + 1]?.filter(filledCell).length
                );
                // Fallback
                if (headerRowIndex === -1 || headerRowIndex > 25) {
                  headerRowIndex = 0;
                }

                // Convert filtered JSON back to CSV
                var csv = XLSX.utils.aoa_to_sheet(filteredData.slice(headerRowIndex)); // Create a new sheet from filtered array of arrays
                csv = XLSX.utils.sheet_to_csv(csv, { header: 1 });
                return csv;
            } catch (e) {
                console.error(e);
                return "";
            }
        }
        return gk_fileData[filename] || "";
        }
        </script><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of a QA Engineer specializing in test automation with Cypress, Playwright, and Postman.">
  <meta name="keywords" content="QA Engineer, Test Automation, Cypress, Playwright, Postman, Software Testing">
  <title>QA Engineer Portfolio</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
  <style>
    nav { position: sticky; top: 0; z-index: 10; }
    .project-card { transition: transform 0.3s ease, box-shadow 0.3s ease; }
    .project-card:hover { transform: translateY(-5px); box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); }
    .filter-btn.active { background-color: #1e40af; color: white; }
    #back-to-top { position: fixed; bottom: 20px; right: 20px; display: none; }
    @media (max-width: 640px) {
      h1 { font-size: 1.8rem; }
      .project-card { padding: 1rem; }
      .filter-btn { font-size: 0.9rem; padding: 0.5rem; }
    }
  </style>
</head>
<body class="bg-gray-100 font-sans text-gray-800">
  <!-- Navigation -->
  <nav class="bg-blue-600 text-white p-4">
    <div class="container mx-auto flex justify-between items-center">
      <a href="#" class="text-xl font-bold">QA Engineer Portfolio</a>
      <div class="space-x-4">
        <a href="#about" class="hover:underline">About</a>
        <a href="#tools" class="hover:underline">Tools</a>
        <a href="#projects" class="hover:underline">Projects</a>
        <a href="#contact" class="hover:underline">Contact</a>
      </div>
    </div>
  </nav>

  <!-- About Section -->
  <section id="about" class="py-12 bg-white">
    <div class="container mx-auto px-4">
      <h1 class="text-4xl font-bold mb-4 text-center">QA Engineer Portfolio</h1>
      <p class="text-lg mb-4">
        I started my career in Quality Assurance (QA) in 2019 and have been passionate about delivering high-quality software ever since. Over the years, I've been determined to grow and evolve in the QA field, and today, I work as a Test Automation Engineer.
      </p>
      <p class="text-lg mb-4">
        My experience spans both manual and automated testing. I specialize in building robust and efficient test automation frameworks using tools like Cypress, Playwright, and Postman. I enjoy finding smart ways to ensure software reliability and improve testing processes to support fast-paced development environments.
      </p>
      <p class="text-lg">
        I'm committed to continuous learning and always eager to explore new technologies and best practices in automation testing.
      </p>
    </div>
  </section>

  <!-- Tools Section -->
  <section id="tools" class="py-12 bg-gray-100">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-6 text-center">Tools I Use</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Cypress</h3>
          <p>Web Apps End-to-End Automation</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Postman</h3>
          <p>API Testing and Automation Scripts</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Jira</h3>
          <p>Project Management and Bug Reporting</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">QAlity Plus</h3>
          <p>Test Case Management within Jira</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Confluence</h3>
          <p>Team Collaboration and Documentation</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Slack</h3>
          <p>Communication</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">JMeter</h3>
          <p>Load and Performance Testing</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Microsoft Dynamics 365</h3>
          <p>CRM Add-on Testing</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Laravel Dusk</h3>
          <p>Laravel Project Testing Automation</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Playwright</h3>
          <p>Automation Testing</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">BrowserStack</h3>
          <p>Cross Browser Testing</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold">Zephyr</h3>
          <p>Test Case Management</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="py-12 bg-white">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-6 text-center">Projects</h2>
      <!-- Filter Buttons -->
      <div class="mb-8 flex flex-wrap justify-center gap-4">
        <h3 class="w-full text-xl font-semibold mb-2">Filter by Industry:</h3>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="all">All</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="e-commerce">E-commerce</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="healthcare">Healthcare</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="retail">Retail</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="education">Education</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="gaming">Gaming</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="travel">Travel</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="government">Government</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-filter="media">Media</button>
      </div>
      <div class="mb-8 flex flex-wrap justify-center gap-4">
        <h3 class="w-full text-xl font-semibold mb-2">Filter by Type:</h3>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-type="all">All</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-type="web">Web</button>
        <button class="filter-btn px-4 py-2 bg-blue-200 text-blue-800 rounded hover:bg-blue-300" data-type="mobile">Mobile</button>
      </div>
      <!-- Project Cards -->
      <div id="project-list" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Sherpa Auto Transport -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="retail travel" data-type="web">
          <h3 class="text-xl font-semibold mb-2">Sherpa Auto Transport</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://sherpaautotransport.com/" target="_blank" class="text-blue-600 hover:underline">sherpaautotransport.com</a></p>
          <p class="mb-2"><strong>About:</strong> Improves the car shipping experience with transparency and reliability.</p>
          <p><strong>QA Responsibilities:</strong> End-to-End functional testing, responsiveness, cross-browser compatibility, UI/UX testing, bug reporting (Shortcut), SEO validation.</p>
        </div>
        <!-- The Gem Cloud -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="e-commerce" data-type="web">
          <h3 class="text-xl font-semibold mb-2">The Gem Cloud</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://www.thegemcloud.com/" target="_blank" class="text-blue-600 hover:underline">thegemcloud.com</a></p>
          <p class="mb-2"><strong>About:</strong> A B2B digital marketplace and inventory system for the gemstone industry.</p>
          <p><strong>QA Responsibilities:</strong> Functional and regression testing (Selenium), UI/UX testing, role-based access verification, cross-browser testing, mobile responsiveness, bug reporting (Jira), media upload and 360-degree view validation.</p>
        </div>
        <!-- ILMZone -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="education" data-type="web">
          <h3 class="text-xl font-semibold mb-2">ILMZone</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://int.ilmzone.com/" target="_blank" class="text-blue-600 hover:underline">int.ilmzone.com</a></p>
          <p class="mb-2"><strong>About:</strong> An EdTech platform offering digital learning and academic support in Pakistan.</p>
          <p><strong>QA Responsibilities:</strong> Led QA effort, automated end-to-end test cases (Cypress), test case management (QAlity Plus), sprint management (Jira), API testing (Postman), performance testing (JMeter, BlazeMeter), Git version control.</p>
        </div>
        <!-- BedrockMD -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="healthcare" data-type="web">
          <h3 class="text-xl font-semibold mb-2">BedrockMD</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://bedrockmd.com/" target="_blank" class="text-blue-600 hover:underline">bedrockmd.com</a></p>
          <p class="mb-2"><strong>About:</strong> A digital platform supporting insurance agents with leads, training, and quoting tools.</p>
          <p><strong>QA Responsibilities:</strong> End-to-End functional testing, responsive design testing, secure data flow validation, UX and bug reporting (Monday.com), test case management (Google Sheets).</p>
        </div>
        <!-- Medicare Comparison Guide -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="healthcare" data-type="web">
          <h3 class="text-xl font-semibold mb-2">Medicare Comparison Guide</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://medicare-advantage-vs-medicare-supplement.com/" target="_blank" class="text-blue-600 hover:underline">medicare-advantage-vs-medicare-supplement.com</a></p>
          <p class="mb-2"><strong>About:</strong> An educational guide comparing Medicare plans.</p>
          <p><strong>QA Responsibilities:</strong> Content validation, UX and flow testing, mobile responsiveness, cross-browser testing, lead form functionality, accessibility and SEO validation, bug tracking (Monday.com).</p>
        </div>
        <!-- BedrockFS -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="healthcare" data-type="web">
          <h3 class="text-xl font-semibold mb-2">BedrockFS</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://bedrockfs.com/" target="_blank" class="text-blue-600 hover:underline">bedrockfs.com</a></p>
          <p class="mb-2"><strong>About:</strong> Combines marketing support, CRM software, and insurance products for financial professionals.</p>
          <p><strong>QA Responsibilities:</strong> Functional and cross-device testing, marketing content validation, bug reporting (Monday.com), regression testing.</p>
        </div>
        <!-- MitraMundo -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="e-commerce" data-type="web">
          <h3 class="text-xl font-semibold mb-2">MitraMundo</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://mitramundo.com/contact-us/" target="_blank" class="text-blue-600 hover:underline">mitramundo.com</a></p>
          <p class="mb-2"><strong>About:</strong> Provides consulting services and products for the Latin American market.</p>
          <p><strong>QA Responsibilities:</strong> Functional testing, cross-browser and mobile responsiveness testing, UI/UX testing, Stripe payment integration testing, bug reporting (Jira).</p>
        </div>
        <!-- Postal-Service-Health-Benefits -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="healthcare government" data-type="web">
          <h3 class="text-xl font-semibold mb-2">Postal-Service-Health-Benefits</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://postal-service-health-benefits.com/" target="_blank" class="text-blue-600 hover:underline">postal-service-health-benefits.com</a></p>
          <p class="mb-2"><strong>About:</strong> Educates U.S. postal workers about healthcare and Medicare options.</p>
          <p><strong>QA Responsibilities:</strong> Educational content validation, mobile and cross-browser testing, accessibility compliance, lead capture form testing, SEO validation, bug tracking (Monday.com).</p>
        </div>
        <!-- Credkeeper -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="media" data-type="web">
          <h3 class="text-xl font-semibold mb-2">Credkeeper</h3>
          <p class="mb-2"><strong>Website:</strong> <a href="https://credkeeper.com/" target="_blank" class="text-blue-600 hover:underline">credkeeper.com</a></p>
          <p class="mb-2"><strong>About:</strong> Amplifies a business’s online credibility to increase client trust and lead conversions.</p>
          <p><strong>QA Responsibilities:</strong> Functional and mobile responsiveness testing, UI/UX consistency, bug tracking and test management (Monday.com, Google Sheets).</p>
        </div>
        <!-- LitMe -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="gaming" data-type="mobile">
          <h3 class="text-xl font-semibold mb-2">LitMe</h3>
          <p class="mb-2"><strong>Google Play:</strong> <a href="https://play.google.com/store/apps/details?id=com.litmeapp.litapp" target="_blank" class="text-blue-600 hover:underline">LitMe</a></p>
          <p class="mb-2"><strong>About:</strong> An app for creating, managing events, and social engagement.</p>
          <p><strong>QA Responsibilities:</strong> Led a team of 6 QA engineers, cross-device UAT on 12 Android devices, UI/UX testing, bug reporting (Jira), performance testing (Apache JMeter), API testing (Postman).</p>
        </div>
        <!-- Scalamed -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="healthcare" data-type="mobile">
          <h3 class="text-xl font-semibold mb-2">Scalamed</h3>
          <p class="mb-2"><strong>Google Play:</strong> <a href="https://play.google.com/store/apps/details?id=com.scalamed.patientmobileapp&hl=en_IE" target="_blank" class="text-blue-600 hover:underline">Scalamed</a></p>
          <p class="mb-2"><strong>Web:</strong> <a href="https://www.myhealthapplication.com/app/scalamed" target="_blank" class="text-blue-600 hover:underline">myhealthapplication.com</a></p>
          <p class="mb-2"><strong>About:</strong> A mobile solution for prescription management between patients and pharmacies.</p>
          <p><strong>QA Responsibilities:</strong> End-to-End functional testing, UI/UX testing, bug reporting (Jira), performance testing (Apache JMeter), API testing and documentation (Postman), regression testing.</p>
        </div>
        <!-- SameForYou -->
        <div class="project-card bg-blue-50 p-6 rounded-lg shadow-md" data-industries="media" data-type="mobile">
          <h3 class="text-xl font-semibold mb-2">SameForYou</h3>
          <p class="mb-2"><strong>App Store:</strong> <a href="https://apps.apple.com/us/app/same-for-you/id1643425190" target="_blank" class="text-blue-600 hover:underline">SameForYou</a></p>
          <p class="mb-2"><strong>About:</strong> Connects merchants and customers through a meal ordering and delivery platform.</p>
          <p><strong>QA Responsibilities:</strong> End-to-End functional testing, cross-device testing on iOS devices, UI/UX testing, bug reporting (Jira).</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-12 bg-gray-100">
    <div class="container mx-auto px-4 text-center">
      <h2 class="text-3xl font-bold mb-6">Get in Touch</h2>
      <p class="text-lg mb-4">Interested in collaborating or learning more about my work? Feel free to reach out!</p>
      <a href="mailto:your.email@example.com" class="inline-block px-6 py-3 bg-blue-600 text-white rounded hover:bg-blue-700">Contact Me</a>
    </div>
  </section>

  <!-- Back to Top Button -->
  <button id="back-to-top" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Back to Top</button>

  <script>
    // Filter Projects
    const filterButtons = document.querySelectorAll('.filter-btn');
    const projectCards = document.querySelectorAll('.project-card');

    filterButtons.forEach(button => {
      button.addEventListener('click', () => {
        // Handle Industry Filters
        if (button.dataset.filter) {
          filterButtons.forEach(btn => btn.classList.remove('active'));
          button.classList.add('active');
          const filter = button.dataset.filter;
          projectCards.forEach(card => {
            const industries = card.dataset.industries.split(' ');
            if (filter === 'all' || industries.includes(filter)) {
              card.style.display = 'block';
            } else {
              card.style.display = 'none';
            }
          });
        }
        // Handle Type Filters
        if (button.dataset.type) {
          filterButtons.forEach(btn => btn.classList.remove('active'));
          button.classList.add('active');
          const type = button.dataset.type;
          projectCards.forEach(card => {
            if (type === 'all' || card.dataset.type === type) {
              card.style.display = 'block';
            } else {
              card.style.display = 'none';
            }
          });
        }
      });
    });

    // Back to Top Button
    const backToTopButton = document.getElementById('back-to-top');
    window.addEventListener('scroll', () => {
      backToTopButton.style.display = window.scrollY > 300 ? 'block' : 'none';
    });
    backToTopButton.addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  </script>
</body>
</html>
