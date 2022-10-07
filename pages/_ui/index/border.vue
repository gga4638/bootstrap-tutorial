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
      <div class="row gap-4">
        <div class="col-2 p-2 border border-primary">.border-primary</div>
        <div class="col-2 p-2 border border-primary border-opacity-75">.border-primary</div>
        <div class="col-2 p-2 border border-primary border-opacity-50">.border-primary</div>
        <div class="col-2 p-2 border border-primary border-opacity-25">.border-primary</div>
        <div class="col-2 p-2 border border-primary border-opacity-10">.border-primary</div>
        <div class="col-2 p-2 border border-secondary">.border-secondary</div>
        <div class="col-2 p-2 border border-success">.border-success</div>
        <div class="col-2 p-2 border border-info">.border-info</div>
        <div class="col-2 p-2 border border-warning">.border-warning</div>
        <div class="col-2 p-2 border border-danger">.border-danger</div>
        <div class="col-2 p-2 border border-light">.border-light</div>
        <div class="col-2 p-2 border border-dark">.border-dark</div>
        <div class="col-2 p-2 bg-black">
          <div class="px-3 border border-white text-white">.border-white</div>
        </div>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>Border Radius</h2>
    <el-row :gutter="10">
      <el-col :span="5">
        <div class="bg-light p-3 radius-sm">.radius-sm</div>
      </el-col>
      <el-col :span="5">
        <div class="bg-light p-3 radius">.radius</div>
      </el-col>
      <el-col :span="5">
        <div class="bg-light p-3 radius-lg">.radius-lg</div>
      </el-col>
      <el-col :span="5">
        <div class="bg-light p-3 radius-pill">.radius-pill</div>
      </el-col>
      <el-col :span="4">
        <div class="bg-light p-3 radius-circle">.radius-circle</div>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
