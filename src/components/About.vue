<template>
    <section id="about" class="mt-16 px-12 mb-16 shadow-sm">
        <div class="">
            <h2 class="text-xl font-semibold text-[#1B263B]">ABOUT ME</h2>
            <p class="font-semibold text-[#415A77]">Read about my history.</p>
        </div>
        <div class="mb-12 shadow-sm">
            <section class="bg-[#E0E1DD]">
                <div class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12">
                    <div class="hidden lg:mt-0 lg:col-span-5 lg:flex mr-12">
                       <img src="" alt="" class="w-full">
                    </div>
                    <div class="mr-auto place-self-center lg:col-span-7">
                       <p class="text-md text-[#415A77] w-12/12 leading-loose">I am currently a student at the Catholic University of Eastern Africa, pursuing
                         a Bachelor's degree in Computer Science. My coursework has provided me with a strong
                          foundation in programming languages such as Java and Python, as well as exposure to databases,
                           software engineering, and computer networks. Additionally, I have gained experience through
                            internships and projects, such as developing a web-based application for a local business or
                             participating in hackathons. Through these experiences, I have honed my problem-solving skills,
                              ability to work in a team, and ability to adapt to new technologies. Furthermore, I am skilled
                               in UI/UX design, front-end web development, which has helped me to create elegant and user-friendly web applications.
                                I am excited to continue my education and to apply my knowledge and skills in the field of computer science.</p>
                    </div>                
                </div>
            </section>
        </div>
        <div class="flex flex-row justify-between">
            <div>
                <h2 class="text-2xl font-semibold text-[#1B263B]">Qualifications</h2>
                <ol class="relative border-l border-gray-700 mt-12">
                    <li class="mb-10 ml-4">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">September 2020 - April 2024</time>
                        <h3 class="text-lg font-semibold text-gray-900">Catholic University of Eastern Africa</h3>
                        <p class="mb-4 text-base font-normal text-[#415A77]">Bachelors of Science in Computer Science</p>
                    </li>                  
                    <li class="mb-10 ml-4">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">Feb 2016 - December 2019</time>
                        <h3 class="text-lg font-semibold text-gray-900">High School</h3>
                        <p class="mb-4 text-base font-normal text-[#415A77]">Kenya Certificate of Secondary Education ( K.C.S.E )</p>                        
                    </li>
                </ol>
            </div>
            <div class="sm:ml-8">
                <h2 class="text-2xl font-semibold text-[#1B263B]">Experience</h2>
                <ol class="relative border-l border-gray-700 mt-12">                  
                    <li class="mb-10 ml-4">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">May 2021 - August 2021</time>
                        <h3 class="text-lg font-semibold text-gray-900">Ralphowino Consulting</h3>
                        <p class="mb-4 text-base font-normal text-[#415A77]">Gained skills in UI/UX design, front-end Web Development and Project Management.</p>
                    </li>
                    <li class="mb-10 ml-4">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">September 2022 to present</time>
                        <h3 class="text-lg font-semibold text-gray-900">Fourth Profile</h3>
                        <p class="text-base font-normal text-[#415A77]">In charge of creating and implementing designs on different UI elements using Figma and Vue JS.</p>
                    </li>
                    <li class="ml-4 mb-8">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">April 2022 - Present</time>
                        <h3 class="text-lg font-semibold text-gray-900">Freelance</h3>
                        <p class="text-base font-normal text-[#415A77]">Doing projects for different clients from the internet.</p>
                    </li>
                </ol>
            </div>
        </div>
        
    </section>
</template>

<script>


export default{
    name: 'AboutMain'
}
</script>