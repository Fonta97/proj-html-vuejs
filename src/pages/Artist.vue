<script>
import Hello from '../components/Hello.vue'
import ArtistCoaching from '../components/ArtistCoaching.vue'
import GetStarted from '../components/GetStarted.vue'
import YouTube from '../components/YouTube.vue'
import Carousel from '../components/Carousel.vue'
import Shop from '../components/Shop.vue'
import ArticleAndTips from '../components/ArticleAndTips.vue'
import Events from '../components/Events.vue'
import MoveToTop from '../components/MoveToTop.vue'
import ChatBox from '../components/ChatBox.vue'
import SideBar from '../components/SideBar.vue'
export default {
    name: 'Artist',
    components: {
        ArtistCoaching,
        Hello,
        GetStarted,
        YouTube,
        Carousel,
        Shop,
        ArticleAndTips,
        Events,
        MoveToTop,
        ChatBox,
        SideBar,
    },
}
</script>
<template>
    <!-- SEZIONI ALE -->
    <Hello />
    <ArtistCoaching />

    <!-- SEZIONI LUCA -->
    <GetStarted />
    <!-- sezione video youtube -->
    <YouTube />
    <!-- sezione Carousel -->
    <Carousel />
    <!-- sezione card shop-->
    <Shop />

    <ArticleAndTips />
    <Events />

    <SideBar />

    <MoveToTop />

    <ChatBox />

    <!-- SEZIONI DOME -->
    <!-- <section class="my-3" id="article-and-tips">
        <div class="container">
            <div class="row justify-content-center py-5">
                <div class="col-5">
                    <div class="text-center">
                        
                        <h2 class="cursive">Article and Tips</h2>
                        <h3>Latest From The Blog</h3>
                    </div>
                </div>
            </div>

            <div class="dittoBlue-section-cards rotating-image-left">
                <img
                    src="../assets/images/maxcoach-shape-12-orange.png"
                    alt=""
                />
            </div>

            <div class="rotating-image-right dittoShape-section-cards">
                <img src="../assets/images/DittoShapeBlue.svg" alt="" />
            </div>

            <div>
                <img src="../" alt="" />
            </div>

            <div class="row justify-content-around">
                <div class="col-3 col-img1">
                    <div class="card border-0" id="card">
                        <img
                            src="../assets/images/artist-blog-03-480x356.jpeg"
                            class="card-img-top"
                            alt="Immagine 1"
                        />
                        <div class="card-body">
                            <p class="card-text">ARTIST</p>
                            <h4 class="h4-artist">
                                Brush Strokes Energize Trees in Paintings
                            </h4>
                            <p class="text-body-secondary">
                                <i
                                    class="fa-regular fa-calendar"
                                    style="color: #969696"
                                ></i>
                                May 15, 2020
                            </p>
                            <p class="text-body-secondary">
                                <i
                                    class="fa-solid fa-eye"
                                    style="color: #969696"
                                ></i>
                                2,157 Views
                            </p>
                        </div>
                    </div>
                </div>

                <div class="col-5 pos-relative">
                    <div class="card border-0" id="card">
                        <img
                            src="../assets/images/artist-blog-02-500x680.jpg"
                            class="card-img-top"
                            alt="Immagine 2"
                        />
                        <div class="card-body-centrale">
                            <p class="card-text">Artist</p>
                            <h4 class="title-center">
                                Connection Between Self-Portraits and Idantity
                            </h4>

                            <span
                                ><i
                                    class="fa-regular fa-calendar"
                                    style="color: #ffffff"
                                ></i>
                                May 15, 2020</span
                            >
                            <span
                                ><i
                                    class="fa-solid fa-eye"
                                    style="color: #ffffff"
                                ></i>
                                2,167 Views</span
                            >
                        </div>
                    </div>
                </div>

                <div class="col-3">
                    <div class="card border-0" id="card">
                        <img
                            src="../assets/images/artist-blog-01-480x356.jpg"
                            class="card-img-top"
                            alt="Immagine 3"
                        />
                        <div class="card-body">
                            <p class="card-text">ARTIST</p>
                            <h4 class="h4-artist">
                                Pocket-Sized Notebooks Hold Minature Paintings
                            </h4>
                            <p class="text-body-secondary">
                                <i
                                    class="fa-regular fa-calendar"
                                    style="color: #969696"
                                ></i>
                                May 15, 2020
                            </p>
                            <p class="text-body-secondary">
                                <i
                                    class="fa-solid fa-eye"
                                    style="color: #969696"
                                ></i>
                                2,020 Views
                            </p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="text-center mt-5 mb-5">
         
                <span>Get into details now? </span>
                <a href=""
                    ><span class="span-orange" style="font-weight: 700"
                        >View all posts
                        <i
                            class="fa-solid fa-arrow-right"
                            style="color: #ff6600"
                        ></i></span
                ></a>
            </div>
        </div>
    </section>

    <section class="pb-5">
        <div class="container" id="section-upcoming">
            <div>
                <img
                    src="../assets/images/maxcoach-shape-13.png"
                    class="maxcoach-section-upcoming"
                    alt=""
                />
                <img
                    src="../assets/images/maxcoach-shape-05-150x150.png"
                    class="maxcoach-shape-section-upcoming"
                    alt=""
                />
            </div>
            <div class="text-center mt-5">
               
                <h2 class="cursive">Upcoming Event</h2>
                <h3>Let's Work Together</h3>
            </div>

            <div class="row mt-5">
             
                <div class="col-6">
                    <div class="card border-0">
                        <div class="row">
                            <div class="col-4">
                                <img
                                    src="../assets/images/artist-event-04-250x300.jpg"
                                    class="card-img-top"
                                    alt="..."
                                />
                            </div>
                            <div class="col-8" id="descrizione-col8">
                                <div class="card-body">
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            >APR 22,2021</small
                                        >
                                    </p>
                                    <h5 class="card-title">
                                        Storytelling Workshop
                                    </h5>
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            ><i
                                                class="fa-solid fa-location-dot"
                                            ></i>
                                            Texas,US</small
                                        >
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-6">
                    <div class="card border-0">
                        <div class="row">
                            <div class="col-4">
                                <img
                                    src="../assets/images/artist-event-03-250x300.jpg"
                                    class="card-img-top"
                                    alt="..."
                                />
                            </div>
                            <div class="col-8" id="descrizione-col8">
                                <div class="card-body">
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            >APR 22,2021</small
                                        >
                                    </p>
                                    <h5 class="card-title">
                                        Storytelling Workshop
                                    </h5>
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            ><i
                                                class="fa-solid fa-location-dot"
                                            ></i>
                                            Texas,US</small
                                        >
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="row mt-5">
                <div class="col-6">
                    <div class="card border-0">
                        <div class="row">
                            <div class="col-8" id="descrizione-col8">
                                <div
                                    class="card-body"
                                    style="text-align: right"
                                >
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            >NOV 23,2020</small
                                        >
                                    </p>
                                    <h5 class="card-title">
                                        Interntional Art Fair 2020
                                    </h5>
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            ><i
                                                class="fa-solid fa-location-dot"
                                            ></i>
                                            Hamburg, Germany</small
                                        >
                                    </p>
                                </div>
                            </div>
                            <div class="col-4">
                                <img
                                    src="../assets/images/artist-event-02-250x300.jpg"
                                    class="card-img-top"
                                    alt="..."
                                />
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-6">
                    <div class="card border-0">
                        <div class="row">
                            <div class="col-8" id="descrizione-col8">
                                <div
                                    class="card-body"
                                    style="text-align: right"
                                >
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            >DEC 15,2020</small
                                        >
                                    </p>
                                    <h5 class="card-title">
                                        Street Perfomance: Call of Artist
                                    </h5>
                                    <p class="card-text">
                                        <small class="text-body-secondary"
                                            ><i
                                                class="fa-solid fa-location-dot"
                                            ></i>
                                            Illinois,US</small
                                        >
                                    </p>
                                </div>
                            </div>
                            <div class="col-4">
                                <img
                                    src="../assets/images/artist-event-01-250x300.jpg"
                                    class="card-img-top"
                                    alt="..."
                                />
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section> -->

    <!-- <section>
        <div class="container-fluid" id="container-newsletter">
            <div class="row" id="row-newsletter">
                <div class="col d-flex justify-content-between">
                    <img
                        src="../assets/images/artist-shape-color-paint-top-left.png"
                        alt=""
                    />

                    <div class="col-3" id="div-newsletter">
                        <p class="text-white" id="p-newsletter">
                            Newsletter To Get in Touch
                        </p>
                    </div>

                    <div class="">
                        <input
                            type="email"
                            class="form-control"
                            id="exampleFormControlInput1"
                            placeholder="Your e-mail"
                        />
                    </div>

                    <img
                        src="../assets/images/artist-shape-color-paint-bottom-right.png"
                        alt=""
                    />
                </div>
            </div>
        </div>
    </section> -->
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

.cursive {
    font-family: $secondary-font;
    color: $secondary-text-color;
    font-size: 40px;
}
</style>
