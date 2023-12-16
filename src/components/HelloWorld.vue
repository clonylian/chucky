<template>
  <div class="hello">
    <div class="xue">
      <div class="box">
        <div class="head">
          <img src="../assets/1.png">
          <div class="he_1">
            <p><a href="#one">Introduction</a></p>
            <p> <a href="#two">How to buy</a></p>
            <p> <a href="#three">Tokenomics</a></p>
            <p> <a href="#four"  >Roadmap</a></p>
            <p> <a href="https://chucky-topaz.vercel.app/#/about"  @click="to()"  target="_blank"  rel="noopener">Stake</a></p>
            <!-- <p> <a  target="_blank" href='' >stake</a></p> -->
            <p  @click="chad"  style="cursor:pointer;"> Connect </p>
          </div>
          <div class="he_2">
            Buy now
          </div>
        </div>
        <div class="cen" id="two">
          <div class="cen_1">
            <img class="cen_2" src="../assets/2.png">
            <p class="cen_3">Eternal Vigilance, Eternal Value:
              <br>
              "Chucky Coin - The Scam Killer's Choice."
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
    <div class="mgbaol" id="one">
      <div class="mggo">
        <div class="mggo_1">
          <img src="../assets/6.png">
        </div>
        <div class="mggo_2">
          <h1>INTRODUCTION</h1>
          <div class="mggo_3">
            <p>The inspiration and objective behind the creation of Chucky Coin are centered around its role as a token to
              kill scam coins. It is built on the Ethereum ERC-20 network.</p>

            <p>In the future, the scope will expand to encompass various networks. The system will officially announce
              another token sale. The primary purpose of developing this token is to address the dissatisfaction stemming
              from the collapse of various trading platforms, be it centralized or decentralized exchanges, and even
              investment funds that have led to the disappearance of investors' funds. This also includes the prevalence
              of various scam and "shitcoins" designed to deceive investors, coupled with the propagation of rumors
              through various social media platforms.</p>
            <p>
              Chucky Coin, therefore, emerges as a symbol to combat these challenges. It aims to be the most deserving
              asset in the cryptocurrency market, enduring for as long as cryptocurrencies exist in the world. Its purpose
              is to represent the equitable distribution of power to both the cryptocurrency community and investors,
              genuinely and perpetually.
            </p>
          </div>
          <img class="mgo_4" src="../assets/bj_1.png">
          <img class="mgo_5" src="../assets/bj_1.png">
        </div>
      </div>
    </div>
 
    <div class="sjbiao" id="three">
      <div class="sj_h1">
        <h1>TOKENOMICS</h1>
      </div>
      <div class="sj_biaot">
        <div class="sj_bi">
          <img src="../assets/7.png">
        </div>
        <div class="sj_bio">
          <p>TOKEN SUPPLY:</p>
          <h1>1,000,000,000,000</h1>
          <div class="sj_jubiao">
            <div class="sj_txt">
              <p>No Taxes, No fuss, just pure killin' it!. It’s as simple as that.</p>
              <p>80% of the tokens will be sent to the liquidity pool. The remaining 20% of the supply is being held in a
                multi-sig wallet only to be used as tokens for future centralized exchange listings, bridges, and
                liquidity pools.</p>
              <p>This wallet is easily trackable with TxID:
                <br>
                <span>0x80b82a60......48b50938 </span> ,
              </p>
              <p>We want to keep it real and make it awesome - killin' it in all aspects!</p>
            </div>
            <img class="mgo_6" src="../assets/bj_1.png">
            <img class="mgo_7" src="../assets/bj_1.png">
          </div>
        </div>
      </div>
    </div>
    <div class="dao" id="four">
      <div class="daot">
        <div class="dao_t">
          <h1>ROADMAP</h1>
          <img src="../assets/1.png">
        </div>
        <div class="dao_li">
          <div class="dao_lis">
            <h1>Phase 1</h1>
            <li>Launch website</li>
            <li>Market Swap</li>
            <li>Social media</li>
            <li>CoinGecko / Coinmarketcap Listings</li>
            <li>1,000+ wallet address</li>
          </div>
          <div class="dao_lis">
            <h1>Phase 2</h1>
            <li>Holder Chucky</li>
            <li>DEX Listings</li>
            <li>Airdrop</li>
            <li>10,000+ wallet address</li>
          </div>
          <div class="dao_lis">
            <h1>Phase 3</h1>
            <li>Bride of Chucky</li>
            <li>Bride of Chucky</li>
            <li>Curse of Chucky</li>
            <li>100,000+ wallet address</li>
          </div>
          <div class="dao_lis">
            <h1>Phase 4</h1>
            <li>Claim</li>
            <li>Rewards</li>
            <li>Event</li>
            <li>Giveaway</li>
            <li>1,000,000+ wallet address </li>
          </div>
          <div class="dao_lis">
            <h1>Phase 5</h1>
            <li>Games</li>
            <li>Predictions</li>
            <li>NFTs</li>
            <li>10,000,000+ wallet address</li>
          </div>
          <div class="dao_lis_one">
            <h1>Phase 6</h1>
            <img src="../assets/8.png">
            <p>Launch website</p>
          </div>
        </div>
      </div>
    </div>
    <div class="txt">
      <div class="txt_log">
        <p>Chucky Coin has no connection with the "Chucky" movie series in any of its installments. This decision reflects
          our respect for intellectual property and various copyrights. Chucky Coin was created as a representation of the
          ongoing demand that sustains the cryptocurrency market. It symbolizes the need to eliminate negative aspects
          from
          the crypto market, fostering a community where investments can thrive.</p>
        <p>
          Chucky Coin is a meme coin that might not hold immediate tangible value. If financial returns are anticipated,
          caution should be exercised when investing. The team's efforts and plans are focused on long-term creation and
          development, aiming to shape the future. The coin's utility is not fully comprehensive; it's crafted for
          entertainment and signifies the iconic doll character. The only coins that should cease to exist are shitcoins,
          scams, and FUD - Chucky Coin is created for these purposes.
        </p>
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
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      add: '',
      targetDate: moment().add(48, 'days'),
      remainingDays: '',
      remainingHours: '',
      remainingMinutes: '',
      remainingSeconds: ''
    };
  },
  methods: {

    chad(){
      console.log(1111)
      main();
    },
    go() {
      console.log(moment().format('LTS'))
    },
    to(){
      // this.$router.push('/about');
      // window.open(routeUrl.href, '_blank')
    },
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
  created() {
    this.add = moment().format('LTS')
    console.log(this.add)
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@font-face {
  font-family: 'one';
  src: url('../assets/three.woff2') format('truetype');
}

@font-face {
  font-family: 'two';
  src: url('../assets/two.woff2') format('truetype');
}

@font-face {
  font-family: 'three';
  src: url('../assets/three.woff2') format('truetype');
}

@font-face {
  font-family: 'four';
  src: url('../assets/four.woff2') format('truetype');
}

.hello {
  // max-width: 1800px;
  width: 100%;
  margin: 0 auto;
}

.xue {
  width: 100%;
  // height: 100vh;
  margin: 0 auto;
  padding-bottom: 10rem;
  background-image: url('../assets/bj_2.jpg');
  background-size: 100% 100%;
}

.box {
  width: 70%;
  margin: 0 auto;
  // border: 1px red solid;
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

  // background-color: pink;
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
  // max-width: 2000px;
  width: 100%;
  display: flex;
  justify-content: center
}

.cen_1 {
  max-width: 800px;
  width: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
  color: white;
}

.cen_2 {
  width: 430px;
  height: 208px;
  // margin: 1.5rem 0 1.5rem 0;
}

.cen_3 {
  font-size: 26px;
  text-align: center;
}

.cen_4 {
  width: 60%;
  height: 6rem;
  // border: 1px red solid;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  // background-color: white;
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
  max-width: 800px;
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

.mgbaol {
  width: 100%;
  // height: 55rem;
  background-image: url('../assets/bj_3.png');
  background-size: 100% 100%;
}

.mggo {
  max-width: 1680px;
  width: 80%;
  margin: 0 auto;
  display: flex;
}

.mggo_1 {
  width: 35%;
  display: flex;
  margin-top: 8rem;
}

.mggo_1>img {
  width: 421px;
  height: 640px;
}

.mggo_2 {
  max-width: 1400px;
  width: 65%;
  // border: 1px red solid;
  text-align: center;
}

.mggo_2>h1 {
  font-size: 3rem;
  margin: 3rem 0 3rem 0;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}

.mggo_3 {
  border: 2px red solid;
  color: rgba(254, 243, 199);
  font-size: 24px;
  text-align: center;
  border-radius: 10px;
  background-color: rgba(220, 38, 38, 0.4);
  position: relative;
}

.mggo_3>p {
  line-height: 2rem;
  margin: 2rem 0 1rem 0;
}

.mgo_4 {
  width: 417px;
  height: 151px;
  position: absolute;
  left: 44%;
}

.mgo_5 {
  width: 417px;
  height: 151px;
  position: absolute;
  // left: 88%;
}

.rdio {
  width: 100%;
  // height: 60rem;
  background-color: black;
  display: flex;
  align-items: center;
  margin-top: 25rem;
  margin-bottom: 20rem;
}

.rdios {
  max-width: 1400px;
  width: 80%;
  margin: 0 auto;
  // height: 40rem;
  // border: 1px red solid;
  color: white;
  display: flex;
  align-items: center;

}

.rdiosd {
  width: 35%;
  height: 60%;
  display: flex;
  flex-direction: column
}

.rdiosd>h1 {
  font-size: 60px;
  margin: 0em 0 2rem 0;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}

.rdiosd>p {
  color: #dfae0b;
  font-weight: 900;
}

.rdiosd>span {
  // font-size: 14px;
}

.rdiosx {
  width: 60%;
  border: 2px red solid;
  border-radius: 5px;
  position: relative;
}

.rdiosx>img:nth-child(1) {
  width: 100%;
}

.mgo_6 {
  position: absolute;
  width: 414px;
  height: 150px;
  top: 99%;
  left: 1%;
}

.mgo_7 {
  position: absolute;
  width: 414px;
  height: 150px;
  top: 99%;
  left: 50%;
}

.sjbiao {
  width: 100%;
  // height: 50rem;
  margin-bottom: 10rem;
  margin-top: 20rem;
  background-color: black;
}

.sj_h1>h1 {
  margin: 2rem 0 4rem 0;
  text-align: center;
  font-size: 60px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}

.sj_h1 {
  width: 100%;
  text-align: center;
}

.sj_biaot {
  max-width: 1680px;
  width: 80%;
  // height: 100%;
  // border: 1px red solid;
  margin: 0 auto;
  color: white;
  display: flex;
}

.sj_bi {
  width: 35%;
  height: 80%;
  margin-top: 8rem;
}

.sj_bi>img {
  width: 390px;
  height: 582px;
}

.sj_bio {
  width: 65%;
  text-align: center;
}

.sj_bio>p {
  font-size: 30px;
  margin-bottom: 2rem;
}

.sj_bio>h1 {
  font-size: 4.5rem;
  line-height: 1;
  margin-bottom: 3rem;
}

.sj_jubiao {
  width: 100%;
  border-radius: 10px;
  border: 2px red solid;
  background-color: rgba(220, 38, 38, 0.4);
  position: relative;
}

.sj_txt>p:nth-child(1) {
  padding: 2rem;
  color: rgb(254, 243, 199);
  font-size: 30px;
}

.sj_txt>p {
  padding: 1rem;
  color: white;
  font-size: 24px;
}

.sj_txt>p>span {
  text-decoration: underline;
}

.dao {
  width: 100%;
  // height: 100rem;
  background-image: url('../assets/bj_4.png');
  background-size: 100% 100%;
  margin-top: 30rem;
  margin-bottom: 20rem;
}

.daot {
  width: 80%;
  // height: 60rem;
  // border: 1px red solid;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.dao_t {
  width: 100%;
  text-align: center;
  font-size: 35px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}

.dao_t>img {
  width: 277px;
  height: 273px;
}

.dao_li {
  width: 100%;
  max-width: 1680px;
  display: flex;
  color: white;
  flex-wrap: wrap;
  justify-content: space-between;
}

.dao_lis {
  width: 27rem;
  height: 27rem;
  border-radius: 10px;
  background-color: black;
  border: 2px red solid;
  margin-bottom: 5rem;
  margin-top: 2rem;

}

.dao_lis>h1 {
  width: 100%;
  margin-top: 2rem;
  margin-bottom: 2rem;
  text-align: center;
  font-size: 25px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}

.dao_lis>li {
  margin-left: 2rem;
  line-height: 3rem;
  font-size: 24px;
}

.dao_lis_one {
  width: 27rem;
  height: 27rem;
  border-radius: 10px;
  background-color: black;
  border: 2px red solid;
  margin-bottom: 5rem;
  margin-top: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}

.dao_lis_one>h1 {
  width: 100%;
  margin-top: 2rem;
  margin-bottom: 2rem;
  text-align: center;
  font-size: 25px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
  background-image: linear-gradient(-225deg, #f23131, #dfae0b 29%, #dfae0b 67%, #f23131);
}

.dao_lis_one>li {
  margin-left: 2rem;
  line-height: 3rem;
  font-size: 24px;
}

.dao_lis_one>img {
  width: 162px;
  height: 223px;
}

.txt {
  max-width: 1800px;
  width: 100%;
  // height: 60rem;
  background-color: black;
  color: white;
  display: flex;
  text-align: center;
  margin-top:30rem;
  margin: 0 auto;
  // margin-bottom: 10rem;

}

.txt_log {
  width: 80%;
  margin: 0 auto;
  display: flex;
  margin-bottom: 10rem;
  justify-content: flex-end;
  flex-direction: column;
  align-items: center;


}

.txt_log>p {
  font-size: 22px;
  color: rgb(209, 213, 219);
  margin-top: 2rem;
  line-height: 30px;
}

.but {
  width: 100%;
  // height: 60rem;
  background-image: url('../assets/bj_5.png');
  background-size: 100% 100%;
}

.but_1 {
  max-width: 1800px;
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
  width: 22rem;
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
  // text-align: center;
  margin-left: 6rem;
  margin-top: 2rem;
}

.but_5 {
  max-width: 1800px;
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
.cen_6{

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
  .but_2{
    width: 20rem;
  }
  .mggo_2 > h1{
  font-size: 2.7rem;
  }
  .cen_6{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .cen_img{
    margin-left: 0rem;
    margin-top:  -1rem;
  }
}</style>
