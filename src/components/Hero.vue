<template>
        <!--Hero Section-->
        <!--Used grids for this section to separate text from the image-->
        <div class="grid grid-cols-4 gap-0 px-12 shadow-sm">
            <div class="col-start-1 col-span-2 p-6 mt-16 pt-10">
                <h1 class="text-[#1B263B] w-96 font-semibold text-3xl">I create experiences that make people's lives simple.</h1>
                <p class="mt-4 text-md w-8/12 text-[#415A77]">Hi, I’m Bryan, an aspiring Data Scientist and Front-end Web Developer. I help fast growing startups to launch and grow their brands.</p>
                <div class="mt-12 flex flex-row items-center space-x-8">
                    <a href="#contactUs" class="bg-[#1B263B] hover:bg-[#415A77] text-[#E0E1DD] text-sm px-5 py-3">RESUME</a>
                    <a href="#contactUs" class="bg-transparent text-[#1B263B] text-sm p-3 border border-gray-500 hover:bg-[#1B263B] hover:text-[#E0E1DD]">VIEW PROJECTS</a>
                </div>
                <div class="mt-12 flex space-x-5">
                    <a href="https://twitter.com/BryanMurei">
                        <box-icon type='logo' name='twitter' class="w-10 h-10"></box-icon>
                    </a>
                    <a href="https://www.linkedin.com/in/bryan-mureithi-237b33225/">
                        <box-icon name='linkedin' type='logo' class="w-8 h-8"></box-icon>
                    </a>
                    <a href="https://github.com/BryanMureithi">
                        <box-icon name='github' type='logo' class="w-8 h-8"></box-icon>
                    </a>
                    
                </div>
            </div>
            <div class="col-start-3 col-span-2">
                <!--Hero Image-->
                <div class="pb-8">
                    <img src="../assets/coding.svg" class="dev" alt="Programmer">
                </div>
            </div>
        </div>
</template>

<script>


export default{
    name:'HeroMain'
}
</script>

<style>
.dev{
    max-width: 100%;
    height: auto;
}
</style>