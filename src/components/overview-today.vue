<template lang="en">
   <div class="social-media">
      <!-- element -->
      <div class="container">
         <div class="row">
            <div class="row mt-4">
               <div class="col-12 col-md-8">
                  <h2>
                     Overview - Today
                  </h2>
               </div>
               <hr />
            </div>
         </div>



          <div class="row d-flex flex-md-nowrap justify-content-center justify-content-md-between">
            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>

            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>

            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>

            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>
            
         </div>


        <div class="row d-flex flex-md-nowrap justify-content-center justify-content-md-between">
            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>

            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>

            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>

            <div class="col-12 col-md-3 col-xl-3 social-item m-2">
               <div class="social-name d-flex justify-content-between" >
                  <p class="align-bottom grey">
                     Page Views
                  </p>
                  <img    
                     class="social-img align-middle" 
                     :src="imgsource"
                     alt="icone facebook"
                     >
               </div>
               <div class="d-flex justify-content-between mt-4">
                  <h4 class='number col-6 text-start'>87</h4>
                  <p class="progression col-6 text-end green">3%</p>
               </div>
            </div>

         </div>
      </div>
   </div>
</template>
<script>
export default {
  name: "overviewtoday",
  data() {
    return {
      imgsource: require("../assets/img/icon-facebook.svg"),
    };
  },
};
</script>
<style scoped>
.container {
  max-width: 1044px !important;
}

.myheader {
  background-color: chartreuse;
  width: 100%;
}
/* global colors */
.grey {
  color: hsl(228, 12%, 44%);
}

.green {
  color: hsl(163, 72%, 41%);
}
/* global */
.social-media {
  color: hsl(0, 0%, 100%);
}

/* card */
/* global card */
.social-item {
  padding-top: 20px;
  padding-bottom: auto;
  background-color: hsl(228, 28%, 20%);
  width: 250px;
  height: 125px;
  text-align: center;
  
  border-radius: 5px;
}

/* social image */
.social-name {
  display: flex;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: center;
  margin-top: -10px;
}

.social-img {
  width: 20px;
  height: 20px;
}

.follow-name {
  margin-top: 12px;
  margin-left: 5px;
  justify-self: center;
}

/* big number */
.num-of-followers {
  margin-top: -10px;
  font-size: 60px;
  font-style: bold;
  margin-bottom: -5px;
}
</style>
