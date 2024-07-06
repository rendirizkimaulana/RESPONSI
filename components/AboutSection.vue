<template>
  <section class="about">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <img src="assets/fotoku.jpg" alt="Rendi Rizki Maulana" class="img-fluid rounded-box mb-" width="400">
        </div>
        <div class="col-md-6">
          <div class="about-content">
            <h2 class="mb-4">About Me</h2>
            <p class="lead">I am Rendi Rizki Maulana, a passionate Full Stack Developer based in Bay Area, San Francisco, CA. I love creating web applications and solving real-world problems with technology.</p>
            <p>Feel free to reach out to me:</p>
            <ul class="list-unstyled">
              <li><i class="fas fa-envelope"></i> <a href="mailto:rendirizkimaulana@students.amikom.ac.id">rendirizkimaulana@students.amikom.ac.id</a></li>
              <li><i class="fas fa-phone"></i> <a href="tel:+6285703159283">085703159283</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.about {
  padding: 100px 0;
  background-color: #f8f9fa;
}

.about-content {
  color: #333;
}

.about-content h2 {
  font-size: 2.5rem;
  color: #007bff;
}

.about-content p {
  font-size: 1.1rem;
  line-height: 1.8;
}

.about-content ul {
  padding-left: 0;
  list-style: none;
}

.about-content ul li {
  margin-bottom: 10px;
}

.about-content ul li i {
  margin-right: 10px;
}

.img-fluid {
  max-width: 100%;
  height: auto;
  border: 8px solid #fff;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
}
</style>
