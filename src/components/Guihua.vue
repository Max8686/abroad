<template>
  <div class="index">
    <h2>
      <img src="../assets/lxy/Snipaste_2021-11-04_14-56-17.png" alt="" />
      出国留学最新资讯
    </h2>
    <!--  -->
    <div class="lx">
      <h4>出国留学人群</h4>
      <div class="lx-li">
        <li>我要读高中</li>
        <li>我要读高中</li>
        <li>我要读高中</li>
      </div>
    </div>

    <div class="lx">
      <h4>主要留学途径</h4>
      <div class="lx-li">
        <li>留学预科</li>
        <li>留学预科</li>
        <li>留学预科</li>
      </div>
    </div>

    <div class="lx">
      <h4>出国留学国家</h4>
      <div class="lx-li-yg">
        <li>
          <span>
            <img src="../assets/lxy/yg.jpg" alt="" />
          </span>
          英国
        </li>
        <li>
          <span>
            <img src="../assets/lxy/yg.jpg" alt="" />
          </span>
          英国
        </li>
        <li>
          <span>
            <img src="../assets/lxy/yg.jpg" alt="" />
          </span>
          英国
        </li>
      </div>
      <div class="lx-li-yg">
        <li>
          <span>
            <img src="../assets/lxy/yg.jpg" alt="" />
          </span>
          英国
        </li>
        <li>
          <span>
            <img src="../assets/lxy/yg.jpg" alt="" />
          </span>
          英国
        </li>
        <li>
          <span>
            <img src="../assets/lxy/yg.jpg" alt="" />
          </span>
          英国
        </li>
      </div>
    </div>
    <!--  -->
    <div class="back">
      <h4>出国留学有问必答</h4>
      <div class="input">
        <input type="text" placeholder="学生姓名" />
        <input type="tel" placeholder="手机号码" />
      </div>
      <div class="input">
        <input placeholder="出生年月" type="month" />
        <select>
          <option value="">请选择意向学校</option>
        </select>
      </div>
      <div class="input">
        <select>
          <option value="">请选择学历</option>
        </select>
        <textarea name="" id="" cols="30" rows="10" placeholder="你的疑问"></textarea>
      </div>
      <!--  -->
      <div class="button">
          <span class="span">立即提交</span>
          <span>《隐私保证》</span>
      </div>
    </div>
  </div>
</template>
<style scoped lang='less'>
.index {
  width: 95%;
  background: white;
  margin: 0 auto;
  h2 {
    display: flex;
    align-items: center;
    font-size: 0.21rem;
  }
  h2 img {
    width: 8%;
    height: 8%;
    margin: 0.1rem;
  }
  //
  .lx {
    margin-bottom: 20px;
    h4 {
      margin-left: 15px;
      margin-bottom: 5px;
    }
    .lx-li {
        width: 90%;
        margin: 0 auto;
      display: flex;
      justify-content: space-around;
      li {
        float: left;
        border: 0.01rem solid #c0c9e4;
        color: #36477a;
        background: #fcfdff;
        padding: 0.02rem 0.1rem;
        border-radius: 0.04rem;
      }
    }
    .lx-li-yg {
        width: 90%;
        margin: 0 auto;
      display: flex;
      justify-content: space-around;
      span {
          width: 40%;
          height: 100%;
        img {
          width: 100%;
          height: 100%;
          float: left;
        }
      }
      li {
        display: flex;
justify-content: space-around;
        float: left;
        border: 0.01rem solid #c0c9e4;
        color: #36477a;
        background: #fcfdff;
        padding: 0.02rem 0.1rem;
        border-radius: 0.04rem;
        margin-bottom: 10px;
      }
    }
  }
  //
  .back {
      width: 95%;
      margin: 0 auto;
    // height: 2rem;
    background-image: url(../assets/lxy/order-form-bg.jpg);
    h4 {
      margin-left: 15px;
      margin-bottom: 5px;
    }
    .input {
        margin-bottom: 10px;
      display: flex;
      justify-content: space-evenly;
      input {
        width: 40%;
        height: 0.3rem;
      }
    }
    select {
        width: 41%;
        height: 0.35rem;
    }
    textarea{
        width: 40%;
        height: 0.35rem;
        line-height: 0.35rem;
    }
    .button{
            display: flex;
    flex-direction: column;
    align-items: center;
        .span{
            width: 1.5rem;
            height: 0.3rem;
            line-height: 0.3rem;
            text-align: center;
            background: #cc8b59;
    border: 1px solid #cc8b59;
    color: white;
    border-radius: 0.02rem;
    margin: 10px 10px;
    font-size: 0.2rem;
        }
        span{
            font-size: 0.1rem;
        }

    }
  }
}
</style>