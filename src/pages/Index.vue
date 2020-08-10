<template>
<!--
  <Layout>
    -->
    <div id="background" class="container m-auto">
      <h1 class="ml-6 mt-16 mb-16 text-4xl text-red-600">
        Website Moved To www.visitlondon.life
      </h1>
    
      
        <g-image
          class = "w-full h-full object-cover"
          src   = "https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_150,w_560/v1515831480/tower_vow6im.jpg"
          alt   = "tower of london"
      />
      
      <!--<date class="ml-8"/>-->
    
        <br />
     
     
    </div>
    

    <!--
  </Layout>
  -->
</template>

<script>


export default {
  metaInfo: {
    title: "londoneast",
    meta : [
      {
        name   : "description",
        content: 
          "website moved to www.visitlondon.life"
      }
    ],
    script: [
      { scr: "https: //cdn.jsdelivr.net/npm/gsap@3.0.4/dist/gsap.min.js" },
      { src: "https://cdn.jsdelivr.net/npm/jquery@3.4.1/dist/jquery.min.js" },
      { src: "https://cdn.jsdelivr.net/npm/animejs@3.1.0/lib/anime.min.js" },
      { src: "https://kit.fontawesome.com/e3c70d4fc5.js" }
    ]
  },
  components: {
  
  }
};
</script>

<style>
.Hero {
  padding-top   : 10rem;
  padding-bottom: 10rem;
  background    : darksalmon;
  color         : #337;
}
.Port {
  padding: 5rem;
}
.work {
  padding: 2rem 1rem;
}
.work-card {
  box-shadow   : 0px 0px 20px rgba(0, 0, 0.1);
  padding      : 1rem;
  border-radius: 0.2rem;
  color        : #00ff7f;
  margin       : 1rem;
}

.home-links a {
  margin-right: 1rem;
}
</style>
