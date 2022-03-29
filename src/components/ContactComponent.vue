<template>
  <div class="contact">
    <div class="d-flex">
      <div class="subscribe">
        <h2>Subscribe</h2>
        <form action="" method="post">
          <label for="email" class="d-block">Enter yout email...</label>
          <input
            type="email"
            name="email"
            id="email"
            placeholder="Your Email Address"
          />
          <button type="submit">Subscribe</button>
        </form>
      </div>
      <div class="sosmed">
        <h2>Contact</h2>
        <ul>
          <li>mbolang ygy@gmail.com</li>
          <li>Malang, Jawa Timur, Indonesia</li>
          <li>0812-1978-8445</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.contact {
  background: #94b49f;
  padding: 28px;
  margin: 60px 0;
}

.contact h2 {
  font-size: 36px;
  font-weight: bold;
}

.subscribe {
  margin-right: 70px;
}

.contact > .d-flex {
  justify-content: space-around;
}

.sosmed ul {
  list-style: none;
}

.sosmed ul li {
  font-size: 24px;
}

form input {
  background: white;
  height: 37px;
  padding: 5px 10px;
  border-radius: 5px;
  margin-right: 10px !important;
}

form button {
  background: #789395;
  color: white;
  padding: 5px 10px;
  border-radius: 5px;
}

.subscribe > * > *,
.sosmed > * > * {
  margin: 15px 0;
}
</style>
