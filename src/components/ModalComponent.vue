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
            <section class="text-3xl font-semibold tracking-tight text-gray-900 dark:text-white">ASW-G-08 Gundam Barbatos
            </section>
            <br>
            <div class="grid grid-cols-1 gap-6 sm:grid-cols-2">
                <img height="500px" src="https://api.duniagames.co.id/api/content/upload/file/3027223061658211635.jpg"
                    alt="image description">
                <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
                    Gundam Barbatos adalah salah satu dari 72 kerangka "Gundam" yang diproduksi dan digunakan dalam Perang
                    Bencana, kira-kira 300 tahun yang lalu. Setelah pulih, Chryse Guard Security menggunakannya sebagai
                    reaktor daya. Selain fakta bahwa Reaktor Ahab-nya masih berfungsi, hal ini dilakukan terutama karena
                    kokpit Barbatos hilang saat ditemukan. Kokpit baru yang mirip dengan yang digunakan oleh pekerja
                    lapangan CGS dipasang sebelum dipindahkan oleh Grup ke-3. Perawatan yang buruk selama berabad-abad sejak Perang Bencana telah menurunkan armor Barbatos dan potensi
                tempur penuh.
                </p>
            </div>
            <br>
            <p class="text-base leading-relaxed text-gray-500 dark:text-gray-400">
                 Hal ini kemudian diperbaiki oleh teknisi Teiwaz, yang tidak hanya mengembalikan Barbatos ke
                tampilan aslinya tetapi juga mengembalikannya ke performa yang mendekati aslinya. Saat Gjallarhorn
                menyerang, anak laki-laki CGS buru-buru mengaktifkannya, dan Mikazuki Augus menjadi pilotnya. Unit Gundam
                seperti Barbatos mampu mencapai keluaran energi yang tinggi karena mereka memiliki dua Reaktor Ahab
            </p>


        </template>

    </Modal>
</template>
