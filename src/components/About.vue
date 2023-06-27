<template>
    <section id="about" class="mt-16 mb-16 mx-auto max-w-screen-xl sm:py-16">
        <div class="">
            <h2 class="text-xl font-semibold text-[#1B263B]">ABOUT ME</h2>
            <p class="font-semibold text-[#415A77]">Read about my history.</p>
        </div>
        <div class="mb-12 shadow-sm">
            <section class="bg-[#E0E1DD]">
                <div class="grid max-w-screen-xl px-4 py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-16 lg:grid-cols-12">
                    <div class="hidden lg:mt-0 lg:col-span-5 lg:flex mr-12">
                       <img src="../assets/avatar.jpg" alt="" class="w-full">
                    </div>
                    <div class="mr-auto place-self-center lg:col-span-7">
                       <p class="text-md text-[#415A77] w-12/12 leading-loose italic">I am currently a student at the Catholic University of Eastern Africa, pursuing
                         a Bachelor's degree in Computer Science. My coursework has provided me with a strong
                          foundation in programming languages such as Java and Python, as well as exposure to databases,
                           software engineering, and computer networks. Additionally, I have gained experience through
                            internships and projects, such as developing a web-based application for a local business. Through these experiences, I have honed my problem-solving skills,
                              ability to work in a team, and ability to adapt to new technologies. Furthermore, I am skilled
                               in UI/UX design, front-end web development, which has helped me to create elegant and user-friendly web applications.
                                I am excited to continue my education and to apply my knowledge and skills in the field of computer science.</p>
                    </div>                
                </div>
            </section>
        </div>
        <div class="flex justify-between gap-6">
            <div class="sm:ml-8">
                <h2 class="text-2xl font-semibold text-[#1B263B]">Experience</h2>
                <ol class="relative border-l border-gray-700 mt-12">                  
                    <li class="mb-10 ml-4 hover:bg-[#c7c8c4] p-5">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">May 2021 - August 2021</time>
                        <h3 class="text-lg font-semibold text-gray-900">Ralphowino Consulting</h3>
                        <h3 class="font-semi-bold text-gray-700">Intern</h3>

                        <p class="mb-4 text-base w-9/12 font-normal text-[#415A77]">Trained on UI/UX design by creating wireframes and designs using Figma and Adobe XD.
                            Also created projects using Vue JS, Tailwind CSS and GraphQL. Trained on how to debug and correct errors in different projects. Learned how 
                            to use user stories and pseudocodes to help in developing a system.
                        </p>
                    </li>
                    <li class="mb-10 ml-4 hover:bg-[#c7c8c4] p-5">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">September 2022 to present</time>
                        <h3 class="text-lg font-semibold text-gray-900">Fourth Profile</h3>
                        <h3 class="font-semi-bold text-gray-700">UI/UX designer & Front-end developer</h3>
                        <p class="text-base w-9/12 font-normal text-[#415A77]">Created designs for different elements needed for the project on Figma.
                            Implemented the Figma designs using Vue JS and Tailwind CSS.
                        </p>
                    </li>
                    <li class="ml-4 mb-8 hover:bg-[#c7c8c4] p-5">
                        <div class="absolute w-3 h-3 bg-[#1B263B] rounded-full mt-1.5 -left-1.5 border border-white"></div>
                        <time class="mb-1 text-sm font-normal leading-none text-[#415A77]">2 May 2023 - 31 July 2023</time>
                        <h3 class="text-lg font-semibold text-gray-900">Kenya Power and Lighting Company</h3>
                        <h3 class="font-semi-bold text-gray-700">ICT Intern</h3>
                        <p class="text-base w-9/12 font-normal text-[#415A77]">Learnt about the Network Operations Centre(NOC) where all networks, servers
                            routers, switches and the data centre are monitored. Did ICT support tasks where I helped out staff with issues concerning 
                            computer hardware or software. Visited a data center which has the servers containing data crucial to the company.
                        </p>
                    </li>
                </ol>
            </div>
        </div>
        
    </section>
</template>

<script>
export default{
    name:"AboutMain"
}
</script>

<style>
.image{
    width: 100%;
    height: 500px;
    background-color: #1B263B;
    border-radius: 5px;

}
.image img{
    max-width: 100%;
    height: auto;
}
</style>