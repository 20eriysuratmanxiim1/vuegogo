<template>
  <div class="ProfileView">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="media">
            <img src="../assets/profile.jpg" class="mr-3 user-pic" />
            <div class="media-body">
              <h5 class="mt-0">Eriy Suratman</h5>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Voluptas, suscipit.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

import 'bootstrap/dist/css/bootstrap.css'

<script>
export default {
  name: "ProfileView",
  components: {},
};
</script>
<style scoped>
.user-pic {
  height: 120px;
  width: 120px;
  border-radius: 200%;
}
</style>
