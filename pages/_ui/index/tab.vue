<template>
  <div>
    <!-- -->
    <h2>Tab</h2>
    TabName: {{ tabText }}
    <div>
      <ul class="nav nav-tabs" id="myTab" role="tablist">
        <li class="nav-item" role="presentation">
          <button class="nav-link active" id="home-tab" @click="selectTab('first')" data-bs-toggle="tab" data-bs-target="#home-tab-pane" type="button" aria-controls="home-tab-pane" aria-selected="true">Home</button>
        </li>
        <li class="nav-item" role="presentation">
          <button class="nav-link" id="profile-tab" @click="selectTab('second')" data-bs-toggle="tab" data-bs-target="#profile-tab-pane" type="button" aria-controls="profile-tab-pane" aria-selected="false">Profile</button>
        </li>
        <li class="nav-item" role="presentation">
          <button class="nav-link" id="contact-tab" @click="selectTab('third')" data-bs-toggle="tab" data-bs-target="#contact-tab-pane" type="button" aria-controls="contact-tab-pane" aria-selected="false">Contact</button>
        </li>
        <li class="nav-item" role="presentation">
          <button class="nav-link" id="disabled-tab" data-bs-toggle="tab" data-bs-target="#disabled-tab-pane" type="button" aria-controls="disabled-tab-pane" aria-selected="false" disabled>Disabled</button>
        </li>
      </ul>
      <div class="tab-content" id="myTabContent">
        <div class="tab-pane fade show active" id="home-tab-pane" aria-labelledby="home-tab" tabindex="0">
          가나다라마바사아자차카타파하
        </div>
        <div class="tab-pane fade" id="profile-tab-pane" aria-labelledby="profile-tab" tabindex="0">
          ABCDEFGHIJKLMNOPQRSTUVWXYZ
        </div>
        <div class="tab-pane fade" id="contact-tab-pane" aria-labelledby="contact-tab" tabindex="0">
          abcdefghijklmnopqrstuvwxyz
        </div>
        <div class="tab-pane fade" id="disabled-tab-pane" aria-labelledby="disabled-tab" tabindex="0">...</div>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>Card Style</h2>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>Border Card Style</h2>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>Position</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      tabText: 'first',
    }
  },
  methods: {
    selectTab(tabName) {
      this.tabText = tabName
    }
  }
}
</script>

<style lang="scss" scoped></style>
