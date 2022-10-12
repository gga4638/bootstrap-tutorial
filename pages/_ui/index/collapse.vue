<template>
  <div>
    <!-- -->
    <h2>Collapse</h2>
    <div class="mb-5">
      <div class="mb-3">
        <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
          vertical collapse
        </button>
        <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapseWidthExample" aria-expanded="false" aria-controls="collapseWidthExample">
          horizontal collapse
        </button>
        <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target=".multi-collapse" aria-expanded="false" aria-controls="multiCollapseExample1 multiCollapseExample2">Toggle both elements</button>
      </div>
      <div class="row">
        <div class="col">
          <div class="collapse multi-collapse" id="collapseExample">
            <div class="card card-body">
              Some placeholder content for the collapse component. This panel is hidden by default but revealed when the user activates the relevant trigger.
            </div>
          </div>
        </div>
        <div class="col">
          <div style="min-height: 120px;">
            <div class="collapse collapse-horizontal multi-collapse" id="collapseWidthExample">
              <div class="card card-body" style="width: 300px;">
                This is some placeholder content for a horizontal collapse. It's hidden by default and shown when triggered.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <h2>Accordion</h2>
    <div class="mb-5"></div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      activeNames: [],
      activeName: null,
    }
  },
  methods: {
  },
}
</script>

<style lang="scss" scoped></style>
