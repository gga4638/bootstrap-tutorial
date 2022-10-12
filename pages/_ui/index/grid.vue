<template>
  <div>
    <!-- row 대신 grid로 작성함 -->
    <h2>Grid & Responsive</h2>
    <div class="row">
      <div class="p-3 mb-3 col-12 bg-primary-light-8">.g-col-12</div>
      <div class="p-3 mb-3 col-12 col-lg-6 bg-primary-light-8">.g-col-6</div>
      <div class="p-3 mb-3 col-12 col-lg-6 bg-light">.g-col-6</div>
      <div class="p-3 mb-3 col-12 col-lg-4 bg-primary-light-8">.g-col-4</div>
      <div class="p-3 mb-3 col-12 col-lg-4 bg-light">.g-col-4</div>
      <div class="p-3 mb-3 col-12 col-lg-4 bg-primary-light-8">.g-col-4</div>
      <div class="p-3 mb-3 col-6 col-lg-3 bg-primary-light-8">.g-col-3</div>
      <div class="p-3 mb-3 col-6 col-lg-3 bg-light">.g-col-3</div>
      <div class="p-3 mb-3 col-6 col-lg-3 bg-primary-light-8">.g-col-3</div>
      <div class="p-3 mb-3 col-6 col-lg-3 bg-light">.g-col-3</div>
      <div class="p-3 mb-3 col-4 col-lg-2 bg-primary-light-8">.g-col-2</div>
      <div class="p-3 mb-3 col-4 col-lg-2 bg-light">.g-col-2</div>
      <div class="p-3 mb-3 col-4 col-lg-2 bg-primary-light-8">.g-col-2</div>
      <div class="p-3 mb-3 col-4 col-lg-2 bg-light">.g-col-2</div>
      <div class="p-3 mb-3 col-4 col-lg-2 bg-primary-light-8">.g-col-2</div>
      <div class="p-3 mb-3 col-4 col-lg-2 bg-light">.g-col-2</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-primary-light-8">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-light">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-primary-light-8">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-light">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-primary-light-8">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-light">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-primary-light-8">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-light">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-primary-light-8">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-light">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-primary-light-8">.g-col-1</div>
      <div class="p-3 mb-3 col-2 col-lg-1 bg-light">.g-col-1</div>
    </div>
    <!--    -->
    <hr class="my-5" />
    <!--    -->
    <h3>Gutters</h3>
    <div>
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.g-0</code></small>
      <div class="row mb-3 g-0">
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
      </div>
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.g-1</code></small>
      <div class="row mb-3 g-1">
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
      </div>
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.g-2</code></small>
      <div class="row mb-3 g-2">
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
      </div>
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.g-3</code></small>
      <div class="row mb-3 g-3">
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
      </div>
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.g-4</code></small>
      <div class="row mb-3 g-4">
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
      </div>
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.g-5</code></small>
      <div class="row mb-3 g-5">
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
        <div class="col-6">
          <div class="p-3 bg-primary-light-8">.g-col-6</div>
        </div>
      </div>
    </div>
    <!--    -->
    <hr class="my-5" />
    <!-- gutter, offset 동시 사용 안됨 -->
    <!-- https://getbootstrap.com/docs/5.2/layout/gutters/  -->
    <h3>Offset</h3>
    <div>
      <div class="row mb-3">
        <div class="p-3 col-4 bg-primary-light-8">.col-4</div>
        <div class="p-3 col-4 offset-4 bg-primary-light-8">.col-4 .offset-4</div>
      </div>
      <div class="row mb-3">
        <div class="p-3 col-4 offset-4 bg-primary-light-8">.col-4 .offset-4</div>
        <div class="p-3 col-4 bg-primary-light-8">.col-4</div>
      </div>
      <div class="row mb-3">
        <div class="p-3 col-6 offset-3 bg-primary-light-8">.col-6 .offset-3</div>
      </div>
      <h4>Responsive</h4>
      <div>
        <div class="row mb-3">
          <div class="p-3 border border-primary bg-primary-light-8 col-sm-5 col-md-6">.col-sm-5 .col-md-6</div>
          <div class="p-3 border border-primary bg-primary-light-8 col-sm-5 offset-sm-2 col-md-6 offset-md-0">.col-sm-5 .offset-sm-2 .col-md-6 .offset-md-0</div>
        </div>
        <div class="row mb-3">
          <div class="p-3 border border-primary bg-primary-light-8 col-sm-6 col-md-5 col-lg-6">.col-sm-6 .col-md-5 .col-lg-6</div>
          <div class="p-3 border border-primary bg-primary-light-8 col-sm-6 col-md-5 offset-md-2 col-lg-6 offset-lg-0">.col-sm-6 .col-md-5 .offset-md-2 .col-lg-6 .offset-lg-0</div>
        </div>
      </div>
      <div class="row mb-3">
        <div class="p-3 border border-primary bg-primary-light-8 col-md-4">.col-md-4</div>
        <div class="p-3 border border-primary bg-primary-light-8 col-md-4 ms-auto">.col-md-4 .ms-auto</div>
      </div>
      <div class="row mb-3">
        <div class="p-3 border border-primary bg-primary-light-8 col-md-3 ms-md-auto">.col-md-3 .ms-md-auto</div>
        <div class="p-3 border border-primary bg-primary-light-8 col-md-3 ms-md-auto">.col-md-3 .ms-md-auto</div>
      </div>
      <div class="row mb-3">
        <div class="p-3 border border-primary bg-primary-light-8 col-auto me-auto">.col-auto .me-auto</div>
        <div class="p-3 border border-primary bg-primary-light-8 col-auto">.col-auto</div>
      </div>
    </div>
    <!--    -->
    <hr class="my-5" />
    <!--    -->
    <h3>Alignment Horizontal</h3>
    <div>
      <div class="row justify-content-start mb-3">
        <div class="p-3 col-4 bg-primary-light-8">4 (start)</div>
        <div class="p-3 col-4 bg-light">4 (start)</div>
      </div>
      <div class="row justify-content-center mb-3">
        <div class="p-3 col-4 bg-primary-light-8">4 (center)</div>
        <div class="p-3 col-4 bg-light">4 (center)</div>
      </div>
      <div class="row justify-content-end mb-3">
        <div class="p-3 col-4 bg-primary-light-8">4 (end)</div>
        <div class="p-3 col-4 bg-light">4 (end)</div>
      </div>
      <div class="row justify-content-around mb-3">
        <div class="p-3 col-4 bg-primary-light-8">4 (around)</div>
        <div class="p-3 col-4 bg-light">4 (around)</div>
      </div>
      <div class="row justify-content-between mb-3">
        <div class="p-3 col-4 bg-primary-light-8">4 (between)</div>
        <div class="p-3 col-4 bg-light">4 (between)</div>
      </div>
      <div class="row justify-content-evenly mb-3">
        <div class="p-3 col-4 bg-primary-light-8">4 (evenly)</div>
        <div class="p-3 col-4 bg-light">4 (evenly)</div>
      </div>
    </div>
    <!--    -->
    <hr class="my-5" />
    <!--    -->
    <h3>Alignment Vertical</h3>
    <div>
      <div class="row align-items-start mb-3 bg-light" style="height: 150px;">
        <div class="col p-3 bg-primary-light-8">.align-items-start</div>
        <div class="col p-3 bg-primary-light-8">.align-items-start</div>
        <div class="col p-3 bg-primary-light-8">.align-items-start</div>
      </div>
      <div class="row align-items-center mb-3 bg-light" style="height: 150px;">
        <div class="col p-3 bg-primary-light-8">.align-items-center</div>
        <div class="col p-3 bg-primary-light-8">.align-items-center</div>
        <div class="col p-3 bg-primary-light-8">.align-items-center</div>
      </div>
      <div class="row align-items-end mb-3 bg-light" style="height: 150px;">
        <div class="col p-3 bg-primary-light-8">.align-items-end</div>
        <div class="col p-3 bg-primary-light-8">.align-items-end</div>
        <div class="col p-3 bg-primary-light-8">.align-items-end</div>
      </div>
      <div class="row mb-3 bg-light" style="height: 200px;">
        <div class="col p-3 align-self-start bg-primary-light-8">.align-self-start</div>
        <div class="col p-3 align-self-center bg-primary-light-8">.align-self-center</div>
        <div class="col p-3 align-self-end bg-primary-light-8">.align-self-end</div>
      </div>
    </div>
    <!--    -->
    <hr class="my-5" />
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
