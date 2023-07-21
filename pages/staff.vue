<template>
    <section class="w-full bg-center bg-cover min-h-screen relative" style="background-image: url('/staff.jpg');">
        <div class="absolute top-0 left-0 h-full w-full bg-dark/60 backdrop-blur-sm"></div>
        <div class="relative z-10 max-w-5xl m-auto pt-[140px] px-4">
            <h1 class="text-5xl text-white text-center 480px:text-4xl">Our Staff Members</h1>
            <div class="flex justify-center mt-5 mb-5">
                <div class="grid grid-cols-2 gap-12 text-white w-fit 550px:grid-cols-1">
                    <div class="bg-black p-6 rounded-lg relative group">
                        <span class="absolute top-2 rounded-sm font-semibold left-2 p-2 text-sm px-3 bg-rust">Founder/Owner</span>
                        <img class="mb-5 rounded-md group-hover:scale-125 transition-all" width="200" height="200" src="https://media.tenor.com/kupwOBwolcIAAAAC/hyper-gamer.gif">
                        <div class="info">
                            <h2 class="text-center text-xl mb-3">UnknownGamer</h2>
                            <div class="flex text-md items-center justify-center">
                                <Icon class="mr-2" name="logos:discord-icon" />
                                <span class="text-sm">eliteunknowngamer</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-black p-6 rounded-lg relative group">
                        <span class="absolute top-2 rounded-sm font-semibold left-2 p-2 text-sm px-3 bg-rust">Co-Owner</span>
                        <img class="mb-5 rounded-md group-hover:scale-125 transition-all" width="200" height="200" src="https://cdn.akamai.steamstatic.com/steamcommunity/public/images/items/386180/e47273b62284f3ab2e2b9b15c89607c8c1d4dd16.gif">
                        <div class="info">
                            <h2 class="text-center text-xl mb-3">GrimKngCobra</h2>
                            <div class="flex text-md items-center justify-center">
                                <Icon class="mr-2" name="logos:discord-icon" />
                                <span class="text-sm">grimkngcobra</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="grid grid-cols-1 gap-12 text-white w-fit m-auto 550px:grid-cols-1">
                <div class="bg-black p-6 rounded-lg relative group">
                    <span class="absolute top-2 rounded-sm font-semibold left-2 p-2 text-sm px-3 bg-rust">Developer</span>
                    <img class="mb-5 rounded-md group-hover:scale-125 transition-all" width="200" height="200" src="https://avatars.akamai.steamstatic.com/5d9378ab988f5ca6842d7e6f9c71e02b23928f21_full.jpg">
                    <div class="info">
                        <h2 class="text-center text-xl mb-3">iLoBBer</h2>
                        <div class="flex text-md items-center justify-center">
                            <Icon class="mr-2" name="logos:discord-icon" />
                            <span class="text-sm">ilobber</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-black p-6 rounded-lg relative group">
                        <span class="absolute top-2 rounded-sm font-semibold left-2 p-2 text-sm px-3 bg-rust">Head Admin</span>
                        <img class="mb-5 rounded-md group-hover:scale-125 transition-all" width="200" height="200" src="https://media.tenor.com/jdcvq2cpcb0AAAAC/grateful-dead-rainbow.gif">
                        <div class="info">
                            <h2 class="text-center text-xl mb-3">GratefulDead</h2>
                            <div class="flex text-md items-center justify-center">
                                <Icon class="mr-2" name="logos:discord-icon" />
                                <span class="text-sm">gratefuldead</span>
                                </div>
                    </div>
                </div>
            </div>
        </div
    </section>
</template>

<script setup>
    useSeoMeta({
        title: "Staff Memebers — The Sanctuary",
        ogTitle: 'Staff Memebers — The Sanctuary',
        description: "Welcome to The Sanctuary Rust server's staff page official website. Contact Owner of the server in same of any problem.",
        ogDescription: "Welcome to The Sanctuary Rust server's staff page official website. Contact Owner of the server in same of any problem.",
        ogImage: 'https://cdn.discordapp.com/attachments/1130104696066015342/1130479487625216120/cut512x277.gif',
        twitterCard: 'summary_large_image',
    });

</script>
