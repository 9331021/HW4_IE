<template>
    <section>
     
        <table id="table_product" v-if="color===15" >
<tr id="tr_product1">
    <td id="td_product1">
         <product id="product1" :url_select="image_brand_c[counter_brand_c]"></product>
    </td>
     <td id="td_product2">
           <product id="product2" :url_select="image_brand_c[counter_brand_c+1]"></product>
    </td>
     <td id="td_product3">
           <product id="product3" :url_select="image_brand_c[counter_brand_c+3]"></product>
    </td>
     <td id="td_product4">
           <product id="product4" :url_select="image_brand_c[counter_brand_c+4]"></product>
    </td>
    </tr>
            <tr id="tr_product2">
    <td id="td_product21">
     <product id="product21" :url_select="image_brand_c[counter_brand_c+5]"></product>
    
    </td>
     <td id="td_product22">
          <product id="product22" :url_select="image_brand_c[counter_brand_c+6]"></product>
    </td>
     <td id="td_product23">
          <product id="product23" :url_select="image_brand_c[counter_brand_c+7]"></product>
    </td>
     <td id="td_product24">
          <product id="product24" :url_select="image_brand_c[counter_brand_c+8]"></product>
    </td>
    </tr>
            
            
    </table>
        
        
               <table id="table_product" v-if="color===35" >
<tr id="tr_product1">
    <td id="td_product1">
         <product id="product1" :url_select="image_brand_bl[counter_brand_bl]"></product>
    </td>
     <td id="td_product2">
           <product id="product2" :url_select="image_brand_bl[counter_brand_bl+1]"></product>
    </td>
     <td id="td_product3">
           <product id="product3" :url_select="image_brand_bl[counter_brand_bl+3]"></product>
    </td>
     <td id="td_product4">
           <product id="product4" :url_select="image_brand_bl[counter_brand_bl+4]"></product>
    </td>
    </tr>
            <tr id="tr_product2">
    <td id="td_product21">
     <product id="product21" :url_select="image_brand_bl[counter_brand_bl+5]"></product>
    
    </td>
     <td id="td_product22">
          <product id="product22" :url_select="image_brand_bl[counter_brand_bl+6]"></product>
    </td>
     <td id="td_product23">
          <product id="product23" :url_select="image_brand_bl[counter_brand_bl+7]"></product>
    </td>
     <td id="td_product24">
          <product id="product24" :url_select="image_brand_bl[counter_brand_bl+8]"></product>
    </td>
    </tr>
            
            
    </table>
        
        
    </section>

</template>

<script>
      import product from '~/components/product'
    export default {
       props:['color'],
        data () {
            return {
             image_brand_c:[require('~/assets/91.jpg'),require('~/assets/92.jpg'),require('~/assets/93.jpg'),require('~/assets/94.jpg'),require('~/assets/95.jpg'),require('~/assets/96.jpg'),require('~/assets/80.jpg')],
               counter_brand_c:0,
                           image_brand_bl:[require('~/assets/100.jpg'),require('~/assets/101.jpg'),require('~/assets/102.jpg'),require('~/assets/103.jpg'),require('~/assets/104.jpg'),require('~/assets/105.jpg'),require('~/assets/106.jpg'),require('~/assets/107.jpg'),require('~/assets/108.jpg')],
               counter_brand_bl:0,

            }
        },
        components: {
            product,
        }
    }
</script>

<style>
   
    
 
    
    #table_product{
       
        width: 100%;
        height: 750px;
        
    }
    
    #td_product1{
     
         width: 20%;
        height: 280px;
        
        
    }
     #td_product2{
     
         width: 20%;
        height: 270px;   
        
    }
    
     #td_product3{
     
         width: 20%;
        height: 270px;
        
        
    }
     #td_product4{
    
         width: 20%;
        height: 270px;
        
        
    }
    
    
    
    
     #td_product21{
     
         width: 20%;
        height: 280px;
        
        
    }
     #td_product22{
     
         width: 20%;
        height: 270px;   
        
    }
    
     #td_product23{
     
         width: 20%;
        height: 270px;
        
        
    }
     #td_product24{
    
         width: 20%;
        height: 270px;
        
        
    }
       
    
         
    
    
    
    
</style>