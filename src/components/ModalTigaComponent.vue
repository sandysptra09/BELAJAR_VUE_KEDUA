<script setup>
import { Modal } from 'flowbite-vue'
import { ref } from 'vue'

const isShowModal = ref(false)
function closeModal() {
    isShowModal.value = false
}
function showModal() {
    isShowModal.value = true
}
</script>

<template>
    <button @click="showModal" type="button"
    class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-emerald-500 rounded-lg hover:bg-emerald-600 focus:ring-4 focus:outline-none focus:ring-emerald-300 dark:bg-emerald-600 dark:hover:bg-emerald-700 dark:focus:ring-emerald-800">
        Baca
        <svg class="w-3.5 h-3.5 ml-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M1 5h12m0 0L9 1m4 4L9 9" />
        </svg>
    </button>
    <Modal size="5xl" v-if="isShowModal" @close="closeModal">

        <template #body>
            <section class="text-3xl font-semibold tracking-tight text-gray-900 dark:text-white">Gundam Wing Zero
                Gundam
            </section>
            <br>
            <div class="grid grid-cols-1 gap-6 sm:grid-cols-2">
                <img height="500px"
                    src="https://p4.wallpaperbetter.com/wallpaper/161/280/2/anime-robot-gundam-mobile-suit-gundam-wing-wing-gundam-zero-hd-wallpaper-preview.jpg"
                    alt="image description">
                <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
                    Wing Zero adalah Gundam pertama yang dirancang oleh lima insinyur yang mengembangkan OZ-00MS Tallgeese.
                    Sekitar AC 175, MS, yang dikembangkan sebagai "persenjataan" oleh OZ.
                    Gundam Wing Zero memiliki desain yang khas dengan kombinasi warna biru dan putih, mirip dengan gaya
                    desain Gundam RX-78. Namun, Gundam Wing Zero memiliki bentuk yang lebih ramping dan aerodinamis.
                    Keunikan Gundam Wing Zero adalah sepasang sayap besar di bagian belakang yang memberinya tampilan yang
                    spektakuler dan kekuatan tempur yang lebih besar. Sayap-sayap tersebut dapat membuka dan memberikan
                    mobilitas tinggi dalam pertempuran.
                </p>
            </div>
            <br>
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
                Gundam Wing Zero adalah salah satu Mobile Suit paling kuat dalam serial Gundam Wing. Ditenagai oleh sistem
                bermotor nuklir (nuclear thermal engine), Gundam Wing Zero memiliki kemampuan tempur yang luar biasa dan
                senjata-senjata kuat, termasuk senapan energi dan pedang laser berkekuatan tinggi. Kemampuannya dalam
                pertempuran udara dan antariksa membuatnya menjadi ancaman serius bagi pasukan Oz dan menjadi alat utama
            untuk mencapai tujuan para Gundam Pilots.
        </p>


    </template>

</Modal></template>
