<head>
<style>
body {
  background-image: url('/assets/img/37363655772_4d8bd4a4d7_o.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  color: white; /* Ensures text is readable */
  margin: 0;
  padding: 0;
}

.overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.6); /* Darker overlay for better readability */
  backdrop-filter: blur(2px); /* Less intense blur effect */
  z-index: -1; /* Make sure it is behind all content */
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 20px;
}

h1 {
  font-size: 3rem; /* Make the title bigger */
}

.subtitle {
  font-size: 1.5rem;
  font-weight: normal; /* Unbolden the subtitle */
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

@media only screen and (max-width: 580px) {
  .subtitle {
    font-size: 1rem; /* Adjust font size for mobile */
  }
}

.bio {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.bio img {
  margin: 20px;
  border-radius: 8px;
  width: 30%; /* Ensure responsive sizing */
}

.bio p {
  text-align: justify;
  max-width: 600px;
}

a {
  color: #00ffcc; /* Stand out color for hyperlinks */
  text-decoration: underline; /* Underline for clear identification */
}

.center-buttons {
  display: flex;
  justify-content: center;
  gap: 20px; /* Space between buttons */
  margin-top: 20px;
}

.button {
  text-decoration: none;
  padding: 10px 20px;
  border: 2px solid white;
  color: white;
  background: transparent;
  transition: background 0.3s, color 0.3s;
}

.button:hover {
  background: white;
  color: black;
}
</style>
</head>

<body>
<div class="overlay"></div>

<div class="container">
  <h1>Exploring Oceans Across The Solar System</h1>
  <h2 class="subtitle">Ph.D. Student | Engineer | Astrobiologist</h2>
</div>

<div class="bio">
  <img src="/assets/img/JorgeCoppin3.jpg" alt="Jorge Coppin-Massanet">
  <p>
    I am a first-generation Geological Sciences and Astronomy grad student in the <a href="https://schmidt.astro.cornell.edu/">Planetary Habitability and Technology Lab</a> at Cornell University's <a href="https://www.eas.cornell.edu/eas">Earth and Atmospheric Sciences Department</a>, where I work under the guidance of Dr. Britney Schmidt. My research endeavors encompass a wide spectrum of subjects such as exploring the potential for extraterrestrial life in icy moons, designing and testing new instrumentation for detecting biosignatures in extreme environments, and understanding the impacts of climate change on the biodiversity of Earth's polar regions. My work embodies a passion for understanding the limits and extent of life on Earth and the rest of our Solar System, with a particular emphasis on making accessible open-science available to underrepresented communities, advocating for climate justice, and decolonizing scientific practices.
    <br><br>
    Before joining Cornell, I earned my B.S. in Mechanical Engineering from the <a href="https://www.uprm.edu/portada/">University of Puerto Rico</a>, where I developed a strong foundation in engineering principles and gained valuable research experience.
    <br><br>
    If you're interested in learning more about my work and projects, please check out the links below!
  </p>
</div>

<div class="center-buttons">
  <a href="/publications" class="button">Publications</a>
  <a href="/projects" class="button">Projects</a>
  <a href="/cv" class="button" target="_blank" rel="noopener noreferrer">CV</a>
</div>
</body>

<div class="center-buttons">
  <a href="/publications" class="button">Publications</a>
  <a href="/projects" class="button">Projects</a>
  <a href="/cv" class="button" target="_blank" rel="noopener noreferrer">CV</a>
</div>
</body>
