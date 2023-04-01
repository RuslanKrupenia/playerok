<template>
<section class="chats">
<div class="chats__container">
    <div class="chats__content">
        <div class="chats__title"> Чаты</div>
            <div class="chats__list">
                <div class="chats__item">
                    <div class="chats__item-avatar">
                        <img class="chats__item-avatar-img" src="@/assets/image/avatar.jpg" alt="">
                        <img class="chats__item-avatar-online-img" src="@/assets/image/online-indicator.svg" alt="">
                    </div>
                    <div class="chats__item-content">
                        <div class="chats__item-content-up">
                            <div class="chats__item-content-title">Поддержка</div>
                            <div class="chats__item-content-original">
                                <img src="@/assets/image/original.svg" alt="">
                            </div>
                            <div class="chats__item-content-time">15:20</div>
                        </div>
                        <div class="chats__item-content-down">
                            фівпзш фівшпот фівшгпт фшіщвгпфівп вфіп фвіп фівп вфіп віп фівп іфвп фві
                        </div>

                    </div>
                </div>
                <div class="chats__item">
                    <div class="chats__item-avatar">
                        <img class="chats__item-avatar-img" src="@/assets/image/avatar.jpg" alt="">
                        <img class="chats__item-avatar-online-img" src="@/assets/image/online-indicator.svg" alt="">
                    </div>
                    <div class="chats__item-content">
                        <div class="chats__item-content-up">
                            <div class="chats__item-content-title">Поддержка</div>
                            <div class="chats__item-content-original">
                                <img src="@/assets/image/original.svg" alt="">
                            </div>
                            <div class="chats__item-content-time">15:20</div>
                        </div>
                        <div class="chats__item-content-down">
                            фівпзш фівшпот фівшгпт фшіщвгпфівп вфіп фвіп фівп вфіп віп фівп іфвп фві
                        </div>

                    </div>
                </div>
                <div class="chats__item">
                    <div class="chats__item-avatar">
                        <img class="chats__item-avatar-img" src="@/assets/image/avatar.jpg" alt="">
                        <img class="chats__item-avatar-online-img" src="@/assets/image/online-indicator.svg" alt="">
                    </div>
                    <div class="chats__item-content">
                        <div class="chats__item-content-up">
                            <div class="chats__item-content-title">Поддержка</div>
                            <div class="chats__item-content-original">
                                <img src="@/assets/image/original.svg" alt="">
                            </div>
                            <div class="chats__item-content-time">15:20</div>
                        </div>
                        <div class="chats__item-content-down">
                            фівпзш фівшпот фівшгпт фшіщвгпфівп вфіп фвіп фівп вфіп віп фівп іфвп фві
                        </div>

                    </div>
                </div>
            </div>
    </div>
</div>
<div class="communication__container">
    <div class="communication__content">
        <div class="communication__header">
            <div class="communication__inner">
                <div class="communication__inner-img">
                    <img class="communication__inner-img-photo" src="@/assets/image/avatar.jpg" alt="">
                    <img class="communication__inner-img-online" src="@/assets/image/online-indicator.svg" alt="">
                </div>
                <div class="communication__inner-info">
                    <div class="communication__inner-name">
                        <div class="communication__inner-name-top">Поддержка </div>
                            <img src="@/assets/image/original.svg" alt="">
                        </div>
                        <div class="communication__inner-name-down">Работаем 24/7</div>
                </div>
            </div>

        </div>
        <div class="communication__massage">
            <input class="communication__massage-input" type="text">
        </div>
    </div>
</div>
</section>

</template>


<script>


</script>


<style lang="scss">
.chats{
    background-color: #fff;
    display: flex;
    &__container{
        width: 450px;
        margin: 0;
    }
    &__content{
        border-right: 1px solid #f2f4f7 ;
        width: 450px;
        height: 100vh;
    }
    &__title{
        font-family: 'Inter Bold';
        height: 92px;
        display: flex;
        align-items: center;
        font-size: 24px;
        margin-left: 50px;
    }
    &__list{
        width: 100%;
        height: 80vh;
    }
    &__item{
        width: 100%;
        height: 92px;
        background-color: #f2f4f7;
        display: flex;
        padding: 6px 7px 0px 40px;
        &-avatar{
            margin-right: 10px;
            &-img{
                width: 68px;
                height: 68px;
                border-radius: 50%;
            }
            &-online-img{
                position: relative;
                top: -15px;
                right: -50px;
            }
        }

        &-content{
            width: 285px;
            max-height: 70px;
            &-up{
                width: 100%;
                display: flex;
                height: 28px;
                align-items: center;
            }
            &-title{
                font-family: 'Inter Bold';
                margin-right: 8px;
                font-size: 1.125rem;
                line-height: 155%;
            }
            &-original{
                width: 18px;
                height: 18px;
                & img{
                    width: 18px;
                    height: 18px;
                }
            }
            &-time{
                margin-left: auto;
                color: #828794;
            }
            &-down{
                width: 285px;
                max-height: 40px;
                overflow: hidden;
                font-size: 1rem;
                color: #828794;
                line-height: 120%;
            }
        }
    }
}
.communication{
    &__container{
        margin: 20px;
        width: 100%;
    }
    &__content{
        max-width: 100%;
        min-height: 100vh;
    }
    &__header{
        width: 100%;
        height: 95px;
    }
    &__inner{
        display: flex;
        justify-content: space-between;
        width: 165px;
        height: 45px;
        &-img{
            width: 40px;
            height: 40px;
            &-photo{
                border-radius: 50%;
                width: 40px;
                height: 40px;
            }
            &-online{
                width: 12px;
                height: 12px;
                position: relative;
                top: -10px;
                right: -30px;
            }
        }
        &-info{
            width: 116px;
            height: 45px;
        }
        &-name{
            justify-content: space-between;
            display: flex;
            white-space: nowrap;
            align-items: center;
            & img{
                width: 16px;
                height: 16px;
                display: flex;
                align-items: center;
            }
            &-top{
                font-family: 'Inter Bold';
                font-size: 1rem;
                line-height: 160%;
            }
            &-down{
                color: #828794;
                font-size: 0.875rem;
                line-height: 170%;
            }
        }
    }
    &__massage{
        height: 52px;
        width: 1550px;
        &-input{
            width: 100%;
            height: 100%;
        }
    }
}

</style>