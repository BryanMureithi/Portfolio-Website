<template>
    <!--Navigation Bar-->
    <header class="header shadow-md">
        <!--Logo-->
        <a href="../App.vue">
          <img src="../assets/logo.png" alt="Logo" class="logo">
        </a>
        <nav>
            <div class="hidden w-full md:block md:w-auto" id="navbar-default">
                <ul class="flex flex-row items-center space-x-12">
                    <li class="text-[#1B263B] text-sm hover:text-[#415A77]">
                        <a href="../App.vue" class="block">Home</a>
                    </li>
                    <li class="text-[#1B263B] text-sm hover:text-[#415A77]">
                        <a href="#about" class="block">About Me</a>
                    </li>
                    <li class="text-[#1B263B] text-sm hover:text-[#415A77]">
                        <a href="#services" class="block">Services</a>
                    </li>
                    <li class="text-[#1B263B] text-sm hover:text-[#415A77]">
                        <a href="#portfolio" class="block">Portfolio</a>
                    </li>
                    <li class="text-[#1B263B] text-sm hover:text-[#415A77]">
                        <a href="#Home" class="block">Contact Me</a>
                    </li>
                    <a href="#contactUs" class="block bg-[#1B263B] hover:bg-[#415A77] text-[#E0E1DD] text-xs px-3 py-2">START A PROJECT</a>
                    <box-icon name='menu' class="toggle-icon"></box-icon>
                </ul>
            </div>
        </nav>
    </header>
</template>



<script>
export default {
    name: 'NavBar',
}
</script>

<style>
.header{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0px 45px;
}
.logo{
    width: 14em;
    height: 5.5em;
}

.toggle-icon{
    display: none;
}

</style>