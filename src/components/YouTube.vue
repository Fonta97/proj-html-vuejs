<script>
export default {
    name: 'YouTube',
}
</script>
<template>
    <section class="paddingY" id="youtube-section">
        <div
            class="container container-sm d-flex justify-content-lg-center justify-content-sm-center"
        >
            <div class="row justify-content-sm-center">
                <div class="col-lg-12 col-sm-10 pos-relative">
                    <div class="img-box-overlay">
                        <img
                            class="dittoBlue-section-youtube rotating-image-top-right"
                            src="../assets/images/DittoShapeBlue.svg"
                            alt=""
                        />
                        <img
                            class="animated-bg-top-image rotating-image-left"
                            src="../assets/images/maxcoach-shape-12-100x100.png"
                            alt=""
                        />
                        <img
                            class="animated-bg-bottom-image rotating-image-left"
                            src="../assets/images/maxcoach-shape-12-100x100.png"
                            alt=""
                        />
                        <div class="overlay">
                            <a
                                href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&ab_channel=RickAstley"
                                ><img
                                    src="../assets/images/icon-youtube-play.png"
                                    alt="youtube icon play"
                            /></a>
                        </div>
                    </div>
                    <div class="circle rotating-image-right">
                        <div class="inner-circle"></div>
                    </div>
                    <div class="card border-0">
                        <a href=""></a>
                        <img
                            class="youtube-video"
                            src="../assets/images/artist-video-poster.jpg"
                            alt="anteprima"
                        />
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

#youtube-section {
    background-image: url('../assets/images/wave.svg');
    background-position-y: -30%;
    background-repeat: no-repeat;
    background-size: cover;
}

.cursive {
    font-family: $secondary-font;
    color: $secondary-text-color;
    font-size: 40px;
}
.paddingY {
    padding-bottom: 100px;
}

.card {
    position: relative;
    overflow: hidden;
}
.youtube-video {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
}

.card:hover .youtube-video {
    transform: scale(1.1);
}

.pos-relative {
    position: relative;
}

.circle {
    position: absolute;
    top: 10%;
    left: 105%;
    width: 100px;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    background-color: #ecc5ab;
    animation: circle 3s infinite ease-in-out;
    @keyframes circle {
        100% {
            transform: translateY(0);
        }

        50% {
            transform: translateY(50px) translateX(30px);
        }
    }
    .inner-circle {
        width: 75px;
        height: 75px;
        border-radius: 50%;
        background-color: white;
    }
}

.overlay {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 5;
}

.animated-bg-top-image {
    width: 180px;
    position: absolute;
    top: -5%;
    left: -6%;
    z-index: -1;
    animation: points 3s infinite ease-in-out;
    @keyframes points {
        0%,
        100% {
            transform: translateY(0);
        }

        50% {
            transform: translateY(-50px) translateX(-30px);
        }
    }
}

.animated-bg-bottom-image {
    width: 180px;
    position: absolute;
    bottom: -10%;
    right: -7%;
    z-index: -1;
}
.dittoBlue-section-youtube {
    position: absolute;
    width: 250px;
    height: 250px;
    top: -13%;
    left: -10%;
    z-index: -2;
    animation: ditto 3s infinite ease-in-out;
    @keyframes ditto {
        0%,
        100% {
            transform: translateY(0);
        }

        50% {
            transform: translateY(-70px) translateX(70px);
        }
    }
}
</style>
