<template>
    <div class="section paddingtop">
        <h3 class="sec-title sub-title" id="deal-title">Featured Deals</h3>
        <div class="card-m-container">
            <div class="card-big-container" id="deal_8248">
                <div class="card-big">
                    <a href="https://ambankspot.com/deal/8248/15-off">
                        <div class="img-container">
                            <div class="img-content">
                                <img class="img"
                                    src="https://ambankspot.com/wp-content/uploads/2022/10/Harriston-Choc-CV.jpg">
                                <div class="card-star"><img class="img"
                                        src="https://ambankspot.com/wp-content/themes/ambankspot/ui-img/icn-star.png">
                                </div>
                                <div class="card-logo"><img
                                        src="https://ambankspot.com/wp-content/uploads/2021/10/HarristonChocolatier-Logo-1-1.jpg">
                                </div>
                            </div>
                        </div>
                        <div class="info">
                            <div class="title product-title">Harriston Chocolate</div>
                            <div class="des body-copy">15% OFF</div>
                            <div class="cta body-copy">Learn More</div>
                        </div>
                        <div class="clearfix"></div>
                    </a>
                </div>
            </div>
            <div class="clearfix"></div>
        </div>
        <div class="card-m-container-loc" style="display:none"> </div>
    </div>
</template>

<script>

</script>

<style scoped>
.section {
    padding-bottom: 55px;
    margin: auto;
}

.section .paddingtop {
    padding-top: 130px;
}

.sub-title {
    font-size: 24px;
    letter-spacing: 0.5px;
    line-height: 30px;
    font-weight: bold;
}

.card-big-container {
    padding-bottom: 20px;
}

.card-big-container,
.btm-section-container {
    width: 33.3%;
    float: left;
}

.card,
.card-big,
.hcard,
.btm-section {
    transition: all 0.5s ease;
}

.card-big {
    width: calc(100% - 20px);
    float: left;
    margin: 0 10px;
    cursor: pointer;
    border-radius: 5px;
    -moz-border-radius: 5px;
    -webkit-border-radius: 5px;
    overflow: hidden;
    border: 1px solid #e8e8e8;
}

.card-big .img-container,
.card .img-container {
    position: relative;
}

.card-big .img-content,
.card .img-content {
    position: relative;
}

.card-big .img-content .img,
.card .img-content .img {
    width: 100%;
    height: 100%;
    overflow: hidden;
}

.card-big .img,
.card .img {
    z-index: 0;
    top: 0;
    left: 0;
}

.card-big .img-container .card-star {
    background-color: #ffe924;
    height: 50px;
    width: 50px;
    position: absolute;
    top: 8px;
    left: 8px;
    z-index: 2;
    -webkit-box-shadow: 0px 4px 6px 0px rgb(0 0 0 / 35%);
    -moz-box-shadow: 0px 4px 6px 0px rgba(0, 0, 0, 0.35);
    box-shadow: 0px 4px 6px 0px rgb(0 0 0 / 35%);
    margin: auto;
}

.card-big .img-container .card-star img {
    padding: 11px;
}

.card-big .card-star .img {
    width: auto;
    height: auto;
}

.card-big .img-container .card-logo,
.card .img-container .card-logo {
    position: absolute;
    bottom: 0;
    left: 15px;
    z-index: 2;
    height: 24px;
    padding: 8px;
    background-color: #fff;
    -webkit-border-top-left-radius: 3px;
    -webkit-border-top-right-radius: 3px;
    -moz-border-radius-topleft: 3px;
    -moz-border-radius-topright: 3px;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px;
}

.card-big .img-container .card-logo img,
.card .img-container .card-logo img {
    height: 100%;
}

.card-big .info,
.card .info {
    padding: 20px 17px;
    height: 120px;
    position: relative;
}

.card-big .info .title,
.card .info .title,
.hcard .info .title {
    margin-bottom: 10px;
    color: #303031;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    max-height: 23px;
    -webkit-line-clamp: 1;
    -webkit-box-orient: vertical;
}

.product-title {
    font-size: 18px;
    letter-spacing: 0.5px;
    line-height: 24px;
    font-weight: bold;
}

.card-big .info .des,
.card .info .des {
    color: #5F6062;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    max-height: 62px;
    -webkit-line-clamp: 3;
    -webkit-box-orient: vertical;
}

.body-copy,
p {
    font-size: 14px;
    letter-spacing: 0.3px;
    line-height: 20px;
}

.card-big .info .cta,
.card-big .info .cta a,
.card .info .cta,
.card .info .cta a {
    position: absolute;
    bottom: 10px;
    font-weight: bold;
}

.card-big .info .cta:after,
.card .info .cta:after,
.hcard .info .cta:after,
#read-more>div>div>span:after {
    content: url(https://ambankspot.com/wp-content/themes/ambankspot/ui-img/btn-learn-more.svg);
    left: 9px;
    position: relative;
}
</style>