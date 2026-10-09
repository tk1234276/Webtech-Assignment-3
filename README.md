<!DOCTYPE html>
<html 
 lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taonga Kataya | Student Portfolio</title> 
    <link rel="stylesheet" href="css/styles.css">
    <script src="js/script.js" defer></script>   
</head>    
<body margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f4f7fb;
    color: #263238;
    line-height: 1.6;>

<container  width: 90%;
    max-width: 1100px;
    margin: 0 auto;> 
    
    <header>
        <section id="home" class="hero">
        <div>
            <p class="eyebrow">ICT251 | Web Technologies</p>

            <h1>Taonga Kataya</h1>

            <p class="hero-text">
                Welcome to my student portfolio. I am a Computer Science student studying Web Technologies,
                trying to develope my skills in HTML, CSS and JavaScript.
            </p>

            <a href="#projects" class="btn">View My Projects</a>
        </div>
    </section>

    </header background: linear-gradient(135deg, #12355b, #1d70a2);
    color: white;
    text-align: center;
    padding: 3rem 1rem;> 
    <nav>
        <div class="container">
            <a href="#home">Home</a>
            <a href="#about">About Me</a>
            <a href="#hobbies">My Hobbies</a>
            <a href="#learning">Learning Plan</a>
            <a href="#projects">Projects</a>
            <a href="#photos">My Photos</a>
            <a href="#media">My Media</a>
            <a href="#contact">Contact</a>

            <a href="https://developer.mozilla.org/en-US/docs/Learn_web_development"
               target="_blank"
               rel="noopener noreferrer">
                Learn Web Development
            </a>
        </div>
        <button type="button" id="themeToggle">Dark Mode</button>
    </nav>
    <main class="container">

        <section id="about" class="content-section">
            <h2>About Me</h2>

            <p>
                My name is Taonga Kataya and my student ID is 202204909.
                I am a student studying web technologies and I am interested
                in learning how websites are designed and developed. This
                course is helping me understand HTML, CSS and other important
                web development concepts. I enjoy learning practical skills
                by creating projects and testing my code in a web browser.
                My goal is to become more confident in creating attractive,
                responsive and useful websites.
            </p>
        </section>

        <section id="hobbies" class="content-section">
            <h2>My Hobbies</h2>

            <p>My top three hobbies are:</p>

            <ul>
                <li>Coding</li>
                <li>Reading Books</li>
                <li>Listening to Music</li>
            </ul>
        </section>

        <section id="learning" class="content-section">
            <h2>My Learning Plan</h2>

            <p>
                These are some of the steps I will take to improve my web
                development skills:
            </p>

            <ol>
                <li>Practise HTML and CSS regularly.</li>
                <li>Build small websites and improve their designs.</li>
                <li>Practise creating interactive pages.</li>
            </ol>

            <h3>Weekly Web Learning Plan</h3>

            <table border ="2">
                <caption>My Weekly Web Development Practice Plan</caption>

                    <tr> <th>Day</th>
                         <th>Topic</th>
                         <th>Practice Task</th>
                    </tr>

                    <tr> <td>Monday</td>
                         <td>HTML</td>
                         <td>Practise headings, paragraphs, links and lists.</td>
                    </tr>

                    <tr> <td>Tuesday</td>
                         <td>CSS</td>
                         <td>Practise colours, spacing, borders and layouts.</td>
                    </tr>

                    <tr> <td>Thursday</td>
                         <td>Web Design</td>
                         <td>Build and test small responsive webpages.</td>
                    </tr>
            </table>
        </section>
        <section id="projects" class="content-section">
    <h2>My Skills and Projects</h2>

    <div class="project-grid">

        <article class="project-card">
            <h3>HTML5</h3>
            <p>
                I have learned how to create and structure webpages
                using HTML5 elements.
            </p>
        </article>

        <article class="project-card">
            <h3>CSS</h3>
            <p>
                I have learned how to style webpages using colours,
                spacing, borders and responsive layouts.
            </p>
        </article>

        <article class="project-card">
            <h3>JavaScript</h3>
            <p>
                I am learning how JavaScript can make webpages
                interactive using events and DOM manipulation.
            </p>
        </article>

    </div>
</section>

        <section id="photos" class="content-section">
            <h2>My Photos</h2>

            <p>
                The gallery below contains photos that represent my interests
                and student life.
            </p>

            <div class="myweb-images">

                <figure>
                    <img src="file:///C:\Users\VALUED CUSTOMER\Desktop\WebTech_Assignments\myweb\images\photo5.jpg.jpg"
                         alt="Photo representing coding and web development">
                    <figcaption>Coding and learning web development.</figcaption>
                </figure>

                <figure>
                    <img src="file:///C:\Users\VALUED CUSTOMER\Desktop\WebTech_Assignments\myweb\images\photo3 (3).jpg"
                         alt="Photo representing me during my free time">
                    <figcaption>Me during my free time.</figcaption>
                </figure>

                <figure>
                    <img src="file:///C:\Users\VALUED CUSTOMER\Desktop\WebTech_Assignments\myweb\images\photo1.jpg.jpg"
                         alt="Photo representing me going to study">
                    <figcaption>Going to read as one of my hobbies.</figcaption>
                </figure>

            </div>

            <p class="photo-note">
                All photos used on this website are my own photos or photos
                that I have permission to use.
            </p>
        </section>

        
        <section id="media" class="content-section">
            <h2>My Media</h2>

            <h3>My Introduction Video</h3>

            <video controls>
                <source src="videos/intro.mp4" type="video/mp4">
            </video>

            <p>
                In this short video, I introduce myself, mention my programme
                and explain one web development skill that I hope to learn.
            </p>

            <h3>My Audio Clip</h3>

            <audio controls>
                <source src="file:///C:\Users\VALUED CUSTOMER\Desktop\WebTech_Assignments\myweb\videos\voice.mp3.aac">
            
            </audio>

            <p>
                In this audio recording, I talk about one of my hobbies and
                explain why I enjoy it.
            </p>
        </section>

        <section id="contact" class="content-section">
            <h2>Contact Me</h2>

            <p>
                This form is a browser demonstration only. It does not send
                any information to a server.
            </p>

            <form action="#" method="post">

                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text"
                           id="name"
                           name="name"
                           required>
                </div>

                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email"
                           id="email"
                           name="email"
                           required>
                </div>

                <div class="form-group">
                    <label for="topic">Topic:</label>
                    <select id="topic" name="topic">
                        <option value="general">General</option>
                        <option value="web-development">Web Development</option>
                        <option value="hobbies">Hobbies</option>
                        <option value="other">Other</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea id="message"
                              name="message"
                              rows="6"
                              required></textarea>
                </div>

                <button type="submit">Send Message</button>

            </form>
        </section>

    </main>

     <footer>
        <div class="container">
            <p>&copy; 2026 Taonga Kataya | Student ID: 202204909</p>
            <p>ICT251 Web Technologies</p>
        </div>
    </footer>

</body>
</html>

