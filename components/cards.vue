<template>
    <div class="container">
        <ul>
            <li>
                <a href="tel:+989399308958">
                    <div><img src="~/static/icons/phone.svg" alt="phone icon"><p>Call me</p></div>
                </a>
            </li>
            <li>
                <a href="https://www.instagram.com/javanscript__/" target="_blank">
                    <div><img src="~/static/icons/instagram.svg" alt="Instagram icon"><p>Instagram</p></div>
                </a>
            </li>
            <li>
                <a href="https://t.me/JavanScript" target="_blank">
                    <div><img src="~/static/icons/telegram.svg" alt="Telegram icon"><p>Telegram</p></div>
                </a>
            </li>
            <li>
                <a href="https://github.com/JavanScript/" target="_blank">
                    <div><img src="~/static/icons/github.svg`" alt="Github icon"><p>Github</p></div>
                </a>
            </li>
            <li>
                <a href="mailto: hosseinJavanbakht96@gmail.com" target="_blank">
                    <div><img src="~/static/icons/email.svg" alt="Email icon"><p>Email</p></div>
                </a>
            </li>
            <li>
                <a href="https://www.linkedin.com/in/hossein-javanbakht-98046a18b/" target="_blank">
                    <div><img src="~/static/icons/linkedin.svg" alt="linkedin icon"><p>linkedin</p></div>
                </a>
            </li>
        </ul>
    </div>
</template>

<style scoped>
ul{
    list-style: none;
    padding: 0;
    margin: 0;
}
li{
    box-sizing: border-box;
    background-color: #c0c0c0;
    height:60px;
    margin: 10px 0;
    padding: 10px 15px;
    border-radius: 5px;
}
a{
    text-decoration: none;
    color: #010d0a;
}
a div{
    display: flex;
    height: 100%;
    align-items: center;
}
a div p{
    margin-left:10px
}
@media screen and (min-width: 768px) {
    a p{
        display: none;
    }
    ul{
        display: flex;
        gap: 25px;
        justify-content: center;
    }
}
</style>