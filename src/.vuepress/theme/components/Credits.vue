<template>
  <footer class="credits">
    <div class="wrapper">
      <article>
        <p><b>Protonull Corporation Pvt. Ltd.</b> &copy;Copyright <span class="year">{{ year }}</span>. All rights reserved.</p>
      </article>
    </div>
  </footer>
</template>

<script>
export default {
  computed: {
    year () {
      return new Date().getFullYear()
    }
  }
}
</script>
