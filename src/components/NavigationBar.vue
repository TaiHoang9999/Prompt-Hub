<script setup></script>

<template>
        <header class="h-[56px] w-full border-t-4 border-[#CDE200]">
                <nav class=" max-w-[1476px] w-full flex justify-between items-center mx-auto px-[16px]">
                        <div class="h-full flex items-center">
                                <a href=" flex items-center  h-full">
                                        <img class="" src="../assets/img/Logo.svg" alt="OnlyPromptsLogo" />
                                </a>

                        </div>
                        <ul
                                class="menu-list flex items-center gap-[32px] text-[16px] text-[#161C24] font-[600] leading-[24px] h-full">
                                <li class="menu-item p-[16px] h-full">
                                        <a class="flex items-center justify-center h-full" href="">Why us</a>
                                </li>
                                <li class="menu-item p-[16px] h-full relative">
                                        <a class="flex items-center justify-center h-full relative product-link pr-[20px]"
                                                href="">Our product
                                        </a>

                                        <ul class="submenu bg-red absolute top-[56px] right-[-88px] w-[150px] overflow-y-auto flex flex-col  border-[1px] border-solid border-[#637381] rounded-[8px]">
                                                <li class="submenu-item text-[13px] text-[#637381]" ><a href="#" class =" leading-[20px]">Package of prompts</a></li>
                                                <li class="submenu-item text-[#637381] "><a href="#"  class =" leading-[20px]">Subscription plans</a></li>
                                                <li class="submenu-item text-[13px] text-[#161C24] "><a href="#"  class ="  leading-[20px]">One time AI credit</a></li>
                                        </ul>
                                </li>
                                <li class="menu-item p-[16px] h-full">
                                        <a class="flex items-center justify-center h-full" href="">Blog</a>
                                </li>
                        </ul>
                        <div class="flex justify-between items-center gap-[8px] h-full">
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
nav {
        height: calc(100% + 4px);
}

.menu-item:hover {
        border-bottom: 4px solid #161C24;
        transition: all 0.1s ease-in-out 0s;
}


.product-link::after{
        content:'';
        position: absolute;
        border: solid #161C24;
        border-width: 0px 1.8px 1.8px 0;
        right: 0px;
        top: calc(50%);
        transform: translateY(-50%) rotate(45deg);
        padding:4px;
}


.submenu-item {
        width: 100%;
        box-sizing: border-box;
        padding:0 15px 0 15px;
}

.submenu-item a {
        display: block;
        width: 100%;
        text-decoration: none;
        color: #637381;
}

.submenu-item a:hover {
        background-color: #f1f1f1;
        color: #161C24;
}
</style>
