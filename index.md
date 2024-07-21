<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jorge Coppin-Massanet</title>
    <style>
      body {
        background-image: url('/assets/img/37363655772_4d8bd4a4d7_o.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-position: center;
        color: white;
        margin: 0;
        padding: 0;
      }

      .overlay {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.6);
        backdrop-filter: blur(2px);
        z-index: -1;
      }

      .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        padding: 20px;
      }

      h1 {
        font-size: 4rem;
        margin: 10px 0;
      }

      .subtitle {
        font-size: 1.5rem;
        font-weight: normal;
        white-space: nowrap;
        overflow: hidden;
        text-overflow: ellipsis;
      }

      .bio {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 20px;
      }

      .bio img {
        margin: 20px;
        border-radius: 8px;
        width: 30%;
        max-width: 200px;
      }

      .bio p {
        text-align: justify;
        max-width: 600px;
        padding: 0 20px;
      }

      a {
        color: #00ffcc;
        text-decoration: underline;
      }

      .center-buttons {
        display: flex;
        justify-content: center;
        gap: 20px;
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

      @media only screen and (max-width: 768px) {
        h1 {
          font-size: 3rem;
        }

        .subtitle {
          font-size: 1.2rem;
        }

        .bio img {
          width: 50%;
        }

        .bio p {
          padding: 0 10px;
        }

        .center-buttons {
          flex-direction: column;
          gap: 10px;
        }
      }

      @media only screen and (max-width: 480px) {
        h1 {
          font-size: 2.5rem;
        }

        .subtitle {
          font-size: 1rem;
        }

        .bio img {
          width: 70%;
        }

        .bio p {
          padding: 0 5px;
        }

        .center-buttons {
          flex-direction: column;
          gap: 5px;
        }

        .button {
          padding: 8px 15px;
        }
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
      <p> I am a first-generation Geological Sciences and Astronomy grad student in the <a href="https://schmidt.astro.cornell.edu/">Planetary Habitability and Technology Lab</a> at Cornell University's <a href="https://www.eas.cornell.edu/eas">Earth and Atmospheric Sciences Department</a>, where I work under the guidance of Dr. Britney Schmidt. My research endeavors encompass a wide spectrum of subjects such as exploring the potential for extraterrestrial life in icy moons, designing and testing new instrumentation for detecting biosignatures in extreme environments, and understanding the impacts of climate change on the biodiversity of Earth's polar regions. My work embodies a passion for understanding the limits and extent of life on Earth and the rest of our Solar System, with a particular emphasis on making accessible open-science available to underrepresented communities, advocating for climate justice, and decolonizing scientific practices. <br>
        <br> Before joining Cornell, I earned my B.S. in Mechanical Engineering from the <a href="https://www.uprm.edu/portada/">University of Puerto Rico</a>, where I developed a strong foundation in engineering principles and gained valuable research experience. <br>
        <br> If you're interested in learning more about my work and projects, please check out the links below!
      </p>
    </div>
    <div class="center-buttons">
      <a href="/publications" class="button">Publications</a>
      <a href="/projects" class="button">Projects</a>
      <a href="/cv" class="button" target="_blank" rel="noopener noreferrer">CV</a>
    </div>
  </body>
</html>
