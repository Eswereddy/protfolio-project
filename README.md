# protfolio-project
A personal portfolio website showcasing my skills, projects, experience, certifications, and resume. Built using HTML, TailwindCSS, JavaScript, and animated with particles.js for a modern, interactive user experience.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jakkireddy Eswar Reddy | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/particles.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
  <style>
    #particles-js {
      position: fixed;
      width: 100%;
      height: 100%;
      z-index: -1;
      top: 0;
      left: 0;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    section {
      animation: fadeIn 1s ease-out forwards;
      opacity: 0;
    }

    @media (max-width: 768px) {
      .grid-cols-1-md-2 {
        grid-template-columns: 1fr;
      }
      .text-5xl {
        font-size: 3rem;
      }
      .text-xl {
        font-size: 1.125rem;
      }
      .w-56 {
        width: 12rem;
        height: 12rem;
      }
    }

    @media (max-width: 480px) {
      .text-5xl {
        font-size: 2.5rem;
      }
      .text-3xl {
        font-size: 2rem;
      }
      .text-xl {
        font-size: 1rem;
      }
      .w-56 {
        width: 10rem;
        height: 10rem;
      }
    }
  </style>
</head>
<body class="bg-gradient-to-br from-gray-900 via-gray-800 to-gray-900 text-white font-sans">
  <div id="particles-js"></div>
  
  <header class="text-center py-16 animate-fadeIn">
    <img src="eswar.jpg" alt="Jakkireddy Eswar Reddy" class="mx-auto rounded-full w-56 h-56 mb-4 border-4 border-indigo-500 shadow-lg transform transition-transform hover:scale-105">
    <h1 class="text-5xl font-extrabold tracking-tight">Jakkireddy Eswar Reddy</h1>
    <p class="mt-2 text-xl text-indigo-300">Full Stack Developer | Java & Python Enthusiast</p>
    <div class="flex justify-center space-x-6 mt-4">
      <a href="mailto:jakkireddyeswarreddy@gmail.com" class="hover:text-indigo-400 transform hover:scale-110 transition-transform"><i class="fas fa-envelope text-2xl"></i></a>
      <a href="https://github.com/yourgithub" target="_blank" class="hover:text-indigo-400 transform hover:scale-110 transition-transform"><i class="fab fa-github text-2xl"></i></a>
      <a href="https://linkedin.com/in/yourlinkedin" target="_blank" class="hover:text-indigo-400 transform hover:scale-110 transition-transform"><i class="fab fa-linkedin text-2xl"></i></a>
      <a href="#contact" class="hover:text-indigo-400 transform hover:scale-110 transition-transform"><i class="fas fa-phone-alt text-2xl"></i></a>
    </div>
    <a href="#contact" class="mt-6 inline-block bg-indigo-600 px-6 py-2 rounded-full hover:bg-indigo-700 shadow-md transition transform hover:scale-105">Contact Me</a>
  </header>
  
  <section id="about" class="py-12 max-w-6xl mx-auto px-6">
    <h2 class="text-3xl font-bold text-indigo-400 mb-6 text-center">About Me</h2>
    <div class="grid md:grid-cols-2 gap-6 items-center">
      <div>
        <p class="text-lg leading-relaxed mb-4">
          I’m <strong>Jakkireddy Eswar Reddy</strong>, a passionate and detail-oriented developer currently pursuing my B.Tech in Computer Science and Engineering at <strong>G. Pullaiah College of Engineering & Technology, Kurnool</strong>. I have also completed a diploma in CSE from <strong>BIT Institute of Technology, Hindupur</strong>.
        </p>
        <p class="text-lg leading-relaxed mb-4">
          I’ve earned certifications in DBMS, AWS, Microsoft Azure Fundamentals, and Java. I love building user-centric applications, solving real-world problems, and exploring new technologies. I'm highly enthusiastic about learning cloud platforms and backend development practices.
        </p>
        <p class="text-lg leading-relaxed mb-4">
          I'm an active learner who thrives in team environments. I believe in collaboration, continuous upskilling, and delivering scalable applications that solve real-world issues. My goal is to contribute meaningfully in the tech ecosystem and work on impactful projects.
        </p>
        <p class="text-lg leading-relaxed">
          Outside of coding, I enjoy exploring tech blogs, participating in coding contests, and mentoring juniors. My long-term vision includes becoming a versatile developer and cloud solutions architect.
        </p>
      </div>
      <div class="flex flex-col items-center space-y-6">
        <img src="about.jpg" alt="About Me" class="rounded-lg shadow-lg w-full max-w-md transform transition-transform hover:scale-105">
      </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-10">
      <div class="bg-gray-800 p-4 rounded-lg shadow transform transition-transform hover:scale-105">
        <img src="pullaiah.jpg" alt="G. Pullaiah College" class="w-full h-64 object-cover rounded mb-2">
        <h3 class="text-xl font-semibold text-indigo-300">B.Tech – G. Pullaiah College of Engineering & Technology, Kurnool</h3>
        <p class="text-sm mt-2">An autonomous institution accredited with NAAC 'A' grade and NBA-certified departments. Offers in-depth curriculum in engineering principles, design methodologies, and project development with strong placement and research opportunities.</p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg shadow transform transition-transform hover:scale-105">
        <img src="bit.jpg" alt="BIT Institute of Technology" class="w-full h-64 object-cover rounded mb-2">
        <h3 class="text-xl font-semibold text-indigo-300">Diploma – BIT Institute of Technology, Hindupur</h3>
        <p class="text-sm mt-2">A reputed polytechnic institution focusing on practical and technical education. CSE diploma includes programming, system design, and real-time lab sessions, fostering readiness for higher studies and industry exposure.</p>
      </div>
    </div>
  </section>
  
  <section id="resume" class="py-12 text-center">
    <h2 class="text-3xl font-bold text-indigo-400 mb-4">Resume</h2>
    <p class="text-lg text-gray-300 mb-4">My resume reflects my journey as a full stack developer, showcasing my experience, certifications, education, and project work in detail. I’ve included my training in AWS, Azure, DBMS, and my internship with Movidu Technologies.</p>
    <a href="Jakkireddy%20Eswar%20reddy.pdf" download class="bg-indigo-600 hover:bg-indigo-700 px-6 py-2 rounded-full font-semibold text-white transition transform hover:scale-105">Download My Resume (PDF)</a>
  </section>
  
  <section id="experience" class="py-12 max-w-6xl mx-auto px-6">
    <h2 class="text-3xl font-bold text-indigo-400 mb-6 text-center">Experience</h2>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="bg-gray-800 p-6 rounded-lg shadow-md transform transition-transform hover:scale-105">
        <img src="experience.jpg" alt="Internship Certificate" class="w-full h-64 object-cover rounded mb-4">
        <h3 class="text-xl font-semibold text-indigo-300">Business Development Intern – Movidu Technologies</h3>
        <p class="mt-2 text-gray-300">Nov 2023 – May 2024</p>
        <p class="text-sm mt-2">Completed a 6-month internship where I contributed to the Business Development vertical. Built communication, analysis, and reporting skills while also being appreciated as a team player and quick learner.</p>
      </div>
    </div>
  </section>
  
  <section id="certifications" class="py-12 max-w-6xl mx-auto px-6">
    <h2 class="text-3xl font-bold text-indigo-400 mb-6 text-center">Certifications</h2>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="bg-gray-800 p-4 rounded-lg shadow transform transition-transform hover:scale-105">
        <img src="dbms_certificate.jpg" alt="DBMS Certificate" class="w-full h-48 object-cover rounded mb-2">
        <p class="text-sm text-center">DBMS Mastery – Scaler Academy</p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg shadow transform transition-transform hover:scale-105">
        <img src="java_codetantra.jpg" alt="Java Certificate" class="w-full h-48 object-cover rounded mb-2">
        <p class="text-sm text-center">Java Programming – CodeTantra</p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg shadow transform transition-transform hover:scale-105">
        <img src="java_scaler.jpg" alt="Java Fundamentals Certificate" class="w-full h-48 object-cover rounded mb-2">
        <p class="text-sm text-center">Java Fundamentals – Scaler Academy</p>
      </div>
      <div class="bg-gray-800 p-4 rounded-lg shadow transform transition-transform hover:scale-105">
        <img src="webdevelopment.jpg" alt="Web Development Certifications" class="w-full h-48 object-cover rounded mb-2">
        <p class="text-sm text-center">Web Development Certifications by Ecell IIT Madras</p>
      </div>
    </div>
  </section>
  
  <section id="projects" class="py-12">
    <h2 class="text-3xl font-bold text-indigo-400 mb-6 text-center">Projects</h2>
    <div class="grid gap-6 sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 max-w-6xl mx-auto">
      <div class="bg-gradient-to-br from-gray-800 to-gray-900 p-6 rounded-xl shadow-xl hover:shadow-2xl hover:scale-105 transition-transform">
        <h3 class="text-xl font-bold text-white mb-2">Portfolio Website</h3>
        <p class="text-gray-300 mb-2">Responsive personal site using TailwindCSS, HTML, and particle.js background effects.</p>
        <a href="#" class="text-indigo-400 underline">Live Demo</a>
      </div>
      <div class="bg-gradient-to-br from-gray-800 to-gray-900 p-6 rounded-xl shadow-xl hover:shadow-2xl hover:scale-105 transition-transform">
        <h3 class="text-xl font-bold text-white mb-2">Resume Builder</h3>
        <p class="text-gray-300 mb-2">Web application to generate resumes with clean UI and print/export functionality.</p>
        <a href="#" class="text-indigo-400 underline">Live Demo</a>
      </div>
      <div class="bg-gradient-to-br from-gray-800 to-gray-900 p-6 rounded-xl shadow-xl hover:shadow-2xl hover:scale-105 transition-transform">
        <h3 class="text-xl font-bold text-white mb-2">Student Management System</h3>
        <p class="text-gray-300 mb-2">CRUD system using Java and MySQL to manage student academic records efficiently.</p>
        <a href="#" class="text-indigo-400 underline">View Project</a>
      </div>
    </div>
  </section>

  <section id="contact" class="py-12">
    <h2 class="text-3xl font-bold text-indigo-400 mb-6 text-center">Contact Me</h2>
    <div class="max-w-2xl mx-auto bg-gray-800 p-6 rounded-xl shadow-md">
      <form action="#" method="POST" class="space-y-6">
        <div>
          <label for="name" class="block text-sm font-semibold mb-1">Name</label>
          <input type="text" id="name" name="name" required class="w-full px-4 py-2 rounded-lg bg-gray-900 text-white border border-indigo-600 focus:outline-none focus:ring-2 focus:ring-indigo-400">
        </div>
        <div>
          <label for="email" class="block text-sm font-semibold mb-1">Email</label>
          <input type="email" id="email" name="email" required class="w-full px-4 py-2 rounded-lg bg-gray-900 text-white border border-indigo-600 focus:outline-none focus:ring-2 focus:ring-indigo-400">
        </div>
        <div>
          <label for="message" class="block text-sm font-semibold mb-1">Message</label>
          <textarea id="message" name="message" rows="4" required class="w-full px-4 py-2 rounded-lg bg-gray-900 text-white border border-indigo-600 focus:outline-none focus:ring-2 focus:ring-indigo-400"></textarea>
        </div>
        <div class="text-center">
          <button type="submit" class="bg-indigo-600 hover:bg-indigo-700 px-6 py-2 rounded-full text-white font-semibold shadow transition transform hover:scale-105">Send Message</button>
        </div>
      </form>
      <p class="mt-6 text-center text-sm text-gray-400">Or email me directly at <a href="mailto:jakkireddyeswarreddy@gmail.com" class="text-indigo-300 underline">jakkireddyeswarreddy@gmail.com</a></p>
    </div>
  </section>
  
  <footer class="bg-gray-950 text-white py-10 mt-16">
    <div class="max-w-6xl mx-auto px-6">
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8 text-sm text-gray-400">
        <div>
          <h4 class="text-lg font-semibold text-white mb-2">Quick Links</h4>
          <ul class="space-y-1">
            <li><a href="#about" class="hover:text-indigo-400">About</a></li>
            <li><a href="#skills" class="hover:text-indigo-400">Skills</a></li>
            <li><a href="#projects" class="hover:text-indigo-400">Projects</a></li>
            <li><a href="#experience" class="hover:text-indigo-400">Experience</a></li>
            <li><a href="#contact" class="hover:text-indigo-400">Contact</a></li>
          </ul>
        </div>
        <div>
          <h4 class="text-lg font-semibold text-white mb-2">Contact</h4>
          <p><i class="fas fa-phone-alt text-indigo-400"></i> +91 93810 26276</p>
          <p><i class="fas fa-envelope text-indigo-400"></i> jakkireddyeswarreddy@gmail.com</p>
          <p><i class="fas fa-map-marker-alt text-indigo-400"></i> Peapully, Andhra Pradesh, India</p>
        </div>
        <div>
          <h4 class="text-lg font-semibold text-white mb-2">Follow Me</h4>
          <div class="flex space-x-4 mt-2">
            <a href="#" class="hover:text-indigo-400 transform hover:scale-110 transition-transform"><i class="fab fa-github text-2xl"></i></a>
            <a href="#" class="hover:text-indigo-400 transform hover:scale-110 transition-transform"><i class="fab fa-linkedin text-2xl"></i></a>
            <a href="#" class="hover:text-indigo-400 transform hover:scale-110 transition-transform"><i class="fab fa-twitter text-2xl"></i></a>
          </div>
        </div>
      </div>
      <div class="text-center text-sm text-gray-500 mt-8 border-t border-gray-700 pt-4">
        &copy; 2025 Jakkireddy Eswar Reddy. Built with ❤ using HTML, TailwindCSS, and JavaScript.
      </div>
    </div>
  </footer>

  <script>
    particlesJS("particles-js", {
      particles: {
        number: { value: 100 },
        size: { value: 3 },
        color: { value: "#6366f1" },
        line_linked: {
          enable: true,
          distance: 150,
          color: "#a5b4fc",
          opacity: 0.5,
          width: 1
        },
        move: {
          enable: true,
          speed: 2
        }
      },
      interactivity: {
        events: {
          onhover: {
            enable: true,
            mode: "repulse"
          }
        }
      }
    });

    document.addEventListener('DOMContentLoaded', function() {
      const sections = document.querySelectorAll('section');
      const options = {
        threshold: 0.1
      };

      const observer = new IntersectionObserver((entries, observer) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            entry.target.style.animation = 'fadeIn 1s ease-out forwards';
            observer.unobserve(entry.target);
          }
        });
      }, options);

      sections.forEach(section => {
        observer.observe(section);
      });
    });
  </script>
</body>
</html>

