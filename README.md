<!DOCTYPE html>
<html>
<head>
<title>My Portfolio</title>

<style>
html{
  scroll-behavior:smooth;
}

body{
  font-family:Arial,sans-serif;
  margin:0;
  padding:0;
  background-color:#f9f9f9;
  color:#333;
}

main{
  max-width:900px;
  margin:auto;
}

header{
  background-color:grey;
  color:white;
  text-align:center;
  padding:20px;
}

.nav-btn{
  display:inline-block;
  margin:5px;
  padding:8px 12px;
  border-radius:4px;
  background-color:white;
  color:grey;
  text-decoration:none;
  font-weight:bold;
}

.nav-btn:hover{
  background-color:#555;
  color:white;
}

section{
  padding:20px;
  border-radius:8px;
  margin:20px;
  transition:0.3s;
}

section:hover{
  transform:scale(1.01);
}

#about{
  background-color:#e0e0e0;
}

#skills{
  background-color:#f4f4f4;
}

#skills h1{
  color:grey;
}

#projects{
  background-color:white;
  border:1px solid #ccc;
}

#contact{
  background-color:#f1f1f1;
}

#contact form{
  display:flex;
  flex-direction:column;
  gap:10px;
}

#contact label{
  font-weight:bold;
}

#contact input,
#contact textarea{
  padding:6px;
  border:1px solid #ccc;
  border-radius:4px;
}

#contact button{
  background-color:grey;
  color:white;
  cursor:pointer;
  padding:8px;
  border:none;
  border-radius:4px;
}

#contact button:hover{
  background-color:#444;
}

footer{
  background-color:grey;
  color:white;
  text-align:center;
  padding:10px;
}
</style>
</head>

<body>

<header>
  <h1>Welcome To My Portfolio</h1>

  <a href="#about" class="nav-btn">About</a>
  <a href="#skills" class="nav-btn">Skills</a>
  <a href="#projects" class="nav-btn">Projects</a>
  <a href="#contact" class="nav-btn">Contact</a>
</header>

<main>

<section id="about">
  <h1>B. Roji Neha</h1>
  <p>I am currently pursuing my B.Tech in Anil Neerukonda Institute Of Technology And Sciences at Tagarapuvalasa.</p>
  <p>I am studying 3rd year from the branch CSE(AI&ML).</p>
  <p>I am very interested in learning how to create websites using HTML and CSS.</p>
</section>

<section id="skills">
  <h1>My Skills</h1>
  <ol>
    <li>Python Basics</li>
    <li>HTML Basics</li>
    <li>C Programming</li>
    <li>Data Structures</li>
  </ol>
</section>

<section id="projects">
  <h1>Projects</h1>
  <p>Coming soon...</p>
</section>

<section id="contact">
  <h1>Contact Me</h1>
  <h3>Details About Me</h3>

  <form>
    <label>Name:</label>
    <input type="text" required>

    <label>Email:</label>
    <input type="email" required>

    <label>Gender:</label>
    <div>
      <input type="radio" name="gender" id="male">
      <label for="male">Male</label>

      <input type="radio" name="gender" id="female">
      <label for="female">Female</label>
    </div>

    <label>Interests:</label>
    <div>
      <input type="checkbox" id="coding">
      <label for="coding">Coding</label>

      <input type="checkbox" id="dancing">
      <label for="dancing">Dancing</label>

      <input type="checkbox" id="reading">
      <label for="reading">Reading</label>
    </div>

    <label>Bio:</label>
    <textarea maxlength="200"></textarea>

    <button type="submit">Submit</button>
  </form>
</section>

</main>

<footer>
  <p>&copy; 2026 My Portfolio</p>
</footer>

</body>
</html>
