<template>
  <div class="container">
    <header>
      <div class="header-content">
        <img src="./assets/ProfileQodri.jpg" alt="Muhammad Qodri" class="profile-picture">
        <h1>Muhammad Qodri</h1>
        <p>Mahasiswa</p>
        <ul class="contact-info">
          <li><i class="fas fa-phone"></i> +62822-9912-3873</li>
          <li><i class="fas fa-envelope"></i> Xyrannnz@gmail.com</li>
          <li><i class="fas fa-map-marker-alt"></i> gang.miduk I, no 17 blok b bukit raya, pekanbaru</li>
        </ul>
      </div>
    </header>
    <section class="about-me">
      <h2>About Me</h2>
      <p>I am Muhammad Qodri, a passionate and driven individual with a strong interest in web design, programming, and marketing. I am a quick learner and have a strong work ethic.</p>
    </section>
    <section class="skills">
      <h2>Skills</h2>
      <ul>
        <li>Web Design</li>
        <li>Branding</li>
        <li>Graphic Design</li>
        <li>Marketing</li>
        <li>Using Software (e.g., Adobe Photoshop, Figma)</li>
      </ul>
    </section>
    <section class="experience">
      <h2>Experience</h2>
      <ul>
        <li>
          <h3>2020-2023</h3>
          <p>Organized a successful event with 100 participants.</p>
        </li>
        <li>
          <h3>2020-2023</h3>
          <p>Managed a team of 5 members to achieve a specific project goal.</p>
        </li>
      </ul>
    </section>
    <section class="language">
      <h2>Language</h2>
      <ul>
        <li>English (Bisa basic-basic nya)</li>
        <li>Indonesia (Bisa)</li>
      </ul>
    </section>
    <section class="portfolio">
      <h2>Portfolio</h2>
      <ul>
        <li>
          <img src="./assets/GambarHTML.jpg" alt="Project 1">
          <h3>Project 1</h3>
          <p>Website design using HTML, CSS, and JavaScript.</p>
        </li>
        <li>
          <img src="./assets/Adobe.jpg" alt="Project 2">
          <h3>Project 2</h3>
          <p>Graphic design project using Adobe Photoshop.</p>
        </li>
      </ul>
    </section>
  </div>
</template>

<style>
  /* Add your CSS styles here */
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }

  .header-content {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .profile-picture {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 20px;
  }

  .contact-info {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .contact-info li {
    margin-bottom: 10px;
  }

  .contact-info i {
    margin-right: 10px;
  }

  .about-me,.skills,.experience,.language,.portfolio {
    background-color: #f7f7f7;
    padding: 20px;
    margin-bottom: 20px;
  }

  .about-me h2,.skills h2,.experience h2,.language h2,.portfolio h2 {
    margin-top: 0;
  }

  .skills ul,.experience ul,.language ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .skills li,.experience li,.language li {
    margin-bottom: 20px;
  }

  .portfolio ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  .portfolio li {
    margin: 20px;
  }

  .portfolio img {
    width: 200px;
    height: 200px;
    border-radius: 10px;
    margin-bottom: 10px;
  }

  /* Add custom styles for the design */
  .header-content {
background-color: #333;
    color: #fff;
    padding: 20px;
    border-radius: 10px;
  }

 .profile-picture {
    border: 5px solid #fff;
  }

 .contact-info li {
    font-size: 18px;
    font-weight: bold;
  }

 .about-me,.skills,.experience,.language,.portfolio {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

 .portfolio ul {
    justify-content: space-between;
  }

 .portfolio li {
    width: 30%;
  }

 .portfolio img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 10px;
  }
</style>