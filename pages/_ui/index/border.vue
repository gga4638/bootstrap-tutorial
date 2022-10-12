<template>
  <div>
    <!-- -->
    <h2>Border Sides</h2>
    <div>
      <div class="row gap-4">
        <div class="col p-3 border">.border</div>
        <div class="col p-3 border-top">.border-top</div>
        <div class="col p-3 border-end">.border-end</div>
        <div class="col p-3 border-bottom">.border-bottom</div>
        <div class="col p-3 border-start">.border-start</div>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>Border Size
      <small class="fs-4 ml-3 ls-0 text-placeholder">1 ~ 5px</small>
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.border</code> required</small>
    </h2>
    <div>
      <div class="row gap-4">
        <div class="col p-3 border border-1">.border-1</div>
        <div class="col p-3 border border-2">.border-2</div>
        <div class="col p-3 border border-3">.border-3</div>
        <div class="col p-3 border border-4">.border-4</div>
        <div class="col p-3 border border-5">.border-5</div>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>
      Border Color
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.border</code> required</small>
    </h2>
    <div>
      <div class="row gap-4 mb-3">
        <div class="col-2 p-2 border border-dark">.border-dark</div>
        <div class="col-2 p-2 border border-white">.border-white</div>
      </div>
      <div class="row gap-4 mb-3">
        <div class="col p-2 border border-primary">.border-primary</div>
        <div class="col p-2 border border-primary border-opacity-75">.border-opacity-75</div>
        <div class="col p-2 border border-primary border-opacity-50">.border-opacity-50</div>
        <div class="col p-2 border border-primary border-opacity-25">.border-opacity-25</div>
        <div class="col p-2 border border-primary border-opacity-10">.border-opacity-10</div>
      </div>
      <div class="row gap-4 mb-3">
        <div class="col p-2 border border-success">.border-success</div>
        <div class="col p-2 border border-success border-opacity-75">.border-opacity-75</div>
        <div class="col p-2 border border-success border-opacity-50">.border-opacity-50</div>
        <div class="col p-2 border border-success border-opacity-25">.border-opacity-25</div>
        <div class="col p-2 border border-success border-opacity-10">.border-opacity-10</div>
      </div>
      <div class="row gap-4 mb-3">
        <div class="col p-2 border border-warning">.border-warning</div>
        <div class="col p-2 border border-warning border-opacity-75">.border-opacity-75</div>
        <div class="col p-2 border border-warning border-opacity-50">.border-opacity-50</div>
        <div class="col p-2 border border-warning border-opacity-25">.border-opacity-25</div>
        <div class="col p-2 border border-warning border-opacity-10">.border-opacity-10</div>
      </div>
      <div class="row gap-4 mb-3">
        <div class="col p-2 border border-danger">.border-danger</div>
        <div class="col p-2 border border-danger border-opacity-75">.border-opacity-75</div>
        <div class="col p-2 border border-danger border-opacity-50">.border-opacity-50</div>
        <div class="col p-2 border border-danger border-opacity-25">.border-opacity-25</div>
        <div class="col p-2 border border-danger border-opacity-10">.border-opacity-10</div>
      </div>
      <div class="row gap-4 mb-3">
        <div class="col p-2 border border-info">.border-info</div>
        <div class="col p-2 border border-info border-opacity-75">.border-opacity-75</div>
        <div class="col p-2 border border-info border-opacity-50">.border-opacity-50</div>
        <div class="col p-2 border border-info border-opacity-25">.border-opacity-25</div>
        <div class="col p-2 border border-info border-opacity-10">.border-opacity-10</div>
      </div>
      <div class="row gap-4 mb-3">
        <div class="col p-2 border border-secondary">.border-secondary</div>
        <div class="col p-2 border border-secondary border-opacity-75">.border-opacity-75</div>
        <div class="col p-2 border border-secondary border-opacity-50">.border-opacity-50</div>
        <div class="col p-2 border border-secondary border-opacity-25">.border-opacity-25</div>
        <div class="col p-2 border border-secondary border-opacity-10">.border-opacity-10</div>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>Radius</h2>
    <div class="row gap-4">
      <div class="col bg-dark text-white p-3 rounded">.rounded</div>
      <div class="col bg-dark text-white p-3 rounded-top">.rounded-top</div>
      <div class="col bg-dark text-white p-3 rounded-end">.rounded-end</div>
      <div class="col bg-dark text-white p-3 rounded-bottom">.rounded-bottom</div>
      <div class="col bg-dark text-white p-3 rounded-start">.rounded-start</div>
      <div class="col bg-dark text-white p-3 rounded-circle">.rounded-circle</div>
      <div class="col bg-dark text-white p-3 rounded-pill">.rounded-pill</div>
    </div>
    <br/>
    <br/>
    <h2>Radius Sizes</h2>
    <div class="row gap-4">
      <div class="col bg-dark text-white p-3 rounded-0">.rounded-0</div>
      <div class="col bg-dark text-white p-3 rounded-1">.rounded-1</div>
      <div class="col bg-dark text-white p-3 rounded-2">.rounded-2</div>
      <div class="col bg-dark text-white p-3 rounded-3">.rounded-3</div>
      <div class="col bg-dark text-white p-3 rounded-4">.rounded-4</div>
      <div class="col bg-dark text-white p-3 rounded-5">.rounded-5</div>
    </div>
    <hr class="my-5" />
    <h2>ETC</h2>
    <div>
      <div class="mb-4">
        <label for="exampleFormControlInput1" class="form-label">Email address</label>
        <input type="email" class="form-control border-success" id="exampleFormControlInput1" placeholder="name@example.com">
      </div>
      <div class="h4 pb-2 mb-4 text-danger border-bottom border-danger">
        Dangerous heading
      </div>
      <div class="p-3 bg-info bg-opacity-10 border border-info border-start-0 rounded-end">
        Changing border color and width
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
