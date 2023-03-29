<template>
<section class="sell">
    <div class="sell__container">
        <div class="sell__content">
        <div class="sell__content-title">Продать</div>
           <div class="sell__content-data">
            <div class="sell__content-info">
                <div class="sell__content-info-title">Что нужно знать</div>
                <div class="sell__content-info-list">
                    <div class="sell__content-info-item">
                        <img src="@/assets/image/information-sign.png" alt="">
                        <p class="sell__content-info-item-text"> Заполнить информацию о товаре и выставить его на продажу</p>
                    </div>
                    <p class="sell__content-info-subtext">Продажа</p>
                    <div class="sell__content-info-item">
                        <img src="@/assets/image/information-sign.png" alt="">
                        <p class="sell__content-info-item-text"> Выполнить свои обязательства по передаче товара покупателю</p>
                    </div>
                    <div class="sell__content-info-item">
                        <img src="@/assets/image/information-sign.png" alt="">
                        <p class="sell__content-info-item-text"> Вы получите оплату после того, как покупатель подтвердит получение товара</p>
                    </div>
                    <p class="sell__content-info-subtext">Сервисные сборы 20%</p>
                </div>
            </div>
            <div class="sell__content-forbidden">
                <div class="sell__content-forbidden-info">
                    <div class="sell__content-forbidden-title">Запрещено</div>
                    <ul class="sell__content-forbidden-list">
                        <li class="sell__content-forbidden-list-item"><img src="@/assets/image/X.png" alt=""> Указывать недостоверную информацию о товаре</li>
                        <li class="sell__content-forbidden-list-item"><img src="@/assets/image/X.png" alt=""> Мошенничество в любом виде</li>
                        <li class="sell__content-forbidden-list-item"><img src="@/assets/image/X.png" alt=""> Общение с покупателем за пределами Playerok</li>
                        <li class="sell__content-forbidden-list-item"><img src="@/assets/image/X.png" alt=""> Продажа запрещенных товаров, в том числе полученных нелегальным путем</li>
                    </ul>
                    <p class="sell__content-info-subtext">За нарушение условий продажи средства будут возвращены покупателю, Ваш товар будет снят с продажи и Ваша учетная запись будет заблокирована</p>
                </div>
            </div>
           </div>
           <a class="sell__content-button-link" href="#"><div class="sell__content-button">
               <div class="sell__content-button-text">Начать продажу</div>
            </div> </a>
           <div class="sell__content-button-text">Нажимая «Начать продажу», Вы принимаете Условия продажи</div>
        </div>
    </div>
</section>

</template>


<script>

</script>

<style lang="scss">
.sell{
    background-color: #fff;
    min-height: 100vh;
    width: 100%;
    &__container{
        max-width: 1700px;
        margin: 20px auto ; 
    }
    &__content{
        margin-left: 40px;
        max-width: 1052px;
        height: 620px;
        &-title{
            width: 100%;
            height: 90px;
            display: flex;
            align-items: center;
            font-size: 1.125rem;
            line-height: 155%;
            font-weight: 700;
        }
        &-data{
            width: 100%;
            max-height: 407px;
            display: flex;
            justify-content:space-between;
        }
        &-info{
            width: 350px;
            height: 360px;
            &-title{
                font-size: 24px;
                font-weight: 900;
                margin-bottom: 20px;
            }
            &-list{
                width: 350px;
                height: 100%;
            }
            &-item{
                width: 320px;
                height: 51px;
                display: flex;
                margin-bottom: 20px;
                & img{
                    width: 20px;
                    height: 20px;
                    margin-right: 10px;
                }
                &-text{
                    font-size: 1rem;
                    line-height: 160%;
                }
            }
            &-subtext{
                font-size: 0.875rem;
                line-height: 170%;
                color: #828794;
                margin-bottom: 20px;
            }
        }
        &-forbidden{
            width: 611px;
            height: 365px;
            background-color: #f2f4f6;
            border-radius: 8px;
            margin-bottom: 40px;
            &-info{
                padding: 16px 20px 20px;
            }
            &-title{
                font-size: 24px;
                font-weight: 900;
                margin-bottom: 20px;
            }
            &-list{
                width: 100%;
                height: 190px;
            
                &-item{

                    display: flex;
                    align-items: center;
                    margin-bottom: 15px;
                    font-size: 1rem;
                    line-height: 160%;
                    & img{
                        width: 32px;
                        height: 32px;
                    }
                }
            }
        }
        &-button{
            width: 100%;
            height: 52px;
            background-color: #1543ff;
            text-align: center;
            display: flex;
            align-items: center;
            text-decoration: none;
            &:hover{
                background-color: #4275ff;
            }
            &-link{
                text-decoration: none;
            }
            &-text{
                margin: auto;
                font-size: 18px;
                line-height: 155%;
                color: #fff;
                font-weight: 800;
            }
        }
    }
}

</style>