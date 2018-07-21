<template>
  
<section>

   <table id="tb_address" v-if="gen_check===0">
   
    <tr id="tr_address">   
       <td id="add1">
          
           <tr> <td><input type="button" id="but_pen"><i id="td_address1" class="fa fa-edit" ></i> </td></tr>
           <tr><td><input type="button" id="but_close"><i id="td_address11" class="fa fa-close" ></i> </td></tr>
    </td>
      
        
        <td id="add2">
            <tr><td id="td_address12"><input type="text" id="address_phone" placeholder="شماره تلفن همراه: شماره"/></td></tr>
            <tr>  <td id="td_address22"><input type="text" id="address_kod" placeholder="کدپستی :مقدار کد پستی"/></td></tr>
    </td>
        
        
        <td id="add3">
            <tr class="addd"><td id="td_address13"><input type="text" id="address_phone_sabet" placeholder="شماره تلفن ثابت :شماره "/></td>
            <td id="td_address14"><input type="text" id="address_delivery" placeholder="تحویل گیرنده : نام"/></td></tr>
            
            <tr class="addd"><td colspan="2" id="td_address23"><input type="text" id="address_text" placeholder="آدرس :متن آدرس"/></td></tr>
    </td>
        
        
        <td id="add5">
            <div  id='ci_address'></div>
    </td>
       
       
    </tr>  
    </table>
    
    <table id="tb_address" v-else-if="gen_check===1">
   
    <tr id="tr_address">   
       <td id="add11">
          
           <tr> <td><input type="button" id="but_pen"><i id="td_address1" class="fa fa-edit" ></i> </td></tr>
           <tr><td><input type="button" id="but_close"><i id="td_address11" class="fa fa-close" ></i> </td></tr>
    </td>
      
        
        <td id="add22">
            <tr><td id="td_address12"><input type="text" id="address_phone" placeholder="شماره تلفن همراه: شماره"/></td></tr>
            <tr>  <td id="td_address22"><input type="text" id="address_kod" placeholder="کدپستی :مقدار کد پستی"/></td></tr>
    </td>
        
        
        <td id="add33">
            <tr class="addd"><td id="td_address13"><input type="text" id="address_phone_sabet" placeholder="شماره تلفن ثابت :شماره "/></td>
            <td id="td_address14"><input type="text" id="address_delivery" placeholder="تحویل گیرنده : نام"/></td></tr>
            
            <tr class="addd"><td colspan="2.5" id="td_address23"><input type="text" id="address_text" placeholder="آدرس :متن آدرس"/></td></tr>
    </td>
        
        
        <td id="add55">
            <div  id='ci_address'></div>
    </td>
       
       
    </tr>  
    </table>
    
    
    
    
    
    </section>

</template>

<script>
    export default {
            props:['gen_check'],
        data () {
            return {
            }
        },
        components: {
        }
    }
</script>

<style>
  
    
    #tb_address{
      width: 100%;
        height: 100px;
        border: 1px solid;
        border-color: deepskyblue;
       
        
    }
     
   
      
  
    #but_circle{
       position: absolute;
      margin-top: -7.2%;
         width: 2.2%;
        height: 93px;
        margin-left: 87.2%;
    }
    
      #add5{
        border: 1px solid;
         width: 3.5%;
          background-color: gainsboro;
    }
    
    
        #add55{
        border: 1px solid;
             background-color: gainsboro;
         width: 3.5%;
          border-color: aqua;
    }
    
    #ci_address{
          position: absolute;
     width: 5%;
        height: 15px;
        direction: rtl;
      margin-left: -1%;
        margin-top: -.6%;
        color: yellow;
     font-size: 25px;
    }
    
    
    
    
    
    #add2{
        border: 1px solid;
         
    }
    
    
     #add3{
        border: 1px solid;
         width: 57%;
        padding-right: 1.5%;
        direction: rtl;
    }
  #add22{
        border: 1px solid;
         border-color: aqua;
  
    }
    
    
     #add33{
        border: 1px solid;
         width: 57%;
         border-color: aqua;
          padding-right: 1.5%;
        direction: rtl;
    }
    
    
     
    
   
    
    
    
    
      #but_pen{
       position: absolute;
      
         width: 2%;
        height: 40px;
        margin-right: 19.2%;
          margin-top: -3%;
  
    }
    
    
    
    
    #td_address1{
          position: absolute;
     width: 1.1%;
        height: 15px;
        direction: rtl;
        margin-right: -5%;
        margin-top: -1.8%;
        color: white;
        font-size: 16px;
        color: white;;
        z-index: 1;
        margin-left: .5%;
    }

    #add1{
        border: 1px solid;
        width: 3%;;
    }
    
    #add11{
        border: 1px solid;
        width: 3%;;
        border-color: aqua;
    }
    #but_close{
       position: absolute;
      
         width: 2%;
        height: 40px;
        margin-right: 18.5%;
          margin-top: 0%;
  padding-left: 1%;
    }
    
    
    
    
    #td_address11{
          position: absolute;
     width: 1.1%;
        height: 15px;
        direction: rtl;
        margin-right: 1.7%;
        margin-left: .5%;
        margin-top: .8%;
        color: white;
      
        
    
        font-size: 16px;
    }
      
    #td_address12{
    width: 24%;
          direction: rtl;
        margin-left: 0%;
        margin-top: 0%;
        border: 1px solid;
         border-color: gainsboro;
       
        
    }
      
    #td_address13{
    width: 45%;
        direction: rtl;
        margin-left: 0%;
        margin-top: 0%;
        border: 1px solid;
        margin-top: -5%;
         border-color: gainsboro;
         
    }
      
    #td_address14{
   width: 28%;
        margin-left: 0%;
        margin-top: 0%;
        border: 1px solid;
       border-color: gainsboro;
          direction: rtl;
        
    }
    
    
    
      
    #td_address21{
      width: 10%;
        margin-left: 0%;
        margin-top: 0%;
        border: 1px solid;
        border-color: gainsboro;
          direction: rtl;
        
        
    }
      
    #td_address22{
      width: 10%;
          direction: rtl;
        margin-left: 0%;
        margin-top: 0%;
        border: 1px solid;
        border-color: gainsboro;
      
        
    }
    
      
    #td_address23{
      width: 10%;
        margin-left: 0%;
        margin-top: 0%;
        border: 1px solid;
      border-color: gainsboro;
          direction: rtl;
    }
      
   
    
    #address_phone{
        width: 100%;
        height: 38px;
         border: 1px solid;
      border-color: white;
        font-size: 16px;
    }
     #address_phone_sabet{
        width: 100%;
        height: 38px;
          font-size: 16px;
          border: 1px solid;
      border-color: white;
         margin-top: 0%;
    }
      #address_delivery{
        width: 100%;
        height: 38px;
          font-size: 16px;
           border: 1px solid;
      border-color: white;
       
         
    }
      #address_text{
        width: 100%;
        height: 38px;
          font-size: 16px;
           border: 1px solid;
      border-color: white;
     
         
    }
      #address_kod{
        width: 100%;
        height: 38px;
           border: 1px solid;
      border-color: white;
          font-size: 16px;
         
    }
    
    
   
    
    
    
    

    
</style>