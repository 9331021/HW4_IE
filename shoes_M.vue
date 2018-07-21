<template>
    <section>
     
        <table id="table_product">
<tr id="tr_product1">
    <td id="td_product1">
         <product id="product1" :url_select="image_shoes_m[counter_shoes_m]"></product>
    </td>
     <td id="td_product2">
           <product id="product2" :url_select="image_shoes_m[counter_shoes_m+1]"></product>
    </td>
     <td id="td_product3">
           <product id="product3" :url_select="image_shoes_m[counter_shoes_m+3]"></product>
    </td>
     <td id="td_product4">
           <product id="product4" :url_select="image_shoes_m[counter_shoes_m+4]"></product>
    </td>
    </tr>
            <tr id="tr_product2">
    <td id="td_product21">
     <product id="product21" :url_select="image_shoes_m[counter_shoes_m+5]"></product>
    
    </td>
     <td id="td_product22">
          <product id="product22" :url_select="image_shoes_m[counter_shoes_m+6]"></product>
    </td>
     <td id="td_product23">
          <product id="product23" :url_select="image_shoes_m[counter_shoes_m+7]"></product>
    </td>
     <td id="td_product24">
          <product id="product24" :url_select="image_shoes_m[counter_shoes_m+8]"></product>
    </td>
    </tr>
            
 
            
            
          
            
            
            
    </table>
        
    </section>

</template>

<script>
      import product from '~/components/product'
    export default {
       
        data () {
            return {
             image_shoes_m:[require('~/assets/31.jpg'),require('~/assets/32.jpg'),require('~/assets/33.jpg'),require('~/assets/34.jpg'),require('~/assets/35.jpg'),require('~/assets/36.jpg'),require('~/assets/37.jpg'),require('~/assets/38.jpg'),require('~/assets/39.jpg')],
               counter_shoes_m:0,

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