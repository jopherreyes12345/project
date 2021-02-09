<template>
  
   
  

 <div class="flex justify-center items-center h-screen">   
    <div class="flex flex-col w-1/3">
            <div class="flex flex-wrap bg-gray-400 p-8 justify-start">
              <label for="department" class="w-full text-left"> Department</label>
              <input type="text" id="department" class="w-full border-gray-400">
            </div>                            
            <div class="flex p-2 bg-gray-300 justify-end">
                <button class="bg-blue-600 text-gray-50 rounded-md p-2"> Create  Department </button>
             </div>                
    </div>      
 </div>  

   

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
