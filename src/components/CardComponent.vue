<script setup>
import ModalComponent from './ModalComponent.vue';
import ModalDuaComponent from './ModalDuaComponent.vue';
import ModalTigaComponent from './ModalTigaComponent.vue'
</script>

<template>
    
    <section class="bg-white dark:bg-gray-900">
        <div class="py-2 px-4 mx-auto max-w-screen-xl lg:py-16">
            <div class="bg-white-50 dark:bg-gray-800 p-8 md:p-12 mb-8">
                <a href="#"
                    class="bg-blue-100 text-blue-800 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded-md dark:bg-gray-700 dark:text-blue-400 mb-2">
                    Gundam is not just Robot
                </a>
                <h1 class="text-gray-900 dark:text-white text-3xl md:text-5xl font-extrabold mb-2">Animasi dari Jepang ? Apa
                    sih Gundam itu ?</h1>

                <p class="mb-3 text-gray-500 dark:text-gray-400">Gundam merupakan serial cerita yang
                    berawal di komik dan dengan perkembangan zaman berubah menjadi animasi yang berasal dari negara Jepang.
                    Pertama kali ditayangkan pada tanggal 7 April 1979 hingga 26 Januari 1980, sepanjang 43 episode.
                    Masyarakat Jepang menyukai dengan adanya animasi Gundam mulai dari berbagai kalangan. Baik itu anak
                    kecil ataupun orang dewasa. Dengan bertemakan masa depan dan peperangan dengan efek-efek yang sangat
                    menarik mata.</p>
                <div class="grid grid-cols-1 gap-6 sm:grid-cols-2">
                    <p class="mb-3 text-gray-500 dark:text-gray-400">Popularitas Gundam tidak berhenti
                        sampai di Jepang saja. Namun karen perkembangan zaman dan globalisasi. Animasi Gundam bisa tersebar
                        ke
                        seluruh dunia dan mendapat reaksi yang sangat bagus dari banyak orang. Hal ini menjadikan Gundam
                        semakin
                        dikenal oleh masyarakat dunia, bukan hanya masyarakat Jepang. <br> <br>
                         Kemunculan series baru Gundam pun
                        semakin
                        banyak dengan alur cerita dan tokoh yang menarik pula. Suatu perusahaan mainan di Jepang yaitu
                        Bandai mengambil kesempatan untuk membuat bentuk nyata Gundam berbentuk mainan. Mainan ini dikenal
                        dengan nama "Gunpla" (Gundam Plastic Model). Dengan munculnya Gunpla membuat penyuka Gundam
                        berbondong-bondong membeli mainan ini. Gunpla hanya mainan yang dijadikan untuk pajangan, namun bisa
                        menjadi wadah kreativitas kita. Karena Gunpla sangat mudah untuk dimodifikasi sesuka hati kita.</p>
                    
                    <img height="500px" src="https://img.freepik.com/free-photo/japanese-japan-mobile-tokyo-city_1232-3844.jpg?w=826&t=st=1690423463~exp=1690424063~hmac=20ce0f33759a447a17b5c74a7d2043c2b20bfaae91e648e417e45477e8e33a7e"
                        alt="image description">

                </div>
                <br>
                <p class="text-lg font-normal text-gray-500 dark:text-gray-400 mb-6">Keberhasilan Bandai dalam menciptakan
                    Gunpla membuat mereka dilirik oleh perusahaan animasi Gundam dan bekerja sama. Kerjasama ini membuat
                    Bandai untung besar dan memudahkan dalam memproduksi Gunpla lebih banyak dan variatif. Mengetahui
                    penikmat Gunpla bukan hanya orang dewasa saja namun juga anak-anak kecil. Bandai membuat tingkatan
                    kesusahan dalam membuat Gunpla sehingga anak-anak bisa tetap ikut merakit Gunpla. Dengan adanya 10
                    tingkatan, mulai dari yang paling sederhana hingga yang paling kompleks dan sangat detail.
                </p>
                <section class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Mari mengenal beberapa
                    Gundam yang paling ikonik di Franchise Mobile Suits</section>
                <div class="grid md:grid-cols-3 gap-8">

                    <div
                        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                        <a href="#">
                            <img class="rounded-t-lg"
                                src="https://api.duniagames.co.id/api/content/upload/file/3027223061658211635.jpg" alt="" />
                        </a>
                        <div class="p-5">
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">ASW-G-08
                                    Gundam Barbatos</h5>
                            </a>
                            <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Perawatan yang buruk selama
                                berabad-abad sejak Perang Bencana telah menurunkan armor Barbatos
                                dan potensi tempur penuh. Hal ini ... </p>
                            <div>
                                <ModalComponent></ModalComponent>
                            </div>
                        </div>
                    </div>

                    <div
                        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                        <a href="#">
                            <img class="rounded-t-lg"
                                src="https://steamuserimages-a.akamaihd.net/ugc/966469933773986762/C2E9D1B0889E85B32B06199C5268F59FC956E9CD/?imw=1024&imh=576&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=true"
                                alt="" />
                        </a>
                        <div class="p-5">
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Strike
                                    Freedom Gundam</h5>
                            </a>
                            <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Strike Freedom pertama kali
                                memasuki perang Valentine Berdarah Kedua pada tahun 74 Era Kosmik ketika ... </p>
                            <br>
                            <div>
                                <ModalDuaComponent></ModalDuaComponent>
                            </div>
                        </div>
                    </div>

                    <div
                        class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
                        <a href="#">
                            <img class="rounded-t-lg"
                                src="https://p4.wallpaperbetter.com/wallpaper/161/280/2/anime-robot-gundam-mobile-suit-gundam-wing-wing-gundam-zero-hd-wallpaper-preview.jpg"
                                alt="" />
                        </a>
                        <div class="p-5">
                            <a href="#">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Gundam Wing
                                    Zero </h5>
                            </a>
                            <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Keunikan Gundam Wing Zero adalah
                                sepasang sayap besar di bagian belakang yang memberinya tampilan yang spektakuler dan
                                memberikan ...
                            </p>
                            <div>
                                <ModalTigaComponent></ModalTigaComponent>
                            </div>

                        </div>
                    </div>

                </div>
            </div>

        </div>
    </section>
</template>

