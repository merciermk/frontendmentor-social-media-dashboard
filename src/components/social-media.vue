<template lang="en">
<div class="social-media">

 
   <!-- element -->

   <div class="container">
       <div class="row">
            <div class="row mt-4">
         <div class="col-12 col-md-8">
            <h2>
               Social Media Dashboard
            </h2>
            <h6 class="total-followers grey">
               Total Followers: 23,004
            </h6>
         </div>
         <hr />
         <div class="col-12 col-md-4">
            <p class="dark-mode-text grey">
               Dark mode
            </p>
         </div>
      </div>
       </div>
      <div class="row d-flex flex-md-nowrap justify-content-center justify-content-md-between">
          
         <!-- element 1 -->
         <div class="col-12 col-md-6 flex-lg-nowrap col-xl-3 social-item m-2">
            <div class="social-name">
               <img    
                  class="social-img" 
                  :src="imgsource"
                  alt="icone facebook"
                  >
               <p class="follow-name grey">
                  @nathanf
               </p>
            </div>
            <p class="num-of-followers">
               1987
            </p>
            <p class="followers-text grey">
               FOLLOWERS
            </p>
            <p class="today green">
               12 Today
            </p>
         </div>
         <!-- element2 -->
         <div class="col-12 col-md-6 flex-lg-nowrap col-xl-3 social-item m-2">
            <div class="social-name">
               <img    
                  class="social-img" 
                  src="../assets/img/icon-twitter.svg"
                  alt="icone Twitter"
                  >
               <p class="follow-name grey">
                  @nathanf
               </p>
            </div>
            <p class="num-of-followers">
               1044
            </p>
            <p class="followers-text grey">
               FOLLOWERS
            </p>
            <p class="today green">
               99 Today
            </p>
         </div>
         <!-- element3 -->
         <div class="col-12 col-md-6 flex-lg-nowrap col-xl-3 social-item m-2">
            <div class="social-name">
               <img    
                  class="social-img" 
                  src="../assets/img/icon-instagram.svg"
                  alt="icone Twitter"
                  >
               <p class="follow-name grey">
                  @realnathanf
               </p>
            </div>
            <p class="num-of-followers">
               11K
            </p>
            <p class="followers-text grey">
               FOLLOWERS
            </p>
            <p class="today green">
               1099 Today
            </p>
         </div>
         <!-- element4 -->
         <div class="col-12 col-md-6 flex-lg-nowrap col-xl-3 social-item m-2">
            <div class="social-name">
               <img    
                  class="social-img" 
                  src="../assets/img/icon-youtube.svg"
                  alt="icone Twitter"
                  >
               <p class="follow-name grey">
                  Nathan F.
               </p>
            </div>
            <p class="num-of-followers">
               8239
            </p>
            <p class="followers-text grey">
               SUBSCRIERS
            </p>
            <p class="today green">
               144 Today
            </p>
         </div>
      </div>
   </div>
</div>
   
   
</template>
<script>
export default {
  name: "social-media",
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
  height: 225px;
  text-align: center;
  border-top: 4px solid blueviolet;
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
