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
            <div>
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
                                                >During my bachelors, I
                                                discovered a passion and talent
                                                for software, which made me
                                                switch to Computer Science.</span
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
                        <li class="flex flex-row justify-between gap-4">
                            <span class="font-bold">Het Baarnsch Lyceum</span
                            ><span>vwo NT&NG gymnasium: 8.6/10 average</span
                            ><span>2012-2018</span>
                        </li>
                    </ul>
                </section>
                <section class="mb-8">
                    <h2 class="text-2xl font-semibold mb-4">Projects</h2>
                    <ul>

                    </ul>
                </section>
            </div>

            <section class="mb-8">
                <h2 class="text-2xl font-semibold">Experience</h2>
                <ul>
                    <li class="text-sm">
                        <div class="float-left mr-4 text-md">
                            <div class="font-bold mb-1 mt-1">SimplyMeals</div>
                            <div class="text-xs">
                                Software Developer <br />& Co-Founder
                            </div>
                            <div class="text-xs italic">2023-present</div>
                        </div>
                        <p>
                            At <a
                                href="https://simplymeals.nl"
                                class="text-blue-600"
                                target="_blank"
                                rel="noopener noreferrer">SimplyMeals</a
                            > I was a part-time co-founder and set up their website,
                            database, registration and payment system from scratch
                            in a team of 2. We built a full-stack application using
                            SvelteKit, where I was primarily responsible for the
                            business logic and backend components. With little time
                            and money, we had to focus on the commercial and operational
                            priorities. The system allowed hosts to order group meals,
                            which the guests could then register and pay for. SimplyMeals
                            serves nearly 2,000 meals per month.
                        </p>
                        <div class="mt-1 text-xs">
                            Technologies: <em
                                >TypeScript, Svelte, PostgreSQL, Docker, GitHub
                                Actions</em
                            >
                        </div>
                    </li>
                    <li class="text-sm">
                        <div class="float-left mr-4 text-md">
                            <div class="font-bold mb-1 mt-1">
                                D.S.A.V. Dodeka
                            </div>
                            <div class="text-xs">
                                .ComCom Member <br />& Chair (volunteer)
                            </div>
                            <div class="text-xs italic">2021-present</div>
                        </div>
                        <p>
                            At D.S.A.V. Dodeka, the 150-member student athletics
                            association in Delft, I was a member and later chair
                            of the commission responsible for developing and
                            maintaining the website. After I joined, I was
                            primarily responsible for developing a login system
                            and backend, which we developed in Python. The login
                            and authorization employs JWTs and was built from
                            scratch to the OAuth 2.0 specification.
                        </p>
                        <div class="mt-1 text-xs">
                            Technologies: <em
                                >Python, JavaScript, FastAPI, OAuth 2.0 and
                                JWTs, PostgreSQL, React, Docker Compose,
                                encryption</em
                            >
                        </div>
                    </li>
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
