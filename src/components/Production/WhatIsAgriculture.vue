<template>
    <div class="what-is-agriculture">
        <div class="what-text">

            <div class="title-what">
                <h2>O que é ?</h2>
            </div>
            <div class="p-what">
                <p>Um meio de cultivo da terra realizado por pequenos proprietários rurais, os quilombolas utilizam esse
                    modo de produção, onde mantém seu solo de plantação sempre saudável, com o conhecimento tradicional
                    de seus antecessores garantindo um entendimento dinâmico do território e das culturas referentes ao
                    plantio.</p>
            </div>
        </div>
        <div class="what-container">
        </div>
    </div>
</template>

<style lang="less" scoped>
.what-is-agriculture {
    height: 100vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.what-container {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50%;
    height: 100%;
    background-image: url(../../assets/WhatIsAgriculture.jpg);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

.what-text {
    width: 50%;
    z-index: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;

    .title-what {
        width: 85%;

        h2 {
            color: #000;
            line-height: 1;
            font-size: 2.5em;
        }

        margin: 0;
        opacity: 0.8;
    }

    .p-what {
        margin-top: 2vh;

        width: 85%;
        font-size: 25px;
        font-weight: 100;
    }
}

.dark {
    .title-what {

        h2 {
            color: #ffffff;
        }
    }

    .p-what {
        color: #ffffff;
    }
}

@media only screen and (max-width: 1000px) {

    .what-is-agriculture {
        justify-content: flex-start;
        align-items: flex-start;
        flex-direction: column;
    }

    .what-container {
        background-size: cover;
        // background-position: center 60%;
        background-repeat: no-repeat;
        width: 100%;
        height: 50%;
    }

    .what-text {
        width: 100%;
        height: 50%;
        padding: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;

        .title-what {
            width: 70%;

            h2 {
                line-height: 1;
                font-size: calc(2em + 2vh);
            }

            margin: 0;
            opacity: 0.8;
        }

        .p-what {
            margin-top: 2vh;

            width: 70%;
            font-size: 20px;
            font-weight: 100;
        }
    }
}

@media only screen and (max-width: 600px) {

    .what-container {
        background-size: cover;
        background-position: center 60%;
        background-repeat: no-repeat;
        width: 100%;
        height: 40vh;
    }

    .what-text {
        width: 100%;
        height: 60%;
        padding: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;

        .title-what {
            width: 90%;

            h2 {
                line-height: 1;
                font-size: calc(1.5em + 2vw);
            }

            margin: 0;
            opacity: 0.8;
        }

        .p-what {
            margin-top: 1vh;

            width: 90%;
            font-size: 18px;
            font-weight: 100;
        }
    }
}

@media only screen and (max-width: 300px) {

    .what-text {

        .title-what {
            width: 90%;

            h2 {
                line-height: 1;
                font-size: calc(1em + 2vw);
            }

            margin: 0;
            opacity: 0.8;
        }

        .p-what {
            margin-top: 1vh;

            width: 90%;
            font-size: 15px;
            font-weight: 100;
        }
    }

}
</style>