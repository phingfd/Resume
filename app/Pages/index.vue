<template>
  <div class="bg-gray-100 p-4 w-full">
    <!-- Profile Image Centered -->
    <div class="flex justify-center mb-4">
      <img
        src="/images/Profile.png"
        alt="Profile"
        class="h-80 w-80 object-cover rounded-full shadow-md"
      />
    </div>

    <!-- Contact Information -->
    <div class="text-center mb-6">
      <div class="text-sm text-gray-700 max-w-md mx-auto text-left">
        <p><strong>Name:</strong> Jerric John D. Denosta</p>
        <p>
          <strong>Email:</strong>
          <a class="text-blue-700 underline" href="mailto:Phingfd@gmail.com">
            Phingfd@gmail.com</a
          >
        </p>
        <p><strong>Phone:</strong> 09203001800</p>
        <p><strong>Address:</strong> Block 13 Lot 9, Cerritos Camella Homes</p>
      </div>
    </div>

    <hr class="border-t border-gray-400 my-6 mx-auto w-full" />

    <!-- Professional Objective -->
    <div class="text-center mb-6">
      <h2 class="text-xl font-semibold text-gray-800">
        Professional Objective
      </h2>
      <p class="text-sm text-gray-950 max-w-3xl mx-auto mt-2">
        Motivated and detail-oriented IT Web Developer seeking a challenging
        position where I can leverage my skills in front-end and back-end
        development to build responsive, user-friendly web applications. Eager
        to contribute to innovative projects, expand my technical expertise in
        modern frameworks and technologies, and support the company’s digital
        growth by delivering efficient, scalable web solutions.
      </p>
    </div>

    <hr class="border-t border-gray-400 my-6 mx-auto w-full" />
    <!-- Personal Information -->
    <div class="bg-gray-100 p-4 w-full">
      <div
        class="text-left text-xl font-bold border-b border-gray-300 text-gray-800 mb-2 max-w-5xl mx-auto"
      >
        Personal Information
      </div>
      <div class="text-left mb-2 max-w-5xl mx-auto">
        Date of Birth: <br />
        <p class="font-semibold">02/06/1999</p>
      </div>
      <div class="text-left mb-2 max-w-5xl mx-auto">
        Marital Status: <br />
        <p class="font-semibold">Single</p>
      </div>
      <div class="text-left mb-2 max-w-5xl mx-auto">
        Nationality: <br />
        <p class="font-semibold">Filipino</p>
      </div>
      <div class="text-left mb-2 max-w-5xl mx-auto">
        Religion: <br />
        <p class="font-semibold">Born Again</p>
      </div>
      <div class="text-left mb-2 max-w-5xl mx-auto">
        Weight: <br />
        <p class="font-semibold max-w-5xl mx-auto">68klg</p>
      </div>
    </div>

    <hr class="border-t border-gray-400 my-6 mx-auto w-full" />

    <!-- Skills -->
    <div class="bg-gray-200 py-5 px-4 w-full">
      <div class="max-w-5xl mx-auto">
        <!-- Section Header -->
        <h2 class="text-2xl font-bold border-b border-gray-300 pb-2 mb-6">
          Skills
        </h2>
        <div class="text-xl text-gray-700 mb-2">Technical Skills</div>

        <!-- Skills Grid -->
        <div class="flex flex-col md:flex-row md:justify-between gap-8">
          <!-- Frontend -->
          <div class="flex-1">
            <h3 class="text-xl font-bold text-gray-800 mb-2">Frontend</h3>
            <ul
              class="list-disc list-inside text-sm font-semibold text-gray-700 space-y-1"
            >
              <li>HTML, Tailwind CSS, JavaScript</li>
              <li>Vue.js, Nuxt, Inertia.js, Vite, NPM</li>
              <li>Responsive Design, Bootstrap, CSS</li>
            </ul>
          </div>

          <!-- Backend -->
          <div class="flex-1">
            <h3 class="text-xl font-bold text-gray-800 mb-2">Backend</h3>
            <ul
              class="list-disc list-inside text-sm font-semibold text-gray-700 space-y-1"
            >
              <li>PHP (Laravel), RESTful APIs</li>
              <li>MySQL, Laravel Sanctum, Nuxt.js</li>
            </ul>
          </div>

          <!-- Applications -->
          <div class="flex-1">
            <h3 class="text-xl font-bold text-gray-800 mb-2">
              Applications Used
            </h3>
            <ul
              class="list-disc list-inside text-sm font-semibold text-gray-700 space-y-1"
            >
              <li>Visual Studio Code, GitHub, Docker, MySQL</li>
            </ul>
          </div>
        </div>

        <!-- Icon Row -->
        <div class="flex flex-wrap justify-center md:justify-start gap-4 mt-5">
          <Icon name="vscode-icons:file-type-html" class="w-8 h-8" />
          <Icon name="skill-icons:javascript" class="w-8 h-8" />
          <Icon name="skill-icons:vuejs-dark" class="w-8 h-8" />
          <Icon name="skill-icons:nuxtjs-light" class="w-8 h-8" />
          <Icon name="skill-icons:tailwindcss-light" class="w-8 h-8" />
          <Icon name="skill-icons:php-dark" class="w-8 h-8" />
          <Icon name="skill-icons:mysql-light" class="w-8 h-8" />
          <Icon name="skill-icons:vscode-dark" class="w-8 h-8" />
          <Icon name="skill-icons:github-dark" class="w-8 h-8" />
          <Icon name="skill-icons:docker" class="w-8 h-8" />
        </div>

        <div class="text-xl text-gray-900 mt-8">Soft Skills</div>
        <div class="flex flex-col md:flex-row md:justify-between gap-8">
          <div class="flex-1 pt-2">
            <ul
              class="list-disc list-inside text-sm font-semibold text-gray-800 space-y-1"
            >
              <li>
                Willingness to Learn: Eager to absorb new concepts,
                technologies, and best practices in web development.
              </li>
              <li>
                Problem-Solving Mindset: Able to approach issues logically and
                seek solutions through research, debugging, and asking the right
                questions.
              </li>
              <li>
                Clear Communication: Comfortable explaining ideas and asking for
                clarification when needed to ensure shared understanding.
              </li>
              <li>
                User-Centered Thinking: Gaining experience in translating basic
                requirements into user-friendly features.
              </li>
              <li>
                Time Awareness: Learning to prioritize tasks and meet deadlines
                with guidance and planning.
              </li>
              <li>
                Team Player: Enthusiastic about contributing to team goals and
                learning from more experienced peers in collaborative
                environments.
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <hr class="border-t border-gray-400 my-6 mx-auto w-full" />
    <!-- Work Experience -->
    <div class="max-w-5xl mx-auto py-5 text-sm text-gray-800 font-sans">
      <h2 class="text-2xl font-bold border-b border-gray-300 pb-2 mb-6">
        Work Experience
      </h2>

      <div class="mb-6">
        <div class="flex justify-between items-start">
          <div>
            <h3 class="text-base font-semibold">Junior Programmer</h3>
            <p class="text-gray-600">Dadiangas Medical Center. (Onsite)</p>
          </div>
          <span class="text-gray-500 text xs">August 2024 - Present</span>
        </div>
        <ul class="list-disc list-inside mt-2 text-gray-700 leading-relaxed">
          <li>
            Developed responsive web pages using HTML, CSS, and JavaScript.
          </li>
          <li>
            Built interactive UI components with Vue.js and Inertia.js for a
            smooth user experience.
          </li>
          <li>
            Connected frontend features to Laravel PHP backend systems and
            RESTful APIs.
          </li>
          <li>
            Worked with MySQL databases for data storage and retrieval in web
            applications.
          </li>
          <li>
            Used Sourcetree for version control and collaborative development.
          </li>
          <li>
            Gained foundational experience with Docker for containerized
            application setups.
          </li>
          <li>
            Explored basic WordPress development for content-driven sites.
          </li>
          <li>
            Learning Nuxt.js for building Vue-based static and server-rendered
            applications.
          </li>
        </ul>
      </div>
      <div class="mb-6">
        <div class="flex justify-between items-start">
          <div>
            <h3 class="text-base font-semibold">
              Software Support / Technical Support / Web Developer / OJT
            </h3>
            <p class="text-gray-600">Dadiangas Medical Center. (Onsite)</p>
          </div>
          <span class="text-gray-500 text xs">March 2023 - July 2023</span>
        </div>
        <ul class="list-disc list-inside mt-2 text-gray-700 leading-relaxed">
          <li>
            Encoded and organized data accurately for internal records and
            reports.
          </li>
          <li>
            Performed inventory adjustments to maintain accurate stock levels.
          </li>
          <li>
            Developed and maintained simple websites using HTML, CSS, and
            JavaScript.
          </li>
          <li>
            Provided basic technical support including connecting printers
            across networks.
          </li>
          <li>
            Troubleshooted and resolved common Windows errors and performed
            system updates.
          </li>
        </ul>
      </div>
    </div>

    <!-- Education History -->
    <hr class="border-t border-gray-400 my-6 mx-auto w-full" />

    <div></div>
  </div>
</template>
