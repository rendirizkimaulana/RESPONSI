<template>
  <section class="contact">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-8">
          <div class="contact-content text-center">
            <h2 class="mb-4">Contact Me</h2>
            <p class="lead">Feel free to get in touch with me. I am available via email or phone.</p>
            <ul class="list-unstyled">
              <li><i class="fas fa-envelope"></i> <a href="mailto:rendirizkimaulana@students.amikom.ac.id">rendirizkimaulana@students.amikom.ac.id</a></li>
              <li><i class="fas fa-phone"></i> <a href="tel:+6285703159283">085703159283</a></li>
            </ul>
            <div class="social-icons mt-4">
              <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
              <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
              <a href="#" class="social-icon"><i class="fab fa-linkedin"></i></a>
              <a href="#" class="social-icon"><i class="fab fa-github"></i></a>
              <a href="#" class="social-icon"><i class="fab fa-facebook"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 100px 0;
  background-color: #f8f9fa;
}

.contact-content {
  color: #333;
}

.contact-content h2 {
  font-size: 2.5rem;
  color: #007bff;
}

.contact-content p {
  font-size: 1.1rem;
  line-height: 1.8;
}

.contact-content ul {
  padding-left: 0;
  list-style: none;
  margin-top: 20px;
}

.contact-content ul li {
  margin-bottom: 10px;
}

.contact-content ul li i {
  margin-right: 10px;
}

.social-icons {
  margin-top: 30px;
}

.social-icon {
  color: #007bff;
  font-size: 24px;
  margin-right: 15px;
  transition: transform 0.3s ease-in-out;
}

.social-icon:hover {
  transform: translateY(-3px);
}
</style>
