<script setup>
import NavigationBar from "./NavigationBar.vue"
</script>

<template>
        <NavigationBar />
        <section>
                <div class="max-w-[1160px] mx-auto flex justify-between items-center flex-col mt-[40px]">
                        <h1 class="text-[#161C24] text-[64px] font-[700] leading-[80px]">One time credit</h1>
                        <p class="text-[14px] leading - [20px] text-[#212B36] pt-[8px]">Top up your account with
                                additional AI
                                credits and keep your tasks running smoothly.</p>
                </div>
                <div>5</div>
                <div class="max-w-[1160px] mx-auto flex justify-between items-center gap-5 mt-[40px]">
                        <div>
                                <span class="text-[#454F5B] text-[16px] leading-[24px] font-[600]">1000 credits</span>
                                <div class="flex justify-between items-center">
                                        <div class="flex justify-between items-center">
                                                <span>$</span>
                                                <span class="text-[#161C24] text-[40px] font-[700]">5</span>
                                        </div>
                                        <button
                                                class="text-[#454F5B] text-[16px] leading-[24px] font-[600]">Purchase</button>
                                </div>
                        </div>

                        <div>
                                <span>1000 credits</span>
                                <div class="flex justify-between items-center">
                                        <span>$5</span>
                                        <button>Purchase</button>
                                </div>
                        </div>


                        <div>
                                <span>1000 credits</span>
                                <div>
                                        <span>$5</span>
                                        <button>Purchase</button>
                                </div>
                        </div>
                </div>



                <div class="flex space-x-4 p-4">
                        <div class="border border-muted rounded-lg p-4 w-64 bg-card">
                                <h2 class="text-lg font-semibold">10,000 credits</h2>
                                <div class="text-4xl font-bold mt-2">$39</div>
                                <button class="bg-muted text-muted-foreground mt-4 py-2 px-4 rounded cursor-not-allowed"
                                        disabled>Purchase</button>
                        </div>
                </div>

        </section>

</template>

<style scoped></style>
