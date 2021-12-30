<template>
  <Header/>
	<section class="dashboard">
      <div class="cont-title">
        <h4>Dashboard</h4>
        <ul class="dash-list">
          <li class="cBrown">
            <img src="../assets/images/dash_01.png" alt="">
            <a href="javascript:void(0)">
              <span>作成中</span>
              <b>45</b>
            </a>
          </li>
          <li class="cBlue2">
            <img src="../assets/images/dash_02.png" alt="">
            <a href="javascript:void(0)">
              <span>要請</span>
              <b>28</b>
            </a>
          </li>
          <li class="cGreen">
            <img src="../assets/images/dash_03.png" alt="">
            <a href="javascript:void(0)">
              <span>完了</span>
              <b>36</b>
            </a>
          </li>
          <li class="cViolet">
            <img src="../assets/images/dash_04.png" alt="">
            <a href="javascript:void(0)">
              <span>拒絶</span>
              <b>64</b>
            </a>
          </li>
        </ul>
      </div>
      <!--dash-title ed-->
      <div class="cont_wrap">
        <div class="dash-top">
          <div class="cont-box">
            <dl>
              <dt class="tit">
                <h5>最近登録された見積書</h5>
                <a class="more-btn" href="javascript:void(0)"><img src="../assets/images/more-btn.png" alt=""></a>
              </dt>
              <dd class="order-list">
                <table class="mr30">
                  <colgroup>
                    <col style="width:40%;"><col>
                  </colgroup>
                  <tbody>
                    <tr>
                      <th>見積番号</th>
                      <td>Q410HDT3</td>
                    </tr>
                    <tr>
                      <th>件名</th>
                      <td>(参考)スレート/6.16kW</td>
                    </tr>
                    <tr>
                      <th>見積有効期限</th>
                      <td><span class="fPopp">2022.01.10</span></td>
                    </tr>
                    <tr>
                      <th>物件番号</th>
                      <td>RX53211015001</td>
                    </tr>
                    <tr>
                      <th>太陽電池容量</th>
                      <td><span class="fPopp">6.16</span> kW</td>
                    </tr>
                  </tbody>
                </table>
                <table class="ml30">
                  <colgroup>
                    <col style="width:40%;"><col>
                  </colgroup>
                  <tbody>
                    <tr>
                      <th>注文番号</th>
                      <td>Q410HDT1</td>
                    </tr>
                    <tr>
                      <th>件名</th>
                      <td>㈱セーフ様</td>
                    </tr>
                    <tr>
                      <th>見積有効期限</th>
                      <td><span class="fPopp">2022.01.10</span></td>
                    </tr>
                    <tr>
                      <th>物件番号</th>
                      <td>RX53211015001</td>
                    </tr>
                    <tr>
                      <th>太陽電池容量</th>
                      <td><span class="fPopp">102.3</span> kW</td>
                    </tr>
                  </tbody>
                </table>
              </dd> 
            </dl>
          </div>

          <div class="cont-box">
            <dl>
              <dt class="tit">
                <h5>直近登録の発注書</h5>
                <a class="more-btn" href="javascript:void(0)"><img src="../assets/images/more-btn.png" alt=""></a>
              </dt>
              <dd class="order-list">
                <table class="mr30">
                  <colgroup>
                    <col style="width:40%;"><col>
                  </colgroup>
                  <tbody>
                    <tr>
                      <th>注文番号</th>
                      <td>M410HDT3</td>
                    </tr>
                    <tr>
                      <th>件名</th>
                      <td>生井甚一棟様邸 太陽光工事</td>
                    </tr>
                    <tr>
                      <th>納品日付</th>
                      <td><span class="fPopp">2022.01.10</span></td>
                    </tr>
                    <tr>
                      <th>物件番号</th>
                      <td>RX53211015001</td>
                    </tr>
                    <tr>
                      <th>太陽電池容量</th>
                      <td><span class="fPopp">6.16</span> kW</td>
                    </tr>
                  </tbody>
                </table>
                <table class="ml30">
                  <colgroup>
                    <col style="width:40%;"><col>
                  </colgroup>
                  <tbody>
                    <tr>
                      <th>注文番号</th>
                      <td>Q410HDT1</td>
                    </tr>
                    <tr>
                      <th>件名</th>
                      <td>㈱セーフ様</td>
                    </tr>
                    <tr>
                      <th>納品日付</th>
                      <td><span class="fPopp">2022.01.10</span></td>
                    </tr>
                    <tr>
                      <th>物件番号</th>
                      <td>RX53211015001</td>
                    </tr>
                    <tr>
                      <th>太陽電池容量</th>
                      <td><span class="fPopp">102.3</span> kW</td>
                    </tr>
                  </tbody>
                </table>
              </dd>
            </dl>
          </div>
        </div>
        <!--dash-top ed-->

        <div class="dash-bottom">
          <div class="left">
            <div class="cont-box">
              <dl class="noti-list">
                <dt class="tit">
                  <h5>お知らせ</h5>
                  <a class="more-btn" href="javascript:void(0)"><img src="../assets/images/more-btn.png" alt=""></a>
                </dt>
                <dd class="mt30">
                  <a href="javascript:void(0)">災害時 /停電時の製品取り扱いについて</a>
                  <span class="fPopp">2022.01.21</span>
                </dd>
                <dd>
                  <a href="javascript:void(0)">災害時 /停電時の製品取り扱いについて</a>
                  <span class="fPopp">2022.01.18</span>
                </dd>
                <dd>
                  <a href="javascript:void(0)">ハンファQCELLSE-Order Systemオープン</a>
                  <span class="fPopp">2022.01.15</span>
                </dd>
              </dl>
            </div>

            <div class="cont-box" style="margin-right:0;">
              <dl class="contact">
                <dt class="tit">
                  <h5>お問い合わせ</h5>
                </dt>
                <dd class="mt30">
                  <img src="../assets/images/dash-icon.png" alt="">
                  <p>
                    東京都港区芝<br/> 4丁目10番1号 ハンファビル7階
                  </p>
                  <p class="mt10">
                    <span>Tel. <em>03-5441-5679</em></span><br/>
                    <span>Fax. <em>03-5441-5915</em></span>
                  </p>
                </dd>
              </dl>
            </div>
          </div>
          <!--left ed-->

          <div class="right ml10">
            <div class="year-count">
              <div class="cont-box">
                <dl>
                  <dt class="tit">
                    <h5>発注金額</h5>
                    <span><em>2021</em>年</span>
                  </dt>
                  <dd>
                    <b>￥ 197,208,000</b>
                    <span>(消費税込)</span>
                  </dd>
                </dl>
              </div>
              <div class="cont-box">
                <dl>
                  <dt class="tit">
                    <h5>入金予定金額</h5>
                    <span><em>2021</em>年</span>
                  </dt>
                  <dd>
                    <b>￥ 34,727,440</b>
                    <span>(消費税込)</span>
                  </dd>
                </dl> 
              </div>
            </div>
  
            <div class="order-enroll">
              <div class="cont-box">
                <img src="../assets/images/dash-icon01.png" alt="">
                <p>発注書登録</p>
                <a class="go-btn" href="javascript:void(0)">GO</a>
              </div>
              <div class="cont-box dash">
                <img src="../assets/images/dash-icon02.png" alt="">
                <p>発注書エクセル<br/>大量登録</p>
                <a class="go-btn brown" href="javascript:void(0)">GO</a>
              </div>
            </div>
          </div>
          <!--left ed-->
        </div>  
        <!--dash-bottom ed-->
      </div>
    </section>
    <Footer/>
</template>

<script>
 import Header from '../components/Header'
 import Footer from '../components/Footer'

 export default{
   name:'Main',
   components:{
     Header,
     Footer
   }

 }
</script>
