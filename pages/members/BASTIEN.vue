<template>
    <div class="content">
        <div class="card">
            <div class="card-nav">
                <h3>Le Chat de Bastien</h3>
            </div>

            <div class="card-body">
                <div class="card card-cat">
                    <div class="card-nav">
                        <h3>Chatouille</h3>
                    </div>
        
                    <div class="card-body">
                        <img src="/public/ourCats/chatouille.jpg " alt="Chatouille">
                        <p v-html="$t('cats.Chatouille')"></p>
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