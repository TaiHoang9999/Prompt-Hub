<script setup></script>

<template>
        <header class="bg-white">
                <nav
                        class="flex justify-between items-center bg-[#F9FAFB] px-[16px] py-[14px] border-t-4 border-[#CDE200]">
                        <div>
                                <img class="" src="../assets/img/Logo.svg" alt="OnlyPromptsLogo" />
                        </div>
                        <div class="">
                                <ul
                                        class="flex items-center gap-[4vw] text-[16px] text-[#161C24] font-[600] leading-[24px]">
                                        <li>
                                                <a href="">Why us</a>
                                        </li>
                                        <li>
                                                <a href="">Our product</a>
                                        </li>
                                        <li>
                                                <a href="">Blog</a>
                                        </li>
                                </ul>
                        </div>

                        <div class="flex justify-between items-center gap-[8px]">
                                <button
                                        class="text-[13px] leading-5 px-[4px] py-[8px] border-[1px] border-solid border-[#637381] rounded-[4px]">
                                        Explore new prompts
                                </button>
                                <button
                                        class="bg-[#CDE200] text-[#161C24] text-[13px] leading-5 px-[4px] py-[8px] rounded-[4px]">
                                        Access my prompts
                                </button>
                        </div>
                </nav>
        </header>
</template>

<style scoped>
header {
        height: 56px;
}

header>nav,
header>div,
header>ul,
header>li {
        height: 100%;
}

a {
        position: relative;
}


a::after {
        position: absolute;
        content: "";
        width: 100%;
        height: 2px;
        background-color: red;
        left: 0;
        bottom: 0;
        transform: scaleX(1);
}
</style>
