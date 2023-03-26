<template>
<section class="header">
    <div class="header__content">
        <div class="header__menu">
            <div class="header__menu-container">
                <div class="header__menu-logo">
                    <img src="https://playerok.com/og_playerok.png" alt="">
                </div>
                <ul class="header__menu-list">
                    <li class="header__menu-item"><a class="header__menu-link" href="#"><img src="@/assets/image/search.svg" alt="">Поиск</a></li>
                    <li class="header__menu-item"><a class="header__menu-link" href="#"><img src="@/assets/image/sell.svg" alt="">Продать</a></li>
                    <li class="header__menu-item"><a class="header__menu-link" href="#"><img src="@/assets/image/chat.svg" alt="">Чаты</a></li>
                    <li class="header__menu-item"><a class="header__menu-link" href="#"><img src="@/assets/image/profile.svg" alt="">Профиль</a></li>
                </ul>
            </div>
            </div>
            <div class="header__services">
                <div class="header__services-container">
                    <div class="header__services-content">
                        <div class="header__services-top">
                                <input type="text" placeholder="Поиск игр и приложений" class="header__services-find">
                            <div class="header__services-rating">
                                <div class="header__services-rating-img">
                                    <img src="@/assets/image/star.svg" alt="">
                                    <div class="header__services-rating-text">5.0 <span>718478</span></div>
                                </div>
                            </div>
                        </div>
                        <div class="header__services-categories">
                            <ul class="header__services-categories-list">
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link"><img src="@/assets/image/categories.svg" alt=""></a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Донат</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Аккаунты</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Другое</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Предметы</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Скины</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Буст</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Игровая валюта</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Пополнение баланса</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Подписки</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Аккаунты с играми</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Услуги</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Игры</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Медиа</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Дизайн</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Ключи</a></li>
                                <li class="header__services-categories-item"><a href="#" class="header__services-categories-link">Обучение</a></li>
                            </ul>
                        </div>
                        <div class="header__services-advantages">
                            <div class="header__services-advantages-entertainment">
                                <div class="header__services-advantages-entertainment-img">
                                    <img src="@/assets/image/gamepad.svg" alt="">
                                    <img src="@/assets/image/folder.png" alt="">
                                </div>
                                <div class="header__services-advantages-entertainment-title">Игры и приложения</div>
                                <div class="header__services-advantages-entertainment-subtitle">Все игры и новые приложения! <br> Большой выбор категорий</div>
                            </div>
                            <div class="header__services-advantages-discount">
                                <div class="header__services-advantages-discount-img">
                                    <img src="@/assets/image/procent.png" alt="">
                                </div>
                                <div class="header__services-advantages-discount-title">По скидке</div>
                                <div class="header__services-advantages-discount-subtitle">Товары по скидке до -50%. <br> Покупайте выгодно!</div>
                            </div>
                            <div class="header__services-advantages-reviews">
                                <div class="header__services-advantages-reviews-img">
                                <img src="@/assets/image/star.svg" alt="">
                                </div>
                                <div class="header__services-advantages-reviews-title">С отзывами</div>
                                <div class="header__services-advantages-reviews-subtitle">Только провереные продавцы с отзывами. <br> Покупайте безопасно!</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
</section>
</template>

<script>


</script>

<style lang="scss">
.header{
    background: #fff;
    &__content{
        display: flex;
        width: 1440px;
    }
    &__menu{
        width: 220px;
        border-right: 2px solid #F2F4F7;
        &-container{
            margin: 0 auto;
        }
        &-logo{
            width: 220px;
            height: 115px;
            position: -webkit-sticky;
            position: sticky;
            top: 0;
            padding: 0;
            border-right: 2px solid #F2F4F7;
        }
        &-list{
            position: -webkit-sticky;
            position: sticky;
            top: 115px;
            padding: 0;

        }
        &-item{
            width: 220px;
            height: 55px;
            display: flex;
            align-items: center;
            &:hover{
                background-color: #F2F4F7;
            }
        }
        &-link{
            display: flex;
            text-decoration: none;
            width: 100%;
            
            & img{
                width: 24px;
                height: 24px;
                margin-right: 10px;
                margin-left: 20px;
            }
        }

    }














    &__services{
        min-height: 1000vh;
        width: 100%;
        &-container{
            max-width: 1200px;
            margin: 20px auto ;
        }
        &-content{
            width: 100%;
            height: 100%;
        }
        &-top{
            width: 100%;
            height: 52px;
            display: flex;
            justify-content: space-between;
            margin-bottom: 40px;
        }
        &-find{
            width: 450px;
            height: 50px;
            padding: 11px 12px 13px 52px;
            border-radius: 8px;
            border: none;
            background-color: #F2F4F7;
        }
        &-rating{
            width: 110px;
            height: 50px;
            display: flex;
            align-items: center;
            &-img{
                width: 14px;
                height: 13px;
                display: flex;
                justify-content: space-between;
                align-items: center;
                & img{
                    margin-right: 5px;
                }
            }
            &-text{
                display: flex;
                justify-content: space-between;

                & span{
                    margin-left: 5px;
                    color: #1453ff;
                }
            }
        }
        &-categories{
            width: 100%;
            height: 50px;
            display: flex;
            align-items: center;
            text-align: center;
            overflow: auto;
            margin-bottom: 40px;
            &::-webkit-scrollbar {
              width: 0;
              height: 0;
              background-color: transparent;
            }
  
            &-list{
                display: flex;
                justify-content: space-between;
                width: 100%;
                height: 100%;
            }
            &-item{
                padding: 12px 24px;
                text-align: center;
                display: flex;
                align-items: center;
                background-color: #F2F4F7;
                margin-right: 10px;
                border-radius: 8px;
                white-space: nowrap;
                &:hover{
                    background-color: #e1e3e8;
                }
            }
            &-link{
                text-decoration: none;
                color: #000;
                font-size: 1.125rem;
                line-height: 155%;
                & img{
                    width: 24px;
                    height: 24px;
                }
            }
        }
        &-advantages{
            width: 100%;
            height: 200px;
            display: flex;
            justify-content: space-between;
            text-align: center;
            &-entertainment{
                background-image: url(https://place-hold.it/356x200/bebebe/bebebe);
                height: 100%;
                width: 385px;
                border-radius: 6px;
                align-items: center;
                &-img{
                    width: 84px;
                    height: 36px;
                    display: flex;
                    justify-content: space-between;
                    margin: 20px auto;
                    & img{
                        width: 36px;
                        height: 36px;
                    }
                }
                &-title{
                    font-size: 24px;
                    font-weight: 600;
                    margin-bottom: 5px;
                }
                &-subtitle{
                    font-size: 16px;
                }
            }
            &-discount{
                background-image: url(https://place-hold.it/356x200/fb326/fb326);
                height: 100%;
                width: 385px;
                border-radius: 6px;
                align-items: center;
                &-img{
                    width: 84px;
                    height: 36px;
                    display: flex;
                    justify-content: space-between;
                    margin: 20px auto;
                    & img{
                        border-radius: 40px;
                        width: 84px;
                        height: 36px;
                    }
                }
                &-title{
                    font-size: 24px;
                    font-weight: 600;
                    margin-bottom: 5px;
                }
                &-subtitle{
                    font-size: 16px;
                }
            }
            &-reviews{
                background-image: url(https://place-hold.it/356x200/2861ff/2861ff);
                height: 100%;
                width: 385px;
                border-radius: 6px;
                align-items: center;
                &-img{
                    width: 36px;
                    height: 36px;
                    display: flex;
                    justify-content: space-between;
                    margin: 20px auto;
                    & img{
                        width: 36px;
                        height: 36px;
                    }
                }
                &-title{
                    font-size: 24px;
                    font-weight: 600;
                    margin-bottom: 5px;
                }
                &-subtitle{
                    font-size: 16px;
                }
            }
        }
    }
}
</style>