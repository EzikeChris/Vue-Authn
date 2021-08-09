<template>
  <div id="App">
  <nav className="navbar navbar-expand navbar-light fixed-top">
       <div className="container">

         <a href="w" className="navbar-brand">Home</a>

         <div className="collapse navbar-collapse">
           <ul className="navbar-nav ml-auto">
             <li className="nav-item">
               <a href="w" className="nav-link">
                 Login
               </a>
             </li>
             <li className="nav-item">
               <a href="w" className="nav-link">
                Sign-Up
               </a>
             </li>

           </ul>

         </div>










       </div>
     </nav>
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


<style scoped>

</style>
