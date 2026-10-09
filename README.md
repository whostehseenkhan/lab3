<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>

    
    <link rel="stylesheet" href="styles.css">

</head>

<body>
    </a>
    <header>
        <h1>Tehseen Ullah Khan</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#timeline">Timeline</a>
            <a href="#media">Media</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <article id="about">
            <h2>About Me</h2>
            <figure>
                <img src="page-pic.jpg" alt="Photo of Tehseen Ullah Khan" width="180" height="80">
            </figure>

            <p>
                I am a Computer Science student interested in
                web development, programming, and building useful
                digital applications.
            </p>

            <p>
                I am currently improving my HTML, CSS, Python,
                and problem solving skills. i want to become
                a skilled web and software developer.
            </p>
            <blockquote>
                <p> "The best way to learn is by building."</p>
            </blockquote>
        </article>

         <section id="skills">
            <h2>Skills I'm Building This Semester</h2>
            <ul>
                <li>HTML5 & Semantic Markup</li>
                <li>CSS and Web Development</li>
                <li>Python Programming</li>
                <li>Problem Solving</li>
                <li>Git & GitHub</li>
            </ul>
        </section>


        <section id="timeline">
            <h2>My Timeline So Far</h2>
            <ol>
                <li> Completed Lab 1 and set up my development environment.</li>
                <li> Built my first static webpage using HTML and CSS.</li>
                <li>Started this semantic HTML5 profile page.</li>
            </ol>
        </section>


        <aside>
            <h2>Fun Fact</h2>
            <p>I enjoy learning new technology by creating small practical projects.</p>
        </aside>


          <section id="media">
            <h2>A Short Clip</h2>
            <video controls width="480">
                <source src="page-shortclip.mp4" type="video/mp4">
            </video>
        </section>


        <section id="contact">
            <h2>Contact Me</h2>
            <form id="contact-form">
                <fieldset>
                    <legend>Send me a message</legend>
                    <p>
                        <label for="name"> Name </label>
                        <input type="text" id="name" name="name" required>
                    </p>

                    <p>
                        <label for="email"> Email </label>
                        <input type="email"id="email"name="email"required>
                    </p>

                    <p>
                        <label for="topic"> Topic </label>
                        <select id="topic" name="topic">
                            <option value="general">General</option>
                            <option value="feedback">Feedback</option>
                            <option value="bug">Report a Bug</option>
                        </select>
                    </p>


                    <p>Preferred reply method:</p>
                    <label> <input type="radio" name="reply" value="email"checked> Email </label>
                    <label> <input type="radio"name="reply"value="phone"> Phone </label>

                    <p>
                        <label> <input type="checkbox"id="subscribe"name="subscribe"> Subscribe to updates </label>
                    </p>


                    <p>
                        <label for="callback-date"> Preferred callback date</label>
                        <input type="date" id="callback-date" name="callback-date">
                    </p>


                    <p>
                        <label for="urgency"> Urgency (1 = whenever, 10 = right now) </label>
                        <input type="range" id="urgency" name="urgency" min="1" max="10" value="5">
                    </p>


                    <p>
                        <label for="message"> Message</label>
                        <textarea id="message" name="message" rows="4" required minlength="10"></textarea>
                    </p>

                    <button type="submit"> Send </button>
                </fieldset>
            </form>
        </section>
    </main>
    <script src="script.js"></script>
</body>

</html>