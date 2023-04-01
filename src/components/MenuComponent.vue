<template>
<section class="header">
    <div class="header__content">
        <div class="header__menu">
            <div class="header__menu-container">
                <div class="header__menu-logo">
                    <img src="https://playerok.com/og_playerok.png" alt="">
                    <ul class="header__menu-list">
                      <li class="header__menu-item header__menu-item-search"><a class="header__menu-link header__menu-link-search " href="#"><img src="@/assets/image/search.svg" alt="">Поиск</a></li>
                      <li class="header__menu-item header__menu-item-sell"><a class="header__menu-link header__menu-link-sell" href="#"><img src="@/assets/image/sell.svg" alt="">Продать</a></li>
                      <li class="header__menu-item header__menu-item-chats"><a class="header__menu-link header__menu-link-chats" href="#"><img src="@/assets/image/chat.svg" alt="">Чаты</a></li>
                      <li class="header__menu-item header__menu-profile"><a class="header__menu-link header__menu-link-profile" href="#"><img src="@/assets/image/profile.svg" alt="">Профиль</a></li>
                    </ul>
                </div>

            </div>
          </div>
    </div>
</section>
</template>

<style lang="scss">
.header{
    background: #fff;
    height: 100%;
    &__content{
        display: flex;
        width: 220px;
      height: 100%;
    }
    &__menu{
        width: 220px;
        border-right: 2px solid #F2F4F7;
        &-container{
            height: 100%;
            width: 100%;
            margin: 0 auto;
        }
        &-logo{
            width: 220px;
            height: 115px;
            position: sticky;
            top: 0;
            padding: 0;
            border-right: 2px solid #F2F4F7;
        }
        &-list{
            position: sticky!important;
            top: 0px!important;
            padding: 0!important;
        }
        &-item{
            width: 220px;
            height: 55px;
            display: flex;
            align-items: center;
            position: -webkit-sticky;
            position: sticky;
            &-search{
                background-color: #F2F4F7;
            }
        }
        &-link{
            display: flex;
            text-decoration: none;
            width: 100%;
            height: 100%;
            align-items: center;
            
            &-search{
                color: #1453ff;
                background-color: #F2F4F7;
            }
            & img{
                width: 24px;
                height: 24px;
                margin-right: 10px;
                margin-left: 20px;
            }
            &:hover{
                color: #1453ff;
            }
        }

    }
}
</style>