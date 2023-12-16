<template>
  <div class="about">
    <div class="xue">
      <div class="box">
        <div class="head">
          <img src="../assets/1.png">
          <div class="he_1">
            <p><a href="#one">Introduction</a></p>
            <p> <a href="#two">How to buy</a></p>
            <p> <a href="#three">Tokenomics</a></p>
            <p> <a href="#four"  >Roadmap</a></p>
            <p> <a  href="#" target="_blank" @click="to()">Stake</a></p>
            <!-- <p> <a  target="_blank" href='' >stake</a></p> -->
            <p style="cursor:pointer;" @click="add"> Connect</p>
          </div>
          <div @click="home" class="he_2">
            Buy now
          </div>
        </div>
        <div class="cen" id="two">
          <div class="cen_1">
            <img class="cen_2" src="../assets/2.png">
            <p class="cen_3_3">
              Comming Soon
            </p>
            <div class="cen_4">
              <div class="cen_5">
                <a href="https://medium.com/@Chucky.Finance">
                  <img src="../assets/a_me.svg">
                </a>
              </div>
              <div class="cen_5">
                <a href="https://twitter.com/ChuckyFinance">
                  <img src="../assets/a_tt.svg">
                </a>
              </div>
              <div class="cen_5">
                <a href="https://www.reddit.com/user/ChuckyFinance">

                  <img src="../assets/a_re.svg">
                </a>
              </div>
              <div class="cen_5">
                <a href="https://discord.gg/X25dWJMjaa">
                  <img src="../assets/d_code.svg">
                </a>
              </div>
              <a href="">
                <img src="../assets/3.png">
              </a>
              <a href="">
                <img src="../assets/4.png">
              </a>
            </div>
            <div class="cen_6">
              <a href="https://etherscan.io/address/0x80b82a600c023a9d04af806a83d2690948b50938">
                <img class="cen_img1" src="../assets/logd.svg">
              </a>
              <a href="">
                <img class="cen_img2" src="../assets/m.png">
              </a>
              <br>
              <a href="https://www.pinksale.finance/launchpad/0x5924cD063DBC4EB6c6eB22c05292600116f076Cb?chain=ETH">
                <img class="cen_img" src="../assets/9.png">
              </a>
              <div @click="go" class="cen_7">
                <img src="../assets/fz.svg">
                <p>White Paper</p>
              </div>
            </div>
            <div class="cen_8">
              <div class="cen_9">
                <p class="cen_10">
                  {{ remainingDays }}
                  <span>day</span>
                </p>
                <p class="cen_10">
                  {{ remainingHours }}
                  <span>Hours</span>
                </p>
                <p class="cen_10">
                  {{ remainingMinutes }}
                  <span>Minute</span>
                </p>
                <p class="cen_10">
                  {{ remainingSeconds }}
                  <span>Second</span>
                </p>
              </div>
            </div>
          </div>
          <div class="cen_rig">
            <div class="cen_rigty">
              <img src="../assets/5.png">
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="but">
      <div class="but_1">
        <h1> Join the community</h1>
        <div class="but_2">
          <div class="x">
            <div>
              <a href="https://medium.com/@Chucky.Finance">

                <img src="../assets/a_me.svg">
              </a>
            </div>
          </div>
          <div class="x">
            <div>
              <a href="https://twitter.com/ChuckyFinance">
                <img src="../assets/a_tt.svg">
              </a>
            </div>
          </div>
          <div class="x">
            <div>
              <a href="https://www.reddit.com/user/ChuckyFinance">
                <img src="../assets/a_re.svg">
              </a>
            </div>
          </div>
          <div class="x">
            <div>
              <a href="https://discord.gg/X25dWJMjaa">
                <img src="../assets/d_code.svg">
              </a>
            </div>
          </div>
        </div>
        <h2>explorer</h2>
      </div>
      <div class="but_4">
        <div class="">
          <a href="https://etherscan.io/address/0x80b82a600c023a9d04af806a83d2690948b50938">
            <img class="cen_img1" src="../assets/logd.svg">
          </a>
          <a href="">
            <img class="cen_img2" src="../assets/m.png">
          </a>
          <br>
          <a href="https://www.pinksale.finance/launchpad/0x5924cD063DBC4EB6c6eB22c05292600116f076Cb?chain=ETH">
            <img class="cen_img4" src="../assets/9.png">
          </a>
        </div>
      </div>
      <div class="but_5">
        <div class="but_6">
          <img src="../assets/1.png">
          <h2>CHUCKY COIN</h2>
          <p>"ETERNAL VIGILANCE, ETERNAL VALUE: CHUCKY COIN - THE SCAM KILLER'S CHOICE."
          </p>
        </div>
        <div class="but_7">
          <h2>QUICK LINKS</h2>
          <p><a href="#one">Introduction</a></p>
          <p> <a href="#two">How to buy</a></p>
          <p> <a href="#three">Tokenomics</a></p>
          <p> <a href="#four">Roadmap</a></p>
          <p><a
              href="https://cdn.shopify.com/s/files/1/0822/1897/5515/files/Chucky_Whitepaper_Final.pdf?v=1694154673">White
              Paper</a> </p>
        </div>
        <div class="but_7">
          <h2><a href="https://chucky.finance/influencerrs">DESTINATIONS</a> </h2>
          <p> FAQ</p>
          <p> Privacy policy</p>
          <p>Term of service</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import moment from 'moment';
export default{
  data(){
    return{
      targetDate: moment().add(48, 'days'),
      remainingDays: '',
      remainingHours: '',
      remainingMinutes: '',
      remainingSeconds: ''
    }
  },
  methods: {
    go() {
      console.log(moment().format('LTS'))
    },
    to(){
      // this.$router.push('/about');
      // window.open(routeUrl.href, '_blank')
    },
    home(){
      this.$router.push('/');
    },
    add(){
      main();
    }
  },
  mounted() {
    this.timer = setInterval(() => {
      const now = moment();
      const timeDiff = this.targetDate.diff(now);

      if (timeDiff <= 0) {
        clearInterval(this.timer);
        this.remainingDays = '0';
        this.remainingHours = '0';
        this.remainingMinutes = '0';
        this.remainingSeconds = '0';
      } else {
        this.remainingDays = Math.floor(timeDiff / (1000 * 60 * 60 * 24));
        this.remainingHours = Math.floor((timeDiff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        this.remainingMinutes = Math.floor((timeDiff % (1000 * 60 * 60)) / (1000 * 60));
        this.remainingSeconds = Math.floor((timeDiff % (1000 * 60)) / 1000);
      }
    }, 1000);
  },
  beforeDestroy() {
    clearInterval(this.timer);
  },
}
</script>
<style>
.about{
  /* max-width: 1800px; */
  width: 100%;
  margin: 0 auto;
  /* background-color: white; */  
  overflow: hidden;
}

.xue {
  width: 100%;
  /* // height: 100vh; */
  margin: 0 auto;
  padding-bottom: 10rem;
  background-image: url('../assets/bj_2.jpg');
  background-size: 100% 100%;
}

.box {
  width: 70%;
  margin: 0 auto;
  /* // border: 1px red solid; */
}

.head {
  height: 6rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 2rem;
}

.head>img {
  width: 97px;
  height: 97px;
}

.he_1 {
  width: 65%;
  display: flex;
  font-family: four;
  color: white;
  font-size: 1.5rem;
  line-height: 2rem;
  font-weight: 500;
  font-size: 20px;
  justify-content: space-between;
  cursor: zoom-in;
}

.he_1>p>a {
  color: white;
}

.he_1>p>a:hover {
  text-decoration: underline;
}

.he_2 {
  color: white;
  width: 6rem;
  height: 2.8rem;
  border: 1px red solid;
  text-align: center;
  line-height: 2.8rem;
  border: 3px red solid;
  border-radius: 10px;
  background-color: rgb(222, 37, 45);
  position: relative;
  cursor: pointer;

  /* // background-color: pink; */
}

.he_2::before,
.he_2::after {
  content: '';
  position: absolute;
  top: -3px;
  bottom: 0;
  width: 100%;
  height: 3rem;
  border-radius: 10px;
  transition: border-color 1s linear;
}

.he_2::before {
  left: -2px;
  border: 2px solid blue;
  border: 2px solid transparent;
}

.he_2::after {
  right: 0;
  border-right: 2px solid blue;
  border: 2px solid transparent;
}

.he_2::before,
.he_2:hover::after {
  border-color: pink;
}

.cen {
  max-width: 2000px;
  width: 100%;
  display: flex;
  margin: 0 auto;
}

.cen_1 {
  width: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
  color: white;
}

.cen_2 {
  width: 430px;
  height: 208px;
  /* // margin: 1.5rem 0 1.5rem 0; */
}

.cen_3_3 {
  font-size: 50px;
  text-align: center;
}

.cen_4 {
  width: 60%;
  height: 6rem;
  /* // border: 1px red solid; */
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  /* // background-color: white; */
}

.cen_4>a>img {
  width: 40px;
  height: 40px;
}

.cen_5 {
  width: 40px;
  height: 40px;
  background-color: white;
  border-radius: 5px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cen_img {
  width: 140px;
  height: 40px;
  margin-left: 6rem;
  margin-top: 1rem;
}

.cen_img4 {
  width: 140px;
  height: 40px;
  margin-left: 6rem;
  margin-top: 1rem;
}
.cen_5>a>img {
  width: 30px;
  height: 30px;
}

.cen_img1 {
  width: 140px;
  height: 32px;
  margin-right: 1rem;
}

.cen_img2 {
  width: 211px;
  height: 32px;
}

.cen_7 {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 1rem;
  font-weight: 900;
  font-size: 20px;

}

.cen_7>img {
  width: 18px;
  height: 28px;
}

.cen_8 {
  width: 100%;
  display: flex;
  justify-content: center;
  margin: 2rem 0 2rem 0;
}

.cen_8>P {
  font-size: 50px;
  font-weight: 900;
}

.cen_9 {
  width: 100%;
  display: flex;
  justify-content: space-around;
}

.cen_10 {
  display: flex;
  font-size: 70px;
  align-items: center;
  flex-direction: column;
  color: red;
  font-weight: 900;
}

.cen_10>span {
  font-weight: 400;
}

.cen_10:nth-child(4) {
  color: white;
}

.cen_10 span {
  font-size: 20px;
}

.cen_rig {
  width: 50%;
}

.cen_rigty {
  width: 100%;
  display: flex;
  justify-content: center;
}

.cen_rigty>img {
  width: 423px;
  height: 710px;
}

.but {
  width: 100%;

  background-image: url('../assets/bj_5.png');
  background-size: 100% 100%;
}

.but_1 {
  width: 80%;
  margin: 0 auto;
  border-top: 2px red solid;
  border-bottom: 2px red solid;
}

.but_1>h1 {
  width: 100%;
  text-align: center;
  font-size: 40px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}


.but_1>h2 {
  width: 100%;
  text-align: center;
  font-size: 30px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}

.but_2 {
  width: 20rem;
  display: flex;
  margin: 0 auto;
  padding-top: 2rem;
  padding-bottom: 5rem;
  justify-content: space-evenly;
}

.x {
  width: 60px;
  height: 60px;
  border-radius: 15px;
  border: 2px red solid;
  background-color: rgba(220, 38, 38, 0.4);
  display: flex;
  justify-content: center;
  align-items: center;

}

.x div {
  width: 50px;
  height: 50px;
  background-color: white;
  display: flex;
  justify-content: center;
  opacity: 0.9;
  align-items: center;
  border-radius: 15px;
}

.x div:hover {
  background-color: #f23131;
}

.x div>a>img {
  width: 30px;
  height: 30px;
}

.but_4 {
  width: 85%;
  margin: 5rem auto;
  display: flex;
  justify-content: center
}

.but_4>div>img {
  width: 140px;
  height: 31px;
  margin-right: 2rem;
}

.but_4>div>img:nth-child(2) {
  width: 211px;
  height: 31px;
}

.but_4>div>img:nth-child(4) {
  width: 140px;
  height: 40px;
 
  margin-left: 6rem;
  margin-top: 2rem;
}

.but_5 {
  width: 80%;
  margin: 0 auto;
  display: flex;
  justify-content: center
}

.but_6 {
  width: 30rem;
  display: flex;
  color: white;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.but_6>img {
  width: 97px;
  height: 95px;
}

.but_6>h2 {
  margin: 2rem 0 01rem;
  font-size: 24px;
}

.but_6>p {
  font-size: 21px;
}

.but_7 {
  width: 30rem;
  display: flex;
  color: white;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.but_7>h2 {
  margin-bottom: 2rem;
}

.but_7>h2>a {
  color: white;
}

.but_7>p>a {
  color: white;
  line-height: 2.5rem;
}

.but_7>p {
  font-size: 22px;
  line-height: 30px;
}

@media (max-width: 600px) {

  .box {
    width: 98%;
  }

  .he_1 {
    display: none;
  }

  .cen {
    flex-direction: column;
    align-items: center;
  }

  .cen_1 {
    width: 90%;
  }

  .cen_2 {
    width: 300px;
    height: 150px;
  }

  .cen_3 {
    font-size: 25px;
  }

  .cen_img2 {
    width: 181px;
  }

  .cen_4 {
    width: 85%;
  }

  .cen_rigty>img {
    display: none;
  }

  .xue {
    padding-bottom: 0;
  }

  .mggo {
    width: 98%;
    flex-direction: column;
  }

  .mggo_1>img {
    width: 382px;
    height: 579px;
  }

  .mggo_2 {
    width: 98%;
  }

  .mgo_4 {
    display: none;
  }

  .mgo_5 {
    display: none;
  }

  .mgo_6 {
    display: none;
  }

  .mgo_7 {
    display: none;
  }

  .rdios {
    width: 95%;
    align-items: center;
    flex-direction: column;
  }

  .rdiosd {
    width: 95%;
  }

  .rdiosd>span {
    font-size: 14px;
  }

  .rdiosx {
    width: 90%;
  }
  .sj_h1 > h1{
    font-size: 40px
  }
  .sj_biaot{
    width: 99%;
    flex-direction: column
  }
  .sj_bio > h1{
    font-size: 1.5rem;
  }
  .sj_bio{
    width: 99%;
  }
  .but_4>div{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .but_4>br{
    display: none;
  }
  .cen_img4{
    margin-top: -1rem;
    margin-left: 0;
  }
  .but_5{
    flex-direction: column;
    align-items: center;
  }
  .but_6{
    width: 23rem;
  }
  .but_7{
    width: 23rem;
  }
  .dao_t{
    font-size: 25px
  }
}
</style>