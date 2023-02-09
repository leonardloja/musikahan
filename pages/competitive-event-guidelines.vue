<template>
    <div class="px-12 py-10 min-h-[90vh]">
        <h1
            class="text-5xl font-bold bg-gradient-to-t text-transparent inline-block bg-clip-text text-center from-[#ff853c] to-[#ffd440]">
            Competitive Event
            Guidelines</h1>
        <div class="mt-10">
            <div class="flex flex-row justify-between mt-2">
                <a href="/event-guidelines/FINAL-OFFICIAL-RONDAL-AWIT-COMPETITION-GUIDELINES.pdf"
                    class="un font-bold text-xl">
                    RONDAL-AWIT COMPETITION
                </a>
            </div>
            <div class="flex flex-row justify-between mt-2">
                <a href="/event-guidelines/FINAL-OFFICIAL-BARANGAY-MUSIKAHAN-COMPETITION-GUIDELINES.pdf"
                    class="un font-bold text-xl">
                    BARANGAY MUSIKAHAN COMPETITION
                </a>
            </div>
            <div class="flex flex-row justify-between mt-2">
                <a href="/event-guidelines/FINAL-OFFICIAL-HIMIG-HANDOG-CHORAL-COMPETITION-GUIDELINES.pdf"
                    class="un font-bold text-xl">
                    HIMIG HANDOG (Choral) COMPETITION
                </a>
            </div>
            <div class="flex flex-row justify-between mt-2">
                <a href="/event-guidelines/FINAL-OFFICIAL-MUSIKAHAN-BATTLE-OF-THE-BAND-COMPETITION-GUIDELINES.pdf"
                    class="un font-bold text-xl">
                    PASIKLABand SA MUSIKAHAN COMPETITION
                </a>
            </div>
            <div class="flex flex-row justify-between mt-2">
                <a href="/event-guidelines/FINAL-OFFICIAL-MUSIKAHAN-MUSIC-VIDEO-COMPETITION-GUIDELINES.pdf"
                    class="un font-bold text-xl">
                    MUSIKAHAN Music Video COMPETITION
                </a>
            </div>
            <div class="flex flex-row justify-between mt-2">
                <a href="/event-guidelines/FINAL-OFFICIAL-RONDAL-AWIT-COMPETITION-GUIDELINES.pdf"
                    class="un font-bold text-xl">
                    RONDAL-AWIT COMPETITION
                </a>
            </div>
        </div>
    </div>
</template>

<style lang="postcss" scoped>
a {
    @apply text-[var(--primary)]
}

.un {
    display: inline-block;
    background-image: linear-gradient(#176634 0 0);
    background-position: 0 100%;
    /*OR bottom left*/
    background-size: 0% 2px;
    background-repeat: no-repeat;
    padding-bottom: 2px;
    transition:
        background-size 0.3s,
        background-position 0s 0.3s;
}

.un:hover {
    background-position: 100% 100%;
    /*OR bottom right*/
    background-size: 100% 2px;
    color: #176634;
}
</style>