<script>
    import jlox from "$lib/assets/jlox.png";
    import gh from "$lib/assets/square-github.svg";
    import linkedin from "$lib/assets/linkedin.svg";
</script>

<body class="container">
    <main class="grid">
        <div class="bar">
            <section class="info">
                <h1>HyungJoo Yoon</h1>
                <h4>Computer Science major</h4>
                <h4>Software Engineer</h4>

                <br><p>I build software. I also break them.</p>
            </section>
            <section class="links">
               <a href="https://github.com/dhnpx"><img src={gh} alt="github" class="icon"></a> 
               <a href="https://linkedin.com/in/hyungjooyoon"><img src={linkedin} alt="linkedin" class="icon"></a>
            <section>
        </div>
        <div class="content">
            <p class="about">
                I started programming in 2021 in a bootcamp and I haven't looked 
                back. I got started in web development, but I started
                dabbling in cyber security, and Linux not too long after. I
                learned to enjoy simple, functional programs and subverting the
                security of systems running them.
            </p>
            <p>
                Now, I'm a student at Cal State Fullerton to learn more about
                lower level systems. I want to build software that solves
                problems and more importantly, help others.
            </p>
            <p>
                In my free time, I'm either planning a new distrohop and
                tinkering with my system, or trying out new software. If you're
                a hobbyist too, let's talk about it.
            </p>
            <h2>Experience</h2><br>
            <div class="grid">
                <div>
                    <span>2024 - Present</span>
                </div>
                <div>
                    <h5>Air Force Research Laboratory</h5>
                    <p>Intern</p>
                    <p>
                        Conduct research and literature review into Cyber
                        Security and attack surfaces of autonomous space
                        systems. Aggreagte literature and devlop a report and
                        publish on the findings.
                    </p>
                </div>
            </div>
            <br />
            <div class="grid">
                <div><span>2022 - 2023</span></div>
                <div>
                    <h5>Revature</h5>
                    <p>Associate</p>
                    <p>
                        Worked with clients to develop and maintain full-stack
                        web applications in Java, SpringBoot, Typescript, and
                        Angular. I also worked with SQL and NoSQL databases as
                        well as AWS deployments. Set up CI/CD pipelines with
                        Jenkins.
                    </p>
                </div>
            </div>
            <br />
            <div class="grid">
                <div><span>2020</span></div>
                <div>
                    <h5>CJ Logistics</h5>
                    <p>Customer I</p>
                    <p>
                        Interfaced with carriers and the warehouse to make sure
                        shipments were correct and on time. Signed off on
                        inbound and outbound BOLs and confirm shipments. Managed
                        Amazon foods accounts and processed orders and
                        shipments.
                    </p>
                </div>
            </div>
            <h2>Projects</h2><br>
            <div class="grid">
                <a href="https://github.com/dhnpx/jlox">
                    <img src={jlox} alt="jlox" />
                </a>
                <div>
                    <h5>JLox</h5>
                    <p>
                        A Java implementation of the Lox language from the book
                        "Crafting Interpreters" by Bob Nystrom. It's followed by
                        a bytecode VM in C.
                    </p>
                </div>
            </div>
        </div>
    </main>
</body>

<style>
    :root {
        font-size: 18px;
    }
    .grid {
        display: grid;
        grid-template-columns: 1fr 3fr;
        gap: 1rem;
    }

    .about {
        text-align: justify;
    }

    img {
        width: 100%;
        height: auto;
    }

    .content {
        height: 100vh;
        overflow-y: scroll;
        scrollbar-width: none;
    }

    .container {
        height: 100vh;
        overflow: hidden;
    }
    
    .icon {
        width: 2rem;
        height: 2rem;
    }

    h5 {
        color: white;
        margin: 0;
    }

    h4 {
        margin: 0;
    }
    
    .links {
        position: fixed;
        bottom: 0;
    }
</style>
