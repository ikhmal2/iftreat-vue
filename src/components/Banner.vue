
<template>
    <div class="hero-banner">
        <div class="hero-banner-bg">
            <div class="banner-content banner-img">
                <div class="banner-copy">
                    <h1 class="line-first">HOT DEALS ON THE SPOT</h1>
                    <h1 class="sline-first">
                        Discover amazing and the best AmBank Credit and Debit Card privileges,
                        offers<br>and deals right here, right now. Exclusively for AmBank Cardholders.
                    </h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style scoped>
.hero-banner {
    background-color: #ef4232;
    height: 383px;
    /* transform: translateY(100px); */
}

.hero-banner-bg {
    height: 383px;
    background-image: url(https://ambankspot.com/wp-content/themes/ambankspot/ui-img/round1.png), url(https://ambankspot.com/wp-content/themes/ambankspot/ui-img/round2.png), url(https://ambankspot.com/wp-content/themes/ambankspot/ui-img/round3.png);
    background-position: left 5% bottom 0, left 50% top 0, right 10% top 0;
    background-repeat: no-repeat;
    background-size: 131px 109px, 431px 107px, 277px 138px;
    border: 1px solid transparent;
}

.banner-content {
    padding-top: 65px;
    max-width: 960px;
    width: 95%;
    height: 100%;
    margin: auto;
}

.banner-content .banner-copy {
    padding-left: 30px;
    padding-top: 100px;
}

.banner-content .banner-copy .line-first {
    color: #fff;
    font-size: 45px;
    font-weight: 400;
    line-height: 50px;
}

.banner-content .banner-copy .sline-first {
    color: #fff;
    font-size: 14px;
    font-weight: 400;
    line-height: 20px;
    letter-spacing: 0.35px;
    margin-top: 20px;
}
</style>