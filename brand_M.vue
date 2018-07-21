<template>
    <section>
     
        <table id="table_product">
<tr id="tr_product1">
    <td id="td_product1">
         <product id="product1" :url_select="image_brand_N[counter_brand_N]"></product>
    </td>
     <td id="td_product2">
           <product id="product2" :url_select="image_brand_N[counter_brand_N+1]"></product>
    </td>
     <td id="td_product3">
           <product id="product3" :url_select="image_brand_N[counter_brand_N+3]"></product>
    </td>
     <td id="td_product4">
           <product id="product4" :url_select="image_brand_N[counter_brand_N+4]"></product>
    </td>
    </tr>
            <tr id="tr_product2">
    <td id="td_product21">
     <product id="product21" :url_select="image_brand_N[counter_brand_N+5]"></product>
    
    </td>
     <td id="td_product22">
          <product id="product22" :url_select="image_brand_N[counter_brand_N+6]"></product>
    </td>
     <td id="td_product23">
          <product id="product23" :url_select="image_brand_N[counter_brand_N+7]"></product>
    </td>
     <td id="td_product24">
          <product id="product24" :url_select="image_brand_N[counter_brand_N+8]"></product>
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
             image_brand_N:[require('~/assets/71.jpg'),require('~/assets/71.jpg'),require('~/assets/72.jpg'),require('~/assets/73.jpg'),require('~/assets/77.jpg'),require('~/assets/76.jpg'),require('~/assets/75.jpg'),require('~/assets/74.jpg'),require('~/assets/78.jpg')],
               counter_brand_N:0,

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