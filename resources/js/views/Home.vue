<template>
    <div>
        <Audio></Audio>

        <Cover></Cover>

        <Mempelai></Mempelai>

        <Acara></Acara>

        <Gallery></Gallery>

        <Protocol></Protocol>

        <section id="bukutamu" class="uk-container uk-container-small">
            <div class="tw-h-24"></div>

            <section>
                <div>
                    <section id="mempelai">
                        <div
                            class="
                                sm:tw-max-w-screen-sm
                                md:tw-max-w-screen-md
                                lg:tw-max-w-screen-lg
                                tw-mx-auto tw-px-2.5 tw-py-10
                            "
                        >
                            <p
                                class="
                                    tw-text-sm tw-leading-relaxed
                                    lg:tw-font-semibold
                                    tw-font-normal tw-text-justify
                                    md:tw-text-center
                                    lg:tw-hidden
                                    tw-py-4 tw-mb-10
                                "
                            >
                                Dengan memohon rahmat dan ridho-Mu Ya Allah,
                                Kami bermaksud mengadakan acara pernikahan putra
                                dan putri kami.
                            </p>
                            <p
                                class="
                                    tw-hidden
                                    lg:tw-block
                                    tw-leading-relaxed tw-text-sm
                                    lg:tw-font-semibold
                                    tw-font-normal tw-text-justify
                                    md:tw-text-center
                                    tw-py-4 tw-mb-16
                                "
                            >
                                Turut Mengundang :
                            </p>

                            <div class="lg:tw-w-4/5 lg:tw-mx-auto">
                                <div
                                    class="
                                        tw-grid tw-grid-cols-1
                                        sm:tw-grid-cols-2 sm:tw-gap-4
                                        md:tw-gap-2
                                        lg:tw-gap-6
                                        tw-mx-auto
                                    "
                                >
                                    <div class="tw-text-center">
                                        <div class="pl tw-mx-auto"></div>
                                        <h2
                                            class="
                                                tw-py-3
                                                m-name
                                                tw-text-1xl
                                                sm:tw-text-lg
                                                md:tw-text-1xl
                                                lg:tw-text-2xl
                                            "
                                        >
                                            Mempelai Wanita :
                                        </h2>
                                        <!-- <a href="" class="">@salmanagustian</a>  -->
                                        <p
                                            class="
                                                tw-text-sm
                                                lg:tw-font-semibold
                                                tw-font-normal tw-mb-10
                                            "
                                        >
                                            Hi. Ekwan Ahmad, S.h
                                            <br />Kel. Sahi<br />Kel. Mowu'u<br />
                                            Kel. Salilama<br />
                                            Kel. Hulalata
                                        </p>
                                    </div>
                                    <div class="tw-text-center">
                                        <div class="pw tw-mx-auto"></div>
                                        <h2
                                            class="
                                                tw-py-3
                                                m-name
                                                tw-text-1xl
                                                sm:tw-text-lg
                                                md:tw-text-1xl
                                                lg:tw-text-2xl
                                            "
                                        >
                                            Mempelai Pria :
                                        </h2>
                                        <!-- <a href="" class="">@zakhansa</a> -->
                                        <p
                                            class="
                                                tw-text-sm
                                                lg:tw-font-semibold
                                                tw-font-normal tw-mb-12
                                                sm:tw-mb-20
                                            "
                                        >
                                            Sertu Purn. Abd. Manan Doa, (Alm.)
                                            <br />Kamala Soleman <br />
                                            Kel. Doa <br />
                                            Kel. Soleman
                                        </p>
                                    </div>
                                </div>
                            </div>

                            <hr class="divider" />
                        </div>
                    </section>
                </div>
            </section>
            <div class="tw-h-16"></div>
        </section>
        <section
            style="
                display: flex;
                flex-direction: column;
                align-items: center;
                text-align: center;
                padding: 2rem;
            "
        >
            <h2
                style="
                    font-family: Scarlet;
                    font-size: 2rem;
                    margin-bottom: 1.5rem;
                "
            >
                Tanpa mengurangi rasa hormat, bagi yang ingin menunjukkan
                apresiasinya kepada kami, dapat dilakukan melalui
            </h2>

            <!-- Bank Card -->
            <div
                style="
                    background-color: white;
                    border-radius: 1rem;
                    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
                    padding: 1.5rem;
                    max-width: 400px; /* Membatasi lebar konten */
                    width: 100%; /* Menjaga responsivitas */
                "
            >
                <div
                    style="
                        display: flex;
                        justify-content: space-between;
                        align-items: flex-start;
                    "
                >
                    <div>
                        <img
                            src="https://upload.wikimedia.org/wikipedia/commons/9/97/Logo_BRI.png"
                            alt="Bank BRI Logo"
                            style="
                                margin-bottom: 1rem;
                                width: 80px;
                                height: auto;
                            "
                        />

                        <div style="margin-top: 1rem">
                            <div
                                style="font-size: 1.125rem; font-weight: 500"
                                class="tw-font-extrabold tw-text-black"
                            >
                                0027 0110 4460 500
                            </div>
                            <div
                                style="font-size: 0.875rem; color: #666"
                                class="tw-font-extrabold tw-text-black"
                            >
                                Cicit Irmawan
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <div class="tw-h-28"></div>

        <p
            class="
                tw-text-xs tw-text-extralight tw-text-center tw-italic
                text-thelast
            "
        >
            - 'Wassalamualaikum Warrahmatullahi Wabarakatuh'
        </p>

        <hr class="divider-thelast" />

        <div class="tw-h-12"></div>

        <Navbar></Navbar>
        <MusicBox></MusicBox>
    </div>
</template>

<script>
import Comment from "./components/Comment.vue";
import Gallery from "./components/Gallery.vue";
import Acara from "./components/Acara.vue";
import Mempelai from "./components/Mempelai.vue";
import Cover from "./components/Cover.vue";
import FormGuestBook from "./components/FormGuestBook.vue";

import Audio from "./addon/Audio.vue";
import Navbar from "./addon/Navbar.vue";
import MusicBox from "./addon/MusicBox.vue";
import Protocol from "./addon/Protocol.vue";

import InfiniteLoading from "vue-infinite-loading";

export default {
    components: {
        Cover,
        Mempelai,
        Acara,
        Gallery,
        Protocol,
        FormGuestBook,
        Comment,
        Audio,
        Navbar,
        MusicBox,
        InfiniteLoading,
    },

    data() {
        return {
            comments: [],
            page: 1,
            busy: false,
        };
    },

    mounted() {
        let prevScrollpos = window.pageYOffset;

        window.onscroll = () => {
            const currentScrollPos = window.pageYOffset;

            if (prevScrollpos > currentScrollPos) {
                document.getElementById("navbar").style.bottom = "0";
            } else {
                document.getElementById("navbar").style.bottom = "-78px";
            }
            prevScrollpos = currentScrollPos;

            let bottomOfWindow =
                document.documentElement.scrollTop + window.innerHeight ===
                document.documentElement.offsetHeight;

            if (bottomOfWindow) {
                this.loadMore();
            }
        };
    },

    methods: {
        loadMore($state) {
            this.busy = true;

            axios
                .get("comments?page=" + this.page)
                .then(({ data }) => {
                    const listComments = data.data;
                    if (listComments.length) {
                        this.page += 1;
                        this.comments.push(...listComments);
                        $state.loaded();
                    } else {
                        $state.complete();
                    }
                })
                .catch((err) => console.log(err));
        },
        addComment(comment) {
            this.comments.unshift(comment);
        },
    },
};
</script>

<style scoped>
.text-thelast {
    color: rgba(206, 180, 108, 0.75);
}

.divider-thelast {
    margin: 0 auto;
    width: 15%;
    margin-top: 3px;
    border: 0;
    height: 1px;
    background-image: linear-gradient(
        to right,
        rgba(255, 255, 255, 0),
        rgba(206, 180, 108, 0.75),
        rgba(255, 255, 255, 0)
    );
}
</style>
