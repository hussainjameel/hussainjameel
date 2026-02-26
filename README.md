<style>
  .profile-container {
    display: flex;
    align-items: flex-start;
    gap: 40px;
    flex-wrap: wrap;
  }
  
  .text-content {
    flex: 1;
    min-width: 300px;
    max-width: 600px;
  }
  
  .image-content {
    flex: 0 0 350px;
  }
  
  .bio-text {
    line-height: 1.6;
    margin: 0 0 20px 0;
    font-size: 16px;
  }
  
  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column-reverse;
    }
    
    .image-content {
      flex: 0 0 auto;
      margin-bottom: 20px;
    }
  }
</style>

<div class="profile-container">
  <div class="text-content">
    <p style="margin: 0; font-size: 16px;">
      Hi 👋, I'm
    </p>

    <h1 style="margin: 0 0 20px 0; font-size: 48px; font-weight: 700;">
      Hussain Jameel
    </h1>

    <p class="bio-text">
      Software Engineer / I love building and rebuilding programs using color, fonts, 
      and illustrations. I'm a great admirer of attention to detail and beautifully 
      crafted designs that not only look exceptional but also are easy to use. 
      I specialize in creating user interfaces and user experiences utilizing the 
      latest web technologies.
    </p>

    <br>

    <h3 style="margin-bottom: 10px;">Let's Connect</h3>
    <p style="margin: 0; line-height: 2;">
      💼 LinkedIn<br>
      ✍️ dev.to<br>
      🛠️ Portfolio<br>
      📬 jameel@gmail.com
    </p>
  </div>
  
  <div class="image-content">
    <img 
      src="https://raw.githubusercontent.com/hussainjameel/hussainjameel/eb646e5125a9357b1d147fd2bc2a04bd37116d1d/Dev_Illustration.png" 
      width="350" 
      alt="illustration" 
      style="max-width: 100%;"
    />
  </div>
</div>
