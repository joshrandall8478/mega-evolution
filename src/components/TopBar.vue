<template>
    <nav>
        <div class="nav__container">

            <div class="logo__container">
                <img id="nav__logo" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/48ebc6c4-0ade-41ab-8548-5238e975dd0e/d88i1ut-6e28999e-4c18-474b-b9fd-f670558caa63.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzQ4ZWJjNmM0LTBhZGUtNDFhYi04NTQ4LTUyMzhlOTc1ZGQwZVwvZDg4aTF1dC02ZTI4OTk5ZS00YzE4LTQ3NGItYjlmZC1mNjcwNTU4Y2FhNjMucG5nIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.KfaFDYSHOMRL3ZwnAOtqapcu7RIirFJStnxEmguA5SQ" alt="">
            </div>
            <div class="item__container">
                <ul class="nav__items">
                    <li class="nav__link">
                        Home
                    </li>
                    <li class="nav__link">
                        About
                    </li>
                    <li class="nav__link">
                        Repo
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>
<style scoped>
nav{
    display: block;
    position: fixed;

    top: 0;
    left: 0;
    background-color: gray;
    width: 100vw;
    height: 100px;
    z-index: 999;
}
.nav__container{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 50px;
    margin: 0px 50px;
}
#nav__logo{
    display: flex;
    width: 50px;
    height: auto;
}

.nav__items{
    display: flex;
    align-self: center;

}
.nav__link{
    padding: 0px 25px;
    list-style: none;
    font-size: 2em;
}
</style>