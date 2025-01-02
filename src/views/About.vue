<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>I'm <strong>Gustavo Barros</strong>, a game designer passionate about bringing game ideas to life.<br/></div>
      
      <div style="margin-top: 20px;">I love discussing, designing, and developing games and apps of all kinds.<br/> I've experienced working on game programming, design, and 3D art throughout my experience and studies, giving me a solid foundation in different aspects of game development.</div>

      <div style="margin-top: 20px;">I'm <strong>currently looking for new opportunities</strong> to work on exciting projects, where I can bring my skills, creativity, and passion to the team.</div>

      <div style="margin-top: 20px;">You can reach me at <a href="mailto:gustavoncbarros@gmail.com">gustavoncbarros@gmail.com</a> or <router-link to="/contact">through here</router-link>.</div>

    </div>

    <div class="photo">
      <img src="img/avatar.jpg" alt="Avatar of John" class="avatar"/> 
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

.avatar {
  width: 224px; /* Set the desired width */
  height: 224px; /* Set the desired height */
  object-fit: cover; /* Ensures the image scales properly without distortion */
  border-radius: 50%; /* Makes the shape circular */
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>