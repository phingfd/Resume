<template>
  <div class="bg-gray-100 p-4 w-full">
    <!-- Profile Image Centered -->
    <div class="relative flex justify-center mb-4">
      <img
        src="/images/Profile.png"
        alt="Profile"
        class="h-80 w-80 object-cover rounded-full shadow-md"
      />
      <button
        @click="printDocument"
        class="absolute top-0 right-96 mt-2 mr-2 px-4 py-2 bg-blue-600 text-white rounded-lg shadow hover:bg-blue-700 transition no-print"
      >
        Print SV
      </button>
    </div>

    <div class="bg-gray-100 p-4 w-full">
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
          <p>
            <strong>Address:</strong> Block 13 Lot 9, Cerritos Camella Homes
          </p>
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
          class="text-left text-xl font-bold border-b border-gray-300 text-gray-800 mb-4 max-w-5xl mx-auto"
        >
          Personal Information
        </div>

        <div class="max-w-5xl mx-auto space-y-2">
          <div class="flex">
            <span class="font-semibold mr-2">Date of Birth:</span>
            <p class="text-gray-600">02/06/1999</p>
          </div>
          <div class="flex">
            <span class="font-semibold mr-2">Marital Status:</span>
            <p class="text-gray-600">Single</p>
          </div>
          <div class="flex">
            <span class="font-semibold mr-2">Nationality:</span>
            <p class="text-gray-600">Filipino</p>
          </div>
          <div class="flex">
            <span class="font-semibold mr-2">Religion:</span>
            <p class="text-gray-600">Born Again</p>
          </div>
          <div class="flex">
            <span class="font-semibold mr-2">Weight:</span>
            <p class="text-gray-600">68kg</p>
          </div>
          <div class="flex">
            <span class="font-semibold mr-2">height:</span>
            <p class="text-gray-600">162cm</p>
          </div>
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
          </div>

          <!-- Icon Row -->
          <div
            class="flex flex-wrap justify-center md:justify-start gap-4 mt-5"
          >
            <img src="/images/skill-icons--html.png" class="w-8 h-8" />
            <img src="/images/skill-icons--javascript.png" class="w-8 h-8" />
            <img src="/images/skill-icons--vuejs-dark.png" class="w-8 h-8" />
            <img src="/images/skill-icons--nuxtjs-dark.png" class="w-8 h-8" />
            <img
              src="/images/skill-icons--tailwindcss-dark.png"
              class="w-8 h-8"
            />
            <img src="/images/skill-icons--php-dark.png" class="w-8 h-8" />
            <img src="/images/skill-icons--mysql-dark.png" class="w-8 h-8" />
            <img src="/images/skill-icons--vscode-dark.png" class="w-8 h-8" />
            <img src="/images/skill-icons--github-dark.png" class="w-8 h-8" />
            <img src="/images/skill-icons--docker.png" class="w-8 h-8" />
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
                  seek solutions through research, debugging, and asking the
                  right questions.
                </li>
                <li>
                  Clear Communication: Comfortable explaining ideas and asking
                  for clarification when needed to ensure shared understanding.
                </li>
                <li>
                  User-Centered Thinking: Gaining experience in translating
                  basic requirements into user-friendly features.
                </li>
                <li>
                  Time Awareness: Learning to prioritize tasks and meet
                  deadlines with guidance and planning.
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

      <div class="max-w-5xl mx-auto py-5 text-sm text-gray-800 font-sans">
        <h2 class="text-2xl font-bold border-b border-gray-300 pb-2 mb-6">
          Education History
        </h2>
        <div class="mb-6">
          <div class="flex justify-between items-start">
            <div>
              <h2 class="text-base font-bold">
                Bachelor of Science in Information Technology
              </h2>
              <p class="text-gray-600 text-sm">
                STI College General Santos City
              </p>
            </div>
            <span>2019 - 2023</span>
          </div>
        </div>
        <div class="mb-6">
          <div class="flex justify-between items-start">
            <div>
              <h2 class="text-base font-bold">Senior High Grade</h2>
              <p class="text-gray-600 text-sm">Labangal General Santos City</p>
            </div>
            <span>2017 - 2019</span>
          </div>
        </div>
        <div class="mb-6">
          <div class="flex justify-between items-start">
            <div>
              <h2 class="text-base font-bold">Secondary Education</h2>
              <p class="text-gray-600 text-sm">Lawang Bato Valenzuela City</p>
            </div>
            <span>2013 - 2017</span>
          </div>
        </div>
        <div class="mb-6">
          <div class="flex justify-between items-start">
            <div>
              <h2 class="text-base font-bold">Primary Education</h2>
              <p class="text-gray-600 text-sm">Balunto Elementary School</p>
            </div>
            <span>2007 - 2013 changes</span>
          </div>
        </div>
      </div>

      <!-- Preference -->
      <hr class="border-t border-gray-400 my-6 mx-auto w-full" />
      <div class="max-w-5xl mx-auto py-5 text-sm text-gray-800 font-sans">
        <h2 class="text-2xl font-bold border-b border-gray-300 pb-2 mb-6">
          References
        </h2>
        <div class="mb-6">
          <div class="flex justify-between items-start">
            <div>
              <h2 class="text-base font-bold border-b border-gray-900">
                Dr. Annie Yabut
              </h2>
              <p class="text-gray-600 text-sm">Hospital Administrator</p>
              <p class="text-gray-600 text-sm">Dadiangas Medical Center</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- clone -->
  <div class="bg-gray-100 p-4 w-full hidden" style="width: 8.5in; height: 13in">
    <!-- Profile Image Centered -->
    <div class="relative flex justify-center mb-4">
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

    <!-- Personal Information -->
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
        </div>

        <!-- Icon Row -->
        <div class="flex flex-wrap justify-center md:justify-start gap-4 mt-5">
          <img src="/images/skill-icons--html.png" class="w-8 h-8" />
          <img src="/images/skill-icons--javascript.png" class="w-8 h-8" />
          <img src="/images/skill-icons--vuejs-dark.png" class="w-8 h-8" />
          <img src="/images/skill-icons--nuxtjs-dark.png" class="w-8 h-8" />
          <img
            src="/images/skill-icons--tailwindcss-dark.png"
            class="w-8 h-8"
          />
          <img src="/images/skill-icons--php-dark.png" class="w-8 h-8" />
          <img src="/images/skill-icons--mysql-dark.png" class="w-8 h-8" />
          <img src="/images/skill-icons--vscode-dark.png" class="w-8 h-8" />
          <img src="/images/skill-icons--github-dark.png" class="w-8 h-8" />
          <img src="/images/skill-icons--docker.png" class="w-8 h-8" />
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
      <h2 class="work-section text-2xl font-bold border-b border-gray-300 pb-2 mb-6">
        Work Experience
      </h2>

      <!-- Work Entry 1 -->
      <div class="mb-6 work-entry">
        <div class="flex justify-between items-start">
          <div>
            <h3 class="text-base font-semibold">Junior Programmer</h3>
            <p class="text-gray-600">Dadiangas Medical Center. (Onsite)</p>
          </div>
          <span class="text-gray-500 text-xs">August 2024 - Present</span>
        </div>
        <ul class="list-disc list-inside mt-2 text-gray-700 leading-relaxed">
          <li>
            Developed responsive web pages using HTML, CSS, and JavaScript.
          </li>
          <li>Built interactive UI components with Vue.js and Inertia.js.</li>
          <li>Connected frontend features to Laravel backend and APIs.</li>
          <li>Worked with MySQL databases for data handling.</li>
          <li>Used Sourcetree for version control and collaboration.</li>
          <li>Gained experience with Docker for app containerization.</li>
        </ul>
      </div>

      <!-- Work Entry 2 -->
      <div class="mb-6 work-entry">
        <div class="flex justify-between items-start">
          <div>
            <h3 class="text-base font-semibold">
              Software Support / Technical Support / Web Developer / OJT
            </h3>
            <p class="text-gray-600">Dadiangas Medical Center. (Onsite)</p>
          </div>
          <span class="text-gray-500 text-xs">March 2023 - July 2023</span>
        </div>
        <ul class="list-disc list-inside mt-2 text-gray-700 leading-relaxed">
          <li>Encoded and organized data accurately.</li>
          <li>Performed inventory adjustments.</li>
          <li>Maintained simple websites using HTML/CSS/JS.</li>
          <li>Provided basic tech support and printer networking.</li>
          <li>Resolved Windows system issues and did updates.</li>
        </ul>
      </div>
    </div>

    <!-- Education History -->
    <hr class="border-t border-gray-400 my-6 mx-auto w-full" />

    <div class="max-w-5xl mx-auto py-5 text-sm text-gray-800 font-sans">
      <h2 class="text-2xl font-bold border-b border-gray-300 pb-2 mb-6">
        Education History
      </h2>
      <div class="mb-6">
        <div class="flex justify-between items-start">
          <div>
            <h2 class="text-base font-bold">
              Bachelor of Science in Information Technology
            </h2>
            <p class="text-gray-600 text-sm">STI College General Santos City</p>
          </div>
          <span>2019 - 2023</span>
        </div>
      </div>
      <div class="mb-6">
        <div class="flex justify-between items-start">
          <div>
            <h2 class="text-base font-bold">Senior High Grade</h2>
            <p class="text-gray-600 text-sm">Labangal General Santos City</p>
          </div>
          <span>2017 - 2019</span>
        </div>
      </div>
      <div class="mb-6">
        <div class="flex justify-between items-start">
          <div>
            <h2 class="text-base font-bold">Secondary Education</h2>
            <p class="text-gray-600 text-sm">Lawang Bato Valenzuela City</p>
          </div>
          <span>2013 - 2017</span>
        </div>
      </div>
      <div class="mb-6">
        <div class="flex justify-between items-start">
          <div>
            <h2 class="text-base font-bold">Primary Education</h2>
            <p class="text-gray-600 text-sm">Balunto Elementary School</p>
          </div>
          <span>2007 - 2013 changes</span>
        </div>
      </div>
    </div>

    <!-- Preference -->
    <hr class="border-t border-gray-400 my-6 mx-auto w-full" />
    <div class="max-w-5xl mx-auto py-5 text-sm text-gray-800 font-sans">
      <h2 class="text-2xl font-bold border-b border-gray-300 pb-2 mb-6">
        References
      </h2>
      <div class="mb-6">
        <div class="flex justify-between items-start">
          <div>
            <h2 class="text-base font-bold border-b border-gray-900">
              Dr. Annie Yabut
            </h2>
            <p class="text-gray-600 text-sm">Hospital Administrator</p>
            <p class="text-gray-600 text-sm">Dadiangas Medical Center</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
function printDocument() {
  // Select the hidden section you want to print
  const container = document
    .querySelector("div.bg-gray-100.hidden")
    .cloneNode(true);

  // Fix Soft Skills section formatting for print
  const softSkillsSection = container.querySelector(
    ".text-xl.text-gray-900.mt-8"
  );
  if (softSkillsSection) {
    softSkillsSection.classList.add("space-y-2"); // Adjust spacing between soft skills items
  }

  // Open a new window to print
  const printWindow = window.open("", "", "width=850,height=1300");

  printWindow.document.write(`
  
        <style>
          @page {
            size: 8.5in 13in;
            margin: 0.5in;
          }

          body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            -webkit-print-color-adjust: exact;
            print-color-adjust: exact;
          }

          .print-container {
            width: 100%;
            max-width: 8in;
            margin: 0 auto;
            padding: 0.5in;
          }

          img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
          }

          .h-80.w-80 {
            width: 200px !important;
            height: 200px !important;
            object-fit: cover;
            border-radius: 9999px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
          }

          /* Skill icons */
          .flex-wrap img {
            display: inline-block;
            width: 32px;
            height: 32px;
          }

          /* Space the icons evenly in print */
          .flex-wrap {
            display: flex;
            justify-content: space-evenly;
            flex-wrap: wrap;
          }

          /* Soft Skills Section Formatting */
          .text-xl.text-gray-900.mt-8 {
            margin-top: 20px;
            font-size: 16px;
            font-weight: 600;
          }

          .list-disc {
            margin-left: 20px;
            padding-left: 5px;
          }

          .work-entry {
            page-break-inside: avoid;
            break-inside: avoid;
            margin-bottom: 1rem;
          }
          .work-section {
            page-break-before: always;
          }

        </style>
      <body>
        <div class="print-container">
          ${container.outerHTML}
        </div>
      </body>
  `);

  // Ensure the print window content is ready before printing
  printWindow.document.close();
  printWindow.onload = () => {
    printWindow.focus(); // Focus on the new window
    printWindow.print(); // Trigger the print dialog
    printWindow.close(); // Close the print window after printing
  };
  
}
</script>
