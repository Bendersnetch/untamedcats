<template>
    <div class="content">
        <div class="card">
            <div class="card-nav">
                <h3>Les Chats de Federico</h3>
            </div>

            <div class="card-body">
                <div class="card card-cat">
                    <div class="card-nav">
                        <h3>Trilly</h3>
                    </div>
        
                    <div class="card-body">
                        <img src="../workspace/public/ourCats/trilly.jpg " alt="Trilly">
                        <p v-html="$t('cats.Trilly')"></p>
                    </div>
                </div>
        
                <div class="card card-cat">
                    <div class="card-nav">
                        <h3>Gigi</h3>
                    </div>
        
                    <div class="card-body">
                        <img src="../workspace/public/ourCats/gigi.jpg " alt="Gigi">
                        <p v-html="$t('cats.Gigi')"></p>
                    </div>
                </div>
        
                <div class="card card-cat">
                    <div class="card-nav">
                        <h3>Luna</h3>
                    </div>
        
                    <div class="card-body">
                        <img src="../workspace/public/ourCats/luna.png " alt="Luna">
                        <p v-html="$t('cats.Luna')"></p>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<style scoped>
.card-cat {background-color: #fff;}
p {text-align: center; margin-top: 30px;}
img {display: block; margin: 0 auto; width: 300px; border-radius: 25px; box-shadow: 5px 5px 15px;}
</style>