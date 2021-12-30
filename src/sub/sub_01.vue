<template>
  <Header/>
	<section class="dashboard">
    <div class="location">
      <h4>発注書登録</h4>
    </div>
    <div class="contBox">    
      <div style="background:#fff;">
          <table>
            <colgroup>
              <col style="width:10%">
              <col style="*">
            </colgroup>
            <tr>
              <th class="title">일자</th>
              <td class="date"><datepicker v-model="picked"  class="datetimepickericon"/></td>
            </tr>
            <tr>
              <th class="title">여행일자</th>
              <td class="date"><datepicker v-model="picked"  class="datetimepickericon"/></td>
            </tr>
          </table>
      </div>
      <div style="margin-top:20px;">
        <Calendar backgroundText  class-name="select-mode"  :remarks="remarks"/>
      </div>
    </div> 
  </section> 
 
  <Footer/>
</template>

<script> 
  import { reactive,ref } from 'vue'
  import Header from '../components/Header'
  import Footer from '../components/Footer'
  import Calendar from 'mpvue-calendar'
  import Datepicker from 'vue3-datepicker'

  export default{
    name:'sub',
    components:{
      Header,
      Footer, 
      Calendar,
      Datepicker
         
    },  
    setup() {
      const remarks = reactive({'2021-12-31': 'Date'})
      const picked = ref(new Date())
      return {
        remarks,
        picked
      }
  } 
  }
</script>
<!--
<script setup>
// import { ref,reactive } from 'vue'
// import Datepicker from 'vue3-datepicker'
// const picked = ref(new Date())
// const remarks = reactive({'2021-12-30': 'Date'})
</script>//-->




<style>
 table th{font-size:14px;font-weight:600;}
 table th.title{position:relative;padding-right:15px;text-align:right}
 table th.title:after{content:'';content: '';display:block;position:absolute;right:0px;top:50%;transform:translateY(-50%);width:1px;height:20px;background: rgb(197, 197, 197);}
 table td.date{padding:10px 15px;}
 input[type=text]:read-only {position:relative;background-color: #f5f5f5;}
 input.datetimepickericon{position:relative;background: url('../assets/images/common/date_ico.png') right 10px  center no-repeat;font-family: 'notokr'; font-size: 13px;cursor:pointer;}
 input.datetimepickericon:after{content:'';position:absolute;right:20px;top:0px;width:1px;height:100%;background-color:#000;}
 .date .v3dp__datepicker {
  --popout-bg-color: var(--vdp-bg-color, #fff);
  --box-shadow: var(
    --vdp-box-shadow,
    0 4px 10px 0 rgba(128, 144, 160, 0.1),
    0 0 1px 0 rgba(128, 144, 160, 0.81)
  );
  --text-color: var(--vdp-text-color, #000000);
  --border-radius: var(--vdp-border-radius, 3px);
  --heading-size: var(--vdp-heading-size, 2.5em); /* 40px for 16px font */
  --heading-weight: var(--vdp-heading-weight, bold);
  --heading-hover-color: var(--vdp-heading-hover-color, #eeeeee);
  --arrow-color: var(--vdp-arrow-color, currentColor);

  --elem-color: var(--vdp-elem-color, currentColor);
  --elem-disabled-color: var(--vdp-disabled-color, #d5d9e0);
  --elem-hover-color: var(--vdp-hover-color, #fff);
  --elem-hover-bg-color: var(--vdp-hover-bg-color, #0baf74);
  --elem-selected-color: var(--vdp-selected-color, #fff);
  --elem-selected-bg-color: var(--vdp-selected-bg-color, #0baf74);

  --elem-font-size: var(--vdp-elem-font-size, 0.95em);
  --elem-border-radius: var(--vdp-elem-border-radius, 3px);

  --divider-color: var(--vdp-divider-color, var(--elem-disabled-color));

  position: relative;
}

.date .v3dp__clearable {
  display: inline;
  position: relative;
  left: -15px;
  cursor: pointer;
}
.date .v3dp__subheading span:last-child{color:rgb(20, 111, 231);}
.date .v3dp__subheading span:first-child{color:rgba(197, 4, 110, 0.89);}
.vc-calendar-timetable .vc-calendar-timetable-wrap .vc-calendar-body .vc-calendar-row .vc-calendar-day .vc-calendar-day-container{text-align:center;}
.vc-calendar-timetable .vc-calendar-timetable-wrap .vc-calendar-body .vc-calendar-row .vc-calendar-day .vc-calendar-date{margin-top:5px;}
.vc-calendar-remark-text{background: #0b6cbc;display: inline-block;text-align:center;white-space: nowrap; padding: 0 3px;border-radius: 3px;transform: scale(.8);color: #fff;}

</style>






