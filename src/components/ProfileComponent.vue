<template>
<section class="profile">
    <div class="profile__container">
        <div class="profile__content">
            <div class="profile__title">Регистрация или вход</div>
            <div class="profile__acces-form">
                <a href="" class="profile__acces-login-vk-link">
                    <div class="profile__acces-login">
                        <img src="@/assets/image/icon-vk.svg" alt="">
                        <p>Войти через Вконтакте</p>
                    </div>
                </a>
                <a href="" class="profile__acces-login-google-link">
                    <div class="profile__acces-login">
                        <img src="@/assets/image/icon-google.svg" alt="">
                        <p>Войти через Google</p>
                    </div>
                </a>
                <label class="profile__acces-input-item">
                    <input class="profile__acces-input" type="mail">
                    <span>Адрес електронной почты</span>
                </label>>
                <a class="profile__acces-button-link" href="#"><div class="profile__acces-button">
                    <div class="profile__acces-button-text">Начать продажу</div>
                 </div> </a>
                <div class="profile__acces-button-text">Нажимая «Начать продажу», Вы принимаете Условия продажи</div>
                    <div class="profile__acces-subtext">Продолжая регистрацию или вход вы принимаете условия <a href="#">Пользовательского соглашения</a> и <a href="#">Политики конфиденциальности</a></div>
            </div>
        </div>
    </div>
</section>

</template>

<script>

</script>

<style lang="scss">
.profile{
    background-color: #fff;
    min-height: 100vh;
    width: 100%;
    &__container{
        max-width: 1700px;
        margin: 20px auto ; 
    }
    &__content{
        margin-left: 40px;
        max-width: 625px;
        height: 520px;
    }
    &__title{
        width: 100%;
        height: 95px;
        font-size: 1.5rem;
        line-height: 135%;
        font-weight: 800;
    }
    &__acces{
        &-form{
            max-width: 515px;
            max-height: 420px;
        }
        &-login{
            display: flex;
            align-items: center;
            width: 100%;
            height: 72px;
            background-color: #f2f4f7;
            margin-bottom: 20px;
            border-radius: 8px;
            padding: 20px 22px 13px;
            &:hover{
                background-color: #e1e3e8;
            }
            &-vk-link,&-google-link{
                text-decoration: none;
            }
            & img{
                margin-right: 5px;
                width: 32px;
                height: 32px;
            }
            & p{
                font-size: 18px;
                color: #1453ff;
            }
        }
        &-input{
            border: none;
            -webkit-appearance: none;
            appearance:none;
            background: #f2f2f2;
            padding: 12px;
            border-radius: 5px;
            width: 100%;
            outline: none;
            &::placeholder{
                position: absolute;
                left: 12px;
                top: calc(50% + 10px);
                transform: translateY(-50%);
                color: #aaa;
            }
            &-item{
                position: relative;
                font-size: 14px;
                padding-top: 20px;
                margin-bottom: 5px;
                
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
        &-subtext{
            width: 100%;
            height: 50px;
            font-size: 14px;
        }
    }
}

</style>