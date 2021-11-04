<template>
    <div class="top">
        <p class="main">育路出国留学网-专注出国留学提供高质量的留学规划服务</p>
        <div class="header">
            <div class="left">
                <div class="logo"><img src="../assets/yuloo-logo.png" alt=""></div>
                <div class="text">
                    <h2>出国留学</h2>
                </div>
            </div>
            <div class="right">
                <button>☰</button>
            </div>
        </div>
        <div class="banner">
            <img src="../assets/banner2.jpg" alt="">
        </div>
        <p class="main">当前位置：首页>出国留学网</p>
    </div>
</template>
<style lang="less">
.top{
    width: 100%;
    .main{
        padding: 0.1rem;
        box-sizing: border-box;
        width: 100%;
        font-size: .13rem;
        text-overflow: ellipsis;
        white-space: nowrap;
        overflow: hidden;
        color: #838c94;
    }
    .header{
        width: 100%;
        // height: .5rem;
        background: #fff;
        padding: 0.1rem;
        box-sizing: border-box;
        display: flex;
        justify-content: space-between;
        .left{
            width: 70%;
            display: flex;
            justify-content: space-between;
            .logo{
                width: 50%;
                img{
                    width: 100%;
                }
            }
            .text{
                width: 50%;
                h2{
                    font-size: .15rem;
                    padding: .1rem;
                    width: 60%;
                    text-align: center;
                    border-radius: .1rem;
                    color: #fff;
                    background:url('../assets/jb.jpg') no-repeat center center;
                }
            }
        }
        .right{
            width: 30%;
            button{
                height: 100%;
                float: right;
                background: #fff;
                padding: 0 .2rem;
                border: .02rem solid #ccc;
                border-radius: .1rem;
                color: #ccc;
            }
        }
    }
    .banner{
        height: 1.1rem;
        width: 100%;
        img{
            width: 100%;
        }
    }
}
</style>