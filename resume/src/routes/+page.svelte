<script>
    // let education = [
    //   {
    //     school: "University Name",
    //     degree: "Degree Name",
    //     year: "Graduation Year"
    //   },
    //   {
    //     school: "College Name",
    //     degree: "Degree Name",
    //     year: "Graduation Year"
    //   }
    // ];

    // let experience = [
    //   {
    //     company: "Company Name",
    //     position: "Job Title",
    //     period: "Start Date - End Date",
    //     description: "Job Description"
    //   },
    //   {
    //     company: "Another Company",
    //     position: "Another Job Title",
    //     period: "Start Date - End Date",
    //     description: "Job Description"
    //   }
    // ];

    // let projects = [
    //   {
    //     name: "Project Name",
    //     description: "Project Description",
    //     link: "https://projectlink.com"
    //   },
    //   {
    //     name: "Another Project",
    //     description: "Project Description",
    //     link: "https://projectlink.com"
    //   }
    // ];
</script>

<div class="bg-gray-600 h-[100vh]">
    <div
        class="bg-white w-[21.6cm] mx-auto invoice px-[1.25cm] pt-[0.75cm] h-[27.9cm]"
    >
        <header class="text-center">
            <h1 class="text-3xl font-bold">Tip ten Brink</h1>
        </header>

        <div class="grid grid-cols-[5fr_3fr] gap-6">
            <section class="">
                <h2 class="text-md font-semibold uppercase">Education</h2>
                <hr class="border-2 border-solid border-black" />
                <ul>
                    <li>
                        <div class="flex flex-row justify-between">
                            <span class="font-bold">TU Delft</span>
                            <span>Sept 2018-June 2025</span>
                        </div>
                        <ul>
                            <li>
                                <div>
                                    MSc Computer Science
                                    <div
                                        class="border border-solid border-black p-1 grid grid-cols-[2fr_1fr] text-sm"
                                    >
                                        <span
                                            >During my bachelors, I discovered a
                                            passion and talent for software,
                                            which made me switch to Computer
                                            Science.</span
                                        >
                                        <span>Hi</span>
                                    </div>
                                </div>
                            </li>
                            <li>Bridging Program Computer Science</li>
                            <li>BSc Applied Physics</li>
                            <li>BSc Applied Mathematics</li>
                        </ul>
                    </li>
                </ul>
            </section>

            <section class="mb-8">
                <h2 class="text-2xl font-semibold mb-4">Experience</h2>
                <ul>
                    <!-- {#each experience as exp}
          <li class="mb-4">
            <p class="text-xl font-medium">{exp.position} at {exp.company}</p>
            <p class="text-gray-600">{exp.period}</p>
            <p>{exp.description}</p>
          </li>
        {/each} -->
                </ul>
            </section>

            <section class="mb-8">
                <h2 class="text-2xl font-semibold mb-4">Projects</h2>
                <ul>
                    <!-- {#each projects as proj}
          <li class="mb-4">
            <p class="text-xl font-medium">
              <a href={proj.link} class="text-blue-500 hover:underline">{proj.name}</a>
            </p>
            <p>{proj.description}</p>
          </li>
        {/each} -->
                </ul>
            </section>
        </div>

        <section class="mb-8">
            <h2 class="text-2xl font-semibold">Competencies</h2>
            * I have a strong and broad academic background, with particularly well-developed
            mathematical skills. The world of mathematicians and physicists is also
            very different, giving me both the "engineering" but also "theoretical"
            mindset. These different worlds can also be seen within computer science,
            which includes both system builders and category theorists. My journey
            through these different worlds has given me a broad perspective on how
            to solve problems.
            <!-- EXAMPLES? -->
            * Throughout my bridging program and master degree, I learned the fundamentals
            of databases, compilers, functional programming, category theory,
        </section>
    </div>
</div>

<style>
    .invoice {
        print-color-adjust: exact;
        /* change the margins as you want them to be. */
    }
</style>
