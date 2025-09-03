# DBMS-NOTES
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=    
    , initial-scale=1.0">
  <title>Document</title>
</head>
<!-- <link rel="stylesheet" href="style.css"> -->
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f9f9f9;


  }

  header {
    background: #2563eb;
    color: white;
    height: 70vh;

    padding: 15px;
    text-align: center;
  }

  header h1 {
    font-size: 25vh;
  }

  nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
  }

  .hero {
    text-align: center;
    padding: 40px;
    background: linear-gradient(to right, #2563eb, #4f46e5);
    color: white;
    display: flex;
    flex-direction: column;

  }


  .search {
    text-align: center;
    margin: 20px;
  }

  .search input {
    padding: 10px;
    width: 250px;
    border-radius: 8px;
    border: 1px solid #ccc;
  }

  .notes {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
  }

  .card {
    background: white;
    padding: 15px;
    border-radius: 12px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
  }

  .card h3 {
    margin: 0 0 5px;
  }

  footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 10px;
    font-family: poppins;
    margin-top: 20px;
  }
</style>

<body>
  <header>
    <h1>📘 DBMS Notes</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Notes</a>
      <a href="#">About</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to DBMS Notes 📚</h2>
    <p>All important topics of DBMS in one place!</p>
  </section>

  <div class="search">
    <input type="text" placeholder="Search topics...">
  </div>

  <section class="notes">

    <div class="card">
      <h3>Introduction</h3>
      <p>Category: Modeling</p>
      <button><a href="chp1.html">Read Notes</a></button>
    </div>
    <div class="card">
      <h3>Data model and keys</h3>
      <p>Category: Query</p>
      <button><a href="chp2.html">Read Notes</a></button>
    </div>
    <div class="card">
      <h3>Relational Model</h3>
      <p>Category: Design</p>
      <button><a href="#">Read Notes</a></button>
    </div>
    <div class="card">
      <h3>Relational Databse Design</h3>
      <p>Category: Design</p>
      <button><a href="#">Read Notes</a></button>
    </div>
    <div class="card">
      <h3>SQL/My SQL</h3>
      <p>Category: Design</p>
      <button><a href="#">Read Notes</a></button>
    </div>
  </section>

  <footer>
    <p>Made with ROSHAN KUMAR | DBMS Notes Project</p>
  </footer>




  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.13.0/gsap.min.js"
    integrity="sha512-NcZdtrT77bJr4STcmsGAESr06BYGE8woZdSdEgqnpyqac7sugNO+Tr4bGwGF3MsnEkGKhU2KL2xh6Ec+BqsaHA=="
    crossorigin="anonymous" referrerpolicy="no-referrer"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.13.0/ScrollTrigger.min.js"
    integrity="sha512-P2IDYZfqSwjcSjX0BKeNhwRUH8zRPGlgcWl5n6gBLzdi4Y5/0O4zaXrtO4K9TZK6Hn1BenYpKowuCavNandERg=="
    crossorigin="anonymous" referrerpolicy="no-referrer"></script>
  <script src="script.js">// let tl = timeline();
    gsap.from("header h1", {
      x: 150,
      duration: 2,
      opacity: 0,
      scrollTrigger: {
        trigger: "header h1",
        scroller: "body",
        // markers:true,
        start: "top 15%",
        end: "top 0%",
        scrub: 2,


      }
    })
    gsap.from("header nav a", {
      x: -58,
      duration: 1,
      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: "header nav a",
        scroller: "body",
        // markers:true,
        start: "top 40%",
        end: "top 35%",
        scrub: 2,
      }


    })
    gsap.from(".hero h2", {
      scale: 0.2,
      duration: 1,
      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: ".hero h2",
        scroller: "body",
        // markers:true,
        start: "top 70%",
        end: "top 55%",
        scrub: 2,
      }


    })


    gsap.from(".hero p", {
      y: 78,
      delay: 8,
      duration: 1,
      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: ".hero h2",
        scroller: "body",
        // markers:true,
        start: "top 50%",
        end: "top 35%",
        scrub: 2,
      }


    })
    gsap.from(".hero p", {
      y: 78,
      delay: 2,
      duration: 1,
      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: ".hero h2",
        scroller: "body",
        // markers:true,
        start: "top 50%",
        end: "top 35%",
        scrub: 2,
      }


    })
    gsap.from(".hero p", {
      y: 78,
      delay: 2,
      duration: 1,
      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: ".hero h2",
        scroller: "body",
        // markers:true,
        start: "top 50%",
        end: "top 35%",
        scrub: 2,
      }

    })
    gsap.from(".search", {
      y: 78,
      delay: 2,
      duration: 1,
      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: ".search",
        scroller: "body",
        // markers:true,
        start: "top 50%",
        end: "top 25%",
        scrub: 2,
      }

    })
    gsap.from(".card", {
      y: 78,
      delay: 5,
      duration: 5,
      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: ".card",
        scroller: "body",
        // markers:true,
        start: "top 60%",
        end: "top 55%",
        scrub: 2,
      }

    })
    gsap.from("footer p", {
      x: 780,

      opacity: 0,
      stagger: 1,
      scrollTrigger: {
        trigger: "footer p",
        scroller: "body",
        // markers: true,
        start: "top 100%",
        end: "top 95%",
        scrub: true,
      }

    })
  </script>
</body>

</html>
