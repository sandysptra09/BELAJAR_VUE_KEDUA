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
            <section class="text-3xl font-semibold tracking-tight text-gray-900 dark:text-white">ZGMF-X20A Strike Freedom
                Gundam
            </section>
            <br>
            <div class="grid grid-cols-1 gap-6 sm:grid-cols-2">
                <img height="500px"
                    src="https://steamuserimages-a.akamaihd.net/ugc/966469933773986762/C2E9D1B0889E85B32B06199C5268F59FC956E9CD/?imw=1024&imh=576&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true"
                    alt="image description">
                <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
                    ZGMF-X20A Strike Freedom Gundam (alias Strike Freedom, Freedom) adalah penerus dari ZGMF-X10A Freedom
                    Gundam yang diperkenalkan di anime Mobile Suit Gundam SEED Destiny. Dipiloti oleh Kira Yamato. Pada
                    perang Valentine Berdarah pertama, ZGMF-X10A Freedom Gundam buatan ZAFT yang dipiloti oleh Kira Yamato
                    merupakan salah satu mobile suit paling kuat yang pernah dibuat. Strike Freedom pertama kali memasuki
                    perang Valentine Berdarah Kedua pada tahun 74 Era Kosmik ketika Kira Yamato terbang ke orbit Bumi dengan
                    menggunakan MBF-02 Strike Rouge untuk membantu Eternal yang diserang oleh pasukan ZAFT.
                </p>
            </div>
            <br>
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
            Tapi disebut juga sebagai Strike Freedom Gundam, atau hanya Freedom Gundam
            saja, perbedaan dengan Freedom sebelumnya adalah, Strike Freedom memiliki frame emas dengan desain sayap
            yang berbeda. Strike Freedom di animenya tidak pernah lecet sama sekali ataupun terkena serangan, maka tidak
            heran gundam ini sangat kuat. Strike Freedom adalah mobile suit yang memiliki kekuatan, kecepatan, dan
            akurasi yang sangat tinggi.
        </p>


    </template>

</Modal></template>
