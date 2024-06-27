<script setup>
</script>

<template>
        <NavigationBar />

        <section class="pt-[120px]">
                <div class="max-w-[1160px] mx-auto flex justify-between items-center flex-col mt-[40px]">
                        <h1 class="text-[#161C24] text-[64px] font-[700] leading-[80px]">
                                Frequently Asked Questions
                        </h1>
                        <p class="text-[14px] leading - [20px] text-[#212B36] pt-[8px]">
                                Top up your account with additional AI credits and keep your tasks
                                running smoothly.
                        </p>
                </div>

                <div class="max-w-[1160px] mx-auto flex justify-center items-center gap-5 mt-[40px] total">
                        <div class="flex justify-center items-center flex-col hehe">
                                <div
                                        class="flex justify-between items-center flex-col w-full h-[120px] p-[16px] pricing">
                                        <span
                                                class="text-[#454F5B] text-[16px] leading-[24px] font-[600] self-start w-full">1000
                                                credits</span>
                                        <div class="flex justify-between items-center self-start w-full">
                                                <div class="flex items-center">
                                                        <span class="self-start font-[700]">$</span>
                                                        <span
                                                                class="text-[#161C24] text-[40px] font-[700] leading-[0.9]">5</span>
                                                </div>
                                                <button
                                                        class="text-[#C4CDD5] text-[16px] leading-[24px] font-[600] bg-[#F4F6F8] py-[16px] px-[24px]">
                                                        Purchase
                                                </button>
                                        </div>
                                </div>
                        </div>

                        <div class="flex justify-center items-center flex-col hehe">
                                <div
                                        class="flex justify-between items-center flex-col w-full h-[120px] p-[16px] pricing">
                                        <span
                                                class="text-[#454F5B] text-[16px] leading-[24px] font-[600] self-start w-full">1000
                                                credits</span>
                                        <div class="flex justify-between items-center self-start w-full">
                                                <div class="flex items-center">
                                                        <span class="self-start font-[700]">$</span>
                                                        <span
                                                                class="text-[#161C24] text-[40px] font-[700] leading-[0.9]">5</span>
                                                </div>
                                                <button
                                                        class="text-[#C4CDD5] text-[16px] leading-[24px] font-[600] bg-[#F4F6F8] py-[16px] px-[24px]">
                                                        Purchase
                                                </button>
                                        </div>
                                </div>
                        </div>

                        <div class="flex justify-center items-center flex-col hehe">
                                <div
                                        class="flex justify-between items-center flex-col w-full h-[120px] p-[16px] pricing">
                                        <span
                                                class="text-[#454F5B] text-[16px] leading-[24px] font-[600] self-start w-full">1000
                                                credits</span>
                                        <div class="flex justify-between items-center self-start w-full">
                                                <div class="flex items-center">
                                                        <span class="self-start font-[700]">$</span>
                                                        <span
                                                                class="text-[#161C24] text-[40px] font-[700] leading-[0.9]">5s</span>
                                                </div>
                                                <button
                                                        class="text-[#C4CDD5] text-[16px] leading-[24px] font-[600] bg-[#F4F6F8] py-[16px] px-[24px]">
                                                        Purchase
                                                </button>
                                        </div>
                                </div>
                        </div>
                </div>
        </section>


</template>

<style scoped>
.hehe {
        width: calc(33.33% - 20px);
        margin-left: 20px;
}

.pricing {
        border: 2px solid #161c24;
        border-radius: 4px;
}

.pricing:hover {
        box-shadow: 5px 8px 0px 0px #000000;
}
</style>
