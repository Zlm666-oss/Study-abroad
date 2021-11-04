<template>
    <div class="head">
        <div class="head_con">
            <div class="head_con_nav">
                <a href="#">
                    <img src="http://cg.yuloo.com/images/yuloo-logo.png" alt="">
                </a>
                
                <h1>出国留学</h1>
                <button class="btn">
                    <span class="line">——</span>
                    <span class="line">——</span>
                </button>
            </div>
        </div>
    </div>
</template>
<style lang="scss">
    .head{
        width: 100%;    
        background-color: #fff;
        .head_con{
            width: 95%;
            margin: 0 auto;
            .head_con_nav{
                padding: .1rem 0;
                height: .5rem;
                line-height: .5rem;
                a{
                    float: left;
                    width: 0.84rem;
                    height: 0.5rem;
                    img{
                        width: .84rem;
                        height: .24rem;
                        margin-top: .1rem;
                    }
                }
                h1{
                    text-align: center;
                    background: url(http://cg.yuloo.com/images/public/jb.jpg) no-repeat center center;
                    font-size: .12rem;
                    color: #fff;
                    padding: 0 15px;
                    height: .3rem;
                    line-height: .3rem;
                    border-radius: 3px;
                    float: left;
                    margin-top: .1rem;
                }
                .btn{
                    float: right;
                    width: .44rem;
                    height: .34rem;
                    margin-right: 15px;
                    background-color: transparent;
                    background-image: none;
                    border: 1px solid #ccc;
                    border-radius: 4px;
                    margin-top: .1rem;
                    .line{
                        display: inline-block;
                        height: .1rem;
                        color: #888;
                    }
                }
            }
        }
    }
</style>