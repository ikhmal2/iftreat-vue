<template>
    <div class="filter-container">
        <div class="filter-deals">
            <div class="copy">
                <h2 class="filter-title sub-title">Unleash The Deals</h2>
                <p>
                    Embark on an exciting journey of deals and promotions below. You can also filter according to your
                    interests, for even better suggestions.
                </p>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
.filter-container {
    position: relative;
    width: 100%;
    z-index: 10;
}

.filter-deals {
    height: 55px;
    padding: 30px 0;
    margin-top: -30px;
    z-index: 6;
    position: absolute;
    width: 100%;
    background-color: #FFE926;
    border-radius: 8px 8px 8px 8px;
    -moz-border-radius: 8px 8px 8px 8px;
    -webkit-border-radius: 8px 8px 8px 8px;
    -webkit-box-shadow: 0px 4px 6px 0px rgb(0 0 0 / 35%);
    -moz-box-shadow: 0px 4px 6px 0px rgba(0, 0, 0, 0.35);
    box-shadow: 0px 4px 6px 0px rgb(0 0 0 / 35%);
}

.filter-deals .copy {
    float: left;
    padding-left: 40px;
}

.filter-deals p {
    color: #5F6062;
    font-size: 13.5px;
    letter-spacing: 0px;
    line-height: 20px;
    padding-top: 5px;
}

.filter-deals .filter-title {
    color: #EF4233;
}

.sub-title {
    font-size: 24px;
    letter-spacing: 0.5px;
    line-height: 30px;
    font-weight: bold;
}
</style>