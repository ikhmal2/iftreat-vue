<template>
    <header>
        <div class="content-area">
            <div class="logo">
                <a href="https://ambankspot.com">
                    <img src="https://ambankspot.com/wp-content/themes/ambankspot/ui-img/ambankspot.svg"
                        alt="AmbankSpot">
                </a>
            </div>
            <ul class="top-link">
                <li>
                    <button type="reset" class="search" id="search-btn"></button>
                </li>
                <li class="btn-call">
                    <a href="https://ambankspot.com/contact-us">
                        <img src="https://ambankspot.com/wp-content/themes/ambankspot/ui-img/btn-call.svg">
                    </a>
                </li>
                <div class="clearfix"></div>
            </ul>
            <div class="clearfix"></div>
        </div>
    </header>
</template>

<script>

</script>

<style scoped>
header {
    background-color: #fff;
    position: relative;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 21;
    box-shadow: 0px 13px 10px -18px #111;
}

.content-area {
    max-width: 960px;
    width: 95%;
    margin: auto;
    position: relative;
}

header .logo {
    width: 112px;
    float: left;
    margin-top: 6px;
    margin-bottom: -26px;
}

header .top-link {
    list-style: none;
    display: inline-block;
    height: 100%;
    margin-top: 20px;
    position: absolute;
    right: 0;
    width: 120px;
}

header .top-link li .search {
    background: none;
    position: absolute;
    top: 12px;
    left: 0;
    height: 28px;
    width: 28px;
    padding: 0;
    border-radius: 100%;
    outline: 0;
    color: inherit;
    cursor: pointer;
    -webkit-transition: 0.2s ease-in-out;
    transition: 0.2s ease-in-out;
    border: 5px solid #ef4233;
    cursor: pointer;
}

header .top-link li .search:before {
    content: "";
    position: absolute;
    width: 10px;
    height: 5px;
    -webkit-border-radius: 100px;
    -moz-border-radius: 100px;
    border-radius: 100px;
    background-color: #ef4233;
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(35deg);
    margin-top: 7px;
    margin-left: 10px;
    -webkit-transition: 0.2s ease-in-out;
    transition: 0.2s ease-in-out;
}

header .top-link li.btn-call {
    left: 70px;
    position: absolute;
    top: 10px;
    height: 30px;
    width: 30px;
}
</style>