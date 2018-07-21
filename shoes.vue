<template>
    <section>
     
        <table id="table_product">
<tr id="tr_product1">
    <td id="td_product1">
         <product id="product1" :url_select="image_shoes_s[counter_shoes_s]"></product>
    </td>
     <td id="td_product2">
           <product id="product2" :url_select="image_shoes_s[counter_shoes_s+1]"></product>
    </td>
     <td id="td_product3">
           <product id="product3" :url_select="image_shoes_s[counter_shoes_s+3]"></product>
    </td>
     <td id="td_product4">
           <product id="product4" :url_select="image_shoes_s[counter_shoes_s+4]"></product>
    </td>
    </tr>
            <tr id="tr_product2">
    <td id="td_product21">
     <product id="product21" :url_select="image_shoes_s[counter_shoes_s+5]"></product>
    
    </td>
     <td id="td_product22">
          <product id="product22" :url_select="image_shoes_s[counter_shoes_s+6]"></product>
    </td>
     <td id="td_product23">
          <product id="product23" :url_select="image_shoes_s[counter_shoes_s+7]"></product>
    </td>
     <td id="td_product24">
          <product id="product24" :url_select="image_shoes_s[counter_shoes_s+8]"></product>
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
             image_shoes_s:[require('~/assets/43.jpg'),require('~/assets/44.jpg'),require('~/assets/45.jpg'),require('~/assets/46.jpg'),require('~/assets/47.jpg'),require('~/assets/48.jpg'),require('~/assets/49.jpg'),require('~/assets/50.jpg'),require('~/assets/51.jpg')],
               counter_shoes_s:0,

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