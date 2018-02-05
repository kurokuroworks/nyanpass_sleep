<template>
  <div class="index">
    <div class="welcome">
      <div class="message">
        <h1>Twitterサークル検索サービス</h1>
        <h1><span class="title">「にゃんぱす！」</span></h1>
        <img src="../assets/building_bigsight.png">
      </div>
      <div class="cutter"></div>
    </div>

    <div class="info container center">
      <div class="section">
        <h2>おやすみ中</h2>
        <p>にゃんぱす！をご利用いただきありがとうございます。</p>
        <p>本サービスはコミックマーケット開催期間前後に役立つ機能を提供しています。</p>
        <p>現在は<span class="strike">サーバー費用が苦しい</span>閑散期の為、サービスの機能を一時的に停止しております。</p>
        <p>ご不便をおかけいたしますが、サービス再開までしばらくお待ち下さい。</p>
        <p>※現在、再開時期は未定です(2017/02/01更新)</p>
      </div>
      <div class="section">
        <p><a href="https://www.kurokuroworks.net/">サークルページはこちら</a></p>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Sleep'
  }
</script>

<style lang="scss" scoped>
  .index {
    padding-bottom: 100px;
  }
  .welcome {
    background-image: url("../assets/welcome.jpg");
    background-size: cover;
    background-position: center;
    overflow: hidden;
    .message {
      text-align: center;
      margin: 30px 0 60px;
      height: 400px;
      img {
        height: 140%;
        overflow: hidden;
        filter: drop-shadow(0 0 20px rgba(0,0,0,0.5));
      }
      h1 {
        font-size: 30px;
        padding: 5px;
        color: #ffffff;
        .title {
          font-size: 35px;
        }
      }
    }
  }
  .section {
    margin-bottom: 20px;
  }
  .info {
    h2 {
      margin: 0;
      font-size: 1.6rem;
    }
    p {
      margin: 0;
    }
  }
  .welcome .cutter {
    position: relative;
    background-color: #555;
    width: 120%;
    height: 200px;
    margin: 0 -10% -150px;
    transform: rotate(3deg);
  }
  .welcome .cutter:before {
    content: "";
    position: absolute;
    width: 120%;
    height: 400px;
    margin: 0 -10%;
    background: #fafafa;
    transform: rotate(-6deg);
  }

</style>