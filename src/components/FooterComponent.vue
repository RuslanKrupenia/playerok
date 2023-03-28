<template>
<footer class="footer">
    <div class="footer__container">
        <div class="footer__content">
            <div class="footer__content-list">
                <div class="footer__content-payment">
                    <div class="footer__content-payment-title">Способы оплаты</div>
                    <div class="footer__content-payment-list">
                        <a class="footer__content-payment-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                        <a class="footer__content-payment-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                        <a class="footer__content-payment-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                        <a class="footer__content-payment-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                        <a class="footer__content-payment-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                        <a class="footer__content-payment-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                    </div>
                </div>
                <div class="footer__content-contacts">
                    <div class="footer__content-contacts-title">Мы в соц. сетях</div>
                    <div class="footer__content-contacts-list">
                        <a class="footer__content-contacts-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                        <a class="footer__content-contacts-link" href="#"><img src="https://place-hold.it/40x40/857/857" alt=""></a>
                    </div>
                    <div class="footer__content-contacts-more"><a href="#"> Контакты </a> </div>
                </div>
                <div class="footer__content-information">
                    <div class="footer__content-information-title">Информация</div>
                    <div class="footer__content-information-list">
                        <a class="footer__content-information-link" href="#">Отзывы</a>
                        <a class="footer__content-information-link" href="#">Пользовательское соглашение</a>
                        <a class="footer__content-information-link" href="#">Условия продажи</a>
                        <a class="footer__content-information-link" href="#">Cookie</a>
                        <a class="footer__content-information-link" href="#">Политика конфиденциальности</a>
                        <a class="footer__content-information-link" href="#">Агентский договор</a>
                    </div>
                </div>
            </div>
            <div class="footer__content-information-bottom-text">2023 © Playerok — маркетплейс игровых товаров и услуг. Все права защищены. ООО "МАЯК" ОГРН 1227700204082</div>
        </div>
    </div>
</footer>
</template>

<script>

</script>

<style lang="scss">
.footer{
    background: #fff;
    margin-left: 218px;
    &__container{
        width: 1300px;
        height: 280px;
        margin: 0 auto;
        border-left: 2px solid #F2F4F7;
        border-top: 2px solid #F2F4F7;
    }
    &__content{
        width: 1200px;
        margin: 0 auto;
        &-list{
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }
        &-payment{
            width: 332px;
            height: 150px;
            &-title{
                font-size: 24px;
                font-weight: 800;
                margin-bottom: 20px;
            }
            &-list{
                width: 150px;
                height: 100px;
                display: flex;
                flex-direction: row;
                flex-wrap: wrap;
                justify-content: space-between;
            }
        }
        &-contacts{
            width: 200px;
            height: 150px;
            &-title{
                font-size: 24px;
                font-weight: 800;
                margin-bottom: 20px;
            }
            &-list{
                width: 100%;
                height: 70px;
                display: flex;
            }
            &-link{
                width: 100%;
                height: 40px;
                & img{
                    margin-right: 24px;
                    &:last-child{
                        margin-right: 0;
                    }
                }
            }
            &-more{
                & a{
                    color: #2a53ff;
                    text-decoration: none;
                    display: flex;
                    align-items:end;
                }
            }
        }
        &-information{
            width: 520px;
            height: 150px;
            margin-bottom: 56px;
            &-title{
                font-size: 24px;
                font-weight: 800;
                margin-bottom: 20px;
            }
            &-list{
                width: 100%;
                height: 60px;
                display: flex;
                flex-direction: row;
                flex-wrap: wrap;   
            }
            &-link{
                font-size: 16px;
                margin-right: 30px;
                text-align: center;
                text-decoration: none;
                color: #000;
                &:last-child{
                    margin-right: 0;
                }
            }
        }
        &-bottom-text{
            color: #828794;
            
        }
    }
}
</style>