<template>
    <div class="home">
        <header class="header" id="header">
            <nav class="nav container">
                <a href="#" class="nav__logo">Vianney</a>
            </nav>

            <!------------------------------ NAV --------------------------->

            <div class="nav__menu" id="nav-menu" v-show="showMenu">
                <ul class="nav__list grid">
                    <li class="nav__item">
                        <a href="#home" class="nav__link" @click="showMenu = !showMenu">
                            <i class="uil uil-estate nav__icon"></i> Home
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#about" class="nav__link" @click="showMenu = !showMenu">
                            <i class="uil uil-user nav__icon"></i> About
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#skills" class="nav__link" @click="showMenu = !showMenu">
                            <i class="uil uil-file-alt nav__icon"></i> Skills
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#services" class="nav__link" @click="showMenu = !showMenu">
                            <i class="uil uil-briefcase-alt nav__icon"></i> Services
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#portfolio" class="nav__link" @click="showMenu = !showMenu">
                            <i class="uil uil-scenery nav__icon"></i> Portfolio
                        </a>
                    </li>
                    <li class="nav__item">
                        <a href="#contact" class="nav__link" @click="showMenu = !showMenu">
                            <i class="uil uil-message nav__icon"></i> Contactme
                        </a>
                    </li>
                </ul>
                <i class="uil uil-times nav__close" id="nav-close" @click="showMenu = !showMenu"></i>
            </div>

            <div class="nav__btns">
                <div class="nav__toggle" id="nav-toggle">
                    <i class="uil uil-apps" @click="showMenu = !showMenu"></i>
                </div>
            </div>
        </header>

        <!------------------------------ MAIN --------------------------->
        <main class="main">
            <!---------------- HOME ----------------->
            <section class="home section" id="home">
                <div class="home__container container grid">
                    <div class="home__content grid">
                        <div class="home__social">
                            <a href="https://www.linkedin.com/feed/" target="_blank" class="home__social-icon">
                                <i class="uil uil-linkedin-alt"></i>
                            </a>

                            <a href="https://dribbble.com/" target="_blank" class="home__social-icon">
                                <i class="uil uil-dribbble"></i>
                            </a>

                            <a href="https://github.com/allvncr" target="_blank" class="home__social-icon">
                                <i class="uil uil-github-alt"></i>
                            </a>
                        </div>
                    </div>

                    <div class="home__img">
                        <svg class="home__blob" viewBox="0 0 200 187" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                            <mask id="mask0" mask-type="alpha">
                                <path d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547 
                                130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775 
                                97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666 
                                0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"/>
                            </mask>
                            <g mask="url(#mask0)">
                                <path d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 
                                165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 
                                129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 
                                -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"/>
                                
                                <image class="home__blob-img" x='12' y='18' xlink:href="@/assets/img/perfil.png"/>
                            </g>
                        </svg>
                    </div>

                    <div class="home__data">
                        <h1 class="home__title">Hi, I'am Vianney</h1>
                        <h3 class="home__subtitle">FullStack developer</h3>
                        <p class="home__description">Good level in web development
                            knowledge, producing quality work.</p>
                        <a href="#contact" class="button button--flex">
                            Contact Me <i class="uil uil-message button__icon"></i>
                        </a>
                    </div>

                    <div class="home__scroll">
                        <a href="#about" class="home__scroll-button button--flex">
                            <i class="uil uil-mouse-alt home__scroll-mouse"></i>
                            <span class="home__scroll-name">Scroll down</span>
                            <i class="uil uil-arrow-down home__scroll-arrow"></i>
                        </a>
                    </div>
                </div>
            </section>
        </main>


        <!------------------------------ FOOTER --------------------------->
        <footer class="footer">
            <div class="footer__bg">
                <div class="footer__container container grid">
                    <div>
                        <h1 class="footer__title">Vianney</h1>
                        <span class="footer__subtitle">FullStack developer</span>
                    </div>

                    <ul class="footer__links">
                        <a href="#services" class="footer__link">Services</a>
                        <a href="#portfolio" class="footer__link">Portfolio</a>
                        <a href="#contact" class="footer__link">Contactme</a>
                    </ul>

                    <div class="footer__socials">
                        <a href="https://www.facebook.com/" target="_blank" class="footer__social">
                            <i class="uil uil-facebook-f"></i>
                        </a>

                        <a href="https://www.instagram.com/" target="_blank" class="footer__social">
                            <i class="uil uil-instagram"></i>
                        </a>

                        <a href="https://twitter.com/" target="_blank" class="footer__social">
                            <i class="uil uil-twitter-alt"></i>
                        </a>
                    </div>
                </div>
                <p class="footer__copy">&#169; Ablo Vianney. All right reserved</p>
            </div>
        </footer>
    </div>
</template>

<script>   
// @ is an alias to /src


export default {
    name: "Home",

    data(){
        return{
            showMenu: false
        }
    },


    }
</script>

<style lang="scss">

    $hue-color: 230; //purple 250 - green 142 - blue 230 - pink 340
    
    $first-color: hsl($hue-color , 69%, 61%);
    $first-color-second: hsl($hue-color, 69%, 61%);
    $first-color-alt: hsl($hue-color, 57%, 53%);
    $first-color-lighter: hsl($hue-color, 92%, 85%);
    $title-color: hsl($hue-color, 8%, 15%);
    $input-color: hsl($hue-color, 8%, 45%);
    $text-color: hsl($hue-color, 8%, 65%);
    $text-color-light: hsl($hue-color, 8%, 65%);
    $body-color: hsl($hue-color, 70%, 96%);
    $body-color: hsl($hue-color, 60%, 99%);
    $container-color: #fff;

    $header-height: 3rem;

// Font and text
    $big-font-size: 2rem;
    $h1-font-size: 1.5rem;
    $h2-font-size: 1.2rem;
    $h3-font-size: 1.125rem;
    $normal-font-size: .938rem;
    $small-font-size: .813rem;
    $smaller-font-size: .75rem;

    // Font weight
    $font-medium: 500;
    $font-semi-bold: 600;
    
// Margin Bottom
    $mb-0-25: .25rem;
    $mb-0-5: .5rem;
    $mb-0-75: .75rem;
    $mb-1: 1rem;
    $mb-1-5: 1.5rem;
    $mb-2: 2rem;
    $mb-2-5: 2.5rem;
    $mb-3: 3rem;

    // z index
    $z-tooltip: 10;
    $z-fixed: 100;
    $z-modal: 1000;

// REUSABLE CSS CLASSES
.section{
    padding: 2rem 0 4rem;
}

.section__title{
    font-size: $h1-font-size;
}

.section__subtitle{
    display: block;
    font-size: $small-font-size;
    margin-bottom: $mb-3;
}

.section__title, .section__subtitle{
    text-align: center;
}

.container{
    max-width: 768px;
    margin-left: $mb-1-5;
    margin-right: $mb-1-5;
}

.grid{
    display: grid;
    gap: 1.5rem;
}

.header{
    width: 100%;
    position: fixed;
    bottom: 0;
    left: 0;
    z-index: $z-fixed;
    background-color: $body-color;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

// NAV
.nav{
    max-width: 968px;
    height: $header-height;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-weight: $font-semi-bold;
}

.nav__menu{
    @media screen and (max-width: 768px) {
        position: fixed;
        bottom: 0;
        width: 100%;
        background-color: $body-color;
        padding: 2rem 1.5rem 4rem;
        box-shadow: 0 -1px 4px rgba(0,0,0,.15);
        border-radius: 1.5rem 1.5rem 0 0;
        transition: .3s;
    }

    .nav__logo, .nav__toggle{
        color: $title-color;
        font-weight: $font-medium;
    }

    .nav__logo:hover{
        color: $first-color;
    }

    .nav__list{
        grid-template-columns: repeat(3, 1fr);
        gap: 2rem;
    }

    .nav__link{
        display: flex;
        flex-direction: column;
        align-items: center;
        font-size: $smaller-font-size;
        color: $title-color;
        font-weight: $font-medium;
    }

    .nav__link:hover{
        color: $first-color;
    }

    .nav__item{
        margin-bottom: $mb-3;
    }

    .nav__icon{
        font-size: 1.2rem;
    }

    .nav__close{
        position: absolute;
        right: 1.13rem;
        bottom: .5rem;
        font-size: 1.5rem;
        cursor: pointer;
        color: $first-color;
    }

    .nav__close:hover{
        color: $first-color-alt;
    }
}

.nav__toggle{
    color: $first-color-second;
    font-size: 1.5rem;
    cursor: pointer;
    margin-left: $mb-1-5;
    margin-right: $mb-1-5;
}

.nav__toggle:hover{
    color: $first-color;
}

// HOME
.home__container{
    gap: 1rem;
}

.home__content{
    grid-template-columns: .5fr 3fr;
    padding-top: 3.5rem;
    align-items: center;
}

.home__social{
    display: grid;
    grid-template-columns: max-content;
    row-gap: 1rem;
}

.home__social-icon{
    font-size: 1.125rem;
    color: $first-color;
}

.home__social-icon:hover{
    color: $first-color-alt;
}

.home__blob{
    width: 200px;
    fill: $first-color;
}

.home__blob-img{
    width: 170px;
}

.home__data{
    grid-column: 1/3;
}

.home__title{
    font-size: $big-font-size;
}

.home__subtitle{
    font-size: $h3-font-size;
    color: $text-color;
    font-weight: $font-medium;
    margin-bottom: $mb-0-75;
}

.home__description{
    margin-bottom: $mb-2;
}

.home__scroll{
    // display: none;
}

.home__scroll-button{
    color: $first-color;
    transition: .3s;
}

.home__scroll-button:hover{
    transform: translateY(.25rem);
}

.home__scroll-mouse{
    font-size: 2rem;
}

.home__scroll-name{
    font-size: $small-font-size;
    color: $title-color;
    font-weight: $font-medium;
    margin-right: $mb-0-25;
}

.home__scroll-arrow{
    font-size: 1.125rem;
}

// BUTTONS
.button{
    display: inline-block;
    background-color: $first-color;
    color: #fff;
    padding: 1rem;
    border-radius: .5rem;
    font-weight: $font-medium;
}

.button:hover{
    background-color: $first-color-alt;
}

.button__icon{
    font-size: 1.125rem;
    margin-left: $mb-0-5;
    transition: .3s;
}

.button--flex{
    display: inline-flex;
    align-items: center;
}

// FOOTER
.footer{
    padding-top: 2rem;
    font-weight: $font-semi-bold;
    background-color: $first-color-second;

    .footer__bg{
        background-color: $first-color-second;
        padding: 2rem 0 3rem;

        .footer__container{
            row-gap: 3.5rem;
        }

        .footer__title{
            font-size: $h1-font-size;
            margin-bottom: $mb-0-25;
        }

        .footer__subtitle{
            font-size: $small-font-size;
        }

        .footer__links{
            display: flex;
            flex-direction: column;
            row-gap: 1.5rem;

            .footer__link:hover{
                color: $first-color-lighter;
            }
        }
        
        .footer__social{
            font-size: 1.125rem;
            margin-right: $mb-1-5;
        }

        .footer__social:hover{
            color: $first-color-lighter;
        }

        .footer__copy{
            font-size: $small-font-size;
            text-align: center;
            color: $text-color-light;
            margin-top: $mb-3;
        }

        .footer__title,
        .footer__subtitle,
        .footer__link,
        .footer__social{
            color: #fff;
        }
    }
}




</style>
