<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Internship in QM</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fefefe;
      color: #333;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #ffafbd, #ffc3a0);
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header img {
      height: 50px;
      width: auto;
    }

    header h1 {
      font-size: 2.5em;
      margin: 0;
    }

    nav {
      background-color: #ffc3a0;
      padding: 10px 0;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    nav a {
      color: #333;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff6f91;
    }

    section {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }

    h1 {
      color: #ff6f91;
      font-size: 2em;
    }

    p, ul {
      margin-bottom: 20px;
    }

    ul {
      list-style-type: circle;
      margin-left: 20px;
    }

    img {
      max-width: 100%;
      height: auto;
      margin: 10px 0;
    }

    .image-row {
      display: flex;
      gap: 10px;
      justify-content: center;
    }

    footer {
      background-color: #ffafbd;
      color: white;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }

    footer a {
      color: white;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.ibb.co/kJ99gXz/qm-car-logo-0-0-1.png" alt="QM Logo">
    <h1>My Internship in QM</h1>
  </header>

  <nav>
    <a href="#W1">&#128150; First Week</a>
    <a href="#W2">&#128187; Online Collection Text Analysis</a>
    <a href="#W3">&#128203; Text Mining Journey</a>
    <a href="#W4">&#128253; A Wider Lens, A New Gérôme</a>
    <a href="#W5">&#128250; Ed Rodley Presentation</a>
    <a href="#W6">&#128694; Visitors Analysis</a>
    <a href="#W7">&#128188; ICOM</a>
    <a href="#W8">&#128376; Web Scraping</a>
  </nav>

  <section id="W1">
    <h1>&#128150; First Week</h1>
    <p>The first week at Qatar Museums was an enriching and immersive experience, marked by:</p>
    <b>Exploration of Qatar’s Cultural Heritage:</b>
    <ul>
      <li>A guided tour of the National Museum of Qatar, revealing fascinating insights into the country’s history and culture.</li>
      <li>Observing visitor interactions with multimedia displays to understand engagement and reactions.</li>
    </ul>
    <b>Visitor Engagement with the Multimedia:</b>
    <ul>
      <li>Conducting surveys to gather opinions on multimedia used in exhibits.</li>
      <li>Addressing challenges like survey fatigue by using conversational techniques to engage visitors effectively.</li>
    </ul>
    <b>Data Analysis and Visualization:</b>
    <ul>
      <li>Analyzing survey quantitative data from NMoQ and TOCW using Excel.</li>
      <li>Focusing on multimedia-related questions to derive actionable insights.</li>
    </ul>
    <b>Website Development:</b>
    <ul>
      <li>Creating a website using GitHub Pages, overcoming technical challenges with support from YouTube tutorials, AI tools, and a helpful colleague.</li>
    </ul>
  </section>

  <section id="W2">
    <h1>&#128187; Online Collection's Text Analysis</h1>
    <p>During my second week at my Qatar Museums internship, I was assigned the task of counting and identifying unique words in an Excel sheet containing all the text from the museum's online collection website.</p>
    <div class="image-row">
      <img src="https://i.ibb.co/M9Wx8JS/Screenshot-2024-11-12-085434.png" alt="Text Analysis Screenshot">
      <img src="https://i.ibb.co/7N5KMJN/Screenshot-2024-11-12-093819.png" alt="Text Analysis Screenshot">
    </div>
    <p>I used Visual Studio to tokenize each word, remove capitalization, filter out numbers, and remove duplicates. My findings revealed that 90% of the words were recurrent, which suggests that using techniques like Named Entity Recognition (NER) could help the translation team focus on unique or context-specific terms.</p>
  </section>

  <section id="W3">
    <h1>&#128203; Text Mining Journey</h1>
    <p>This week, I explored text mining using "Text Mining with R: A Tidy Approach." Text mining is crucial for our digital transformation team as it helps make sense of unstructured text data. By learning these skills, I can significantly enhance our ability to analyze visitor feedback and improve the overall experience.</p>
    <b>Challenges:</b>
    <ul>
      <li>Slow laptop performance when running R Studio functions.</li>
      <li>Inability to install R Studio on a desktop at work.</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2024 Qatar Museums Internship Report. All Rights Reserved.</p>
  </footer>
</body>
</html>
