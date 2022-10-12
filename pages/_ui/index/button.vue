<template>
  <div>
    <!-- -->
    <h2>
      Size
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.btn.btn-*</code></small>
    </h2>
    <div>
      <button type="button" class="btn btn-primary btn-lg">large</button>
      <button type="button" class="btn btn-primary btn-lg">.btn-lg <i class="bi bi-search"/></button>
      <button type="button" class="btn btn-primary btn-lg"><i class="bi bi-search"/></button>
      <br />
      <br />
      <button type="button" class="btn btn-primary">default</button>
      <button type="button" class="btn btn-primary">default <i class="bi bi-search"/></button>
      <button type="button" class="btn btn-primary"><i class="bi bi-search"/></button>
      <br />
      <br />
      <button type="button" class="btn btn-primary btn-sm">samll</button>
      <button type="button" class="btn btn-primary btn-sm">.btn-sm <i class="bi bi-search"/></button>
      <button type="button" class="btn btn-primary btn-sm"><i class="bi bi-search"/></button>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>
      Color
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.btn.btn-*</code></small>
    </h2>
    <div>
      <button type="button" class="btn btn-primary">Primary</button>
      <button type="button" class="btn btn-secondary">Secondary</button>
      <button type="button" class="btn btn-success">Success</button>
      <button type="button" class="btn btn-danger">Danger</button>
      <button type="button" class="btn btn-warning">Warning</button>
      <button type="button" class="btn btn-info">Info</button>
      <button type="button" class="btn btn-light">Light</button>
      <button type="button" class="btn btn-dark">Dark</button>
      <button type="button" class="btn btn-link">Link</button>
      <div class="mt-2">
        <h3>Disable</h3>
        <button type="button" class="btn btn-primary" disabled>Primary</button>
        <button type="button" class="btn btn-secondary" disabled>Secondary</button>
        <button type="button" class="btn btn-success" disabled>Success</button>
        <button type="button" class="btn btn-danger" disabled>Danger</button>
        <button type="button" class="btn btn-warning" disabled>Warning</button>
        <button type="button" class="btn btn-info" disabled>Info</button>
        <button type="button" class="btn btn-light" disabled>Light</button>
        <button type="button" class="btn btn-dark" disabled>Dark</button>
        <button type="button" class="btn btn-link" disabled>Link</button>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>
      Outline buttons
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.btn.btn-outline-*</code></small>
    </h2>
    <div>
      <button type="button" class="btn btn-outline-primary">Primary</button>
      <button type="button" class="btn btn-outline-secondary">Secondary</button>
      <button type="button" class="btn btn-outline-success">Success</button>
      <button type="button" class="btn btn-outline-danger">Danger</button>
      <button type="button" class="btn btn-outline-warning">Warning</button>
      <button type="button" class="btn btn-outline-info">Info</button>
      <button type="button" class="btn btn-outline-light">Light</button>
      <button type="button" class="btn btn-outline-dark">Dark</button>
      <div class="mt-2">
        <h3>Disable</h3>
        <button type="button" class="btn btn-outline-primary" disabled>Primary</button>
        <button type="button" class="btn btn-outline-secondary" disabled>Secondary</button>
        <button type="button" class="btn btn-outline-success" disabled>Success</button>
        <button type="button" class="btn btn-outline-danger" disabled>Danger</button>
        <button type="button" class="btn btn-outline-warning" disabled>Warning</button>
        <button type="button" class="btn btn-outline-info" disabled>Info</button>
        <button type="button" class="btn btn-outline-light" disabled>Light</button>
        <button type="button" class="btn btn-outline-dark" disabled>Dark</button>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>
      Round & Circle
      <small class="fs-4 ml-3 ls-0 text-placeholder"><code>.btn.rounded-*</code></small>
    </h2>
    <button type="button" class="btn btn-primary rounded-pill">.rounded-pill</button>
    <button type="button" class="btn btn-primary rounded-circle">-circle</button>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>
      Icon Button
      <small class="fs-4 ml-3 ls-0 text-placeholder">&lt;i class="bi bi-*"/&gt;</small>
    </h2>
    <button type="button" class="btn btn-sm btn-primary rounded-circle">
      <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
        <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
      </svg>
    </button>
    <button type="button" class="btn btn-small btn-primary rounded-circle"><i class="bi bi-check"></i></button>
    <button type="button" class="btn btn-primary rounded-circle"><i class="bi bi-check-lg"></i></button>
    <button type="button" class="btn btn-primary rounded-circle"><i class="bi bi-check2"></i></button>
    <button type="button" class="btn btn-info rounded-circle"><i class="bi bi-search"></i> </button>
    <button type="button" class="btn btn-warning rounded-circle"><i class="bi bi-search"></i></button>
    <button type="button" class="btn btn-success rounded-circle"><i class="bi bi-pencil"></i></button>
    <button type="button" class="btn btn-outline-warning rounded-circle"><i class="bi bi-search"></i></button>
    <button type="button" class="btn btn-danger rounded-circle"><i class="bi bi-trash"></i></button>
    <button type="button" class="btn btn-lg btn-primary rounded-circle">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="25" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
        <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
      </svg>
    </button>
    <!-- -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      toggleText: null,
    }
  },
  methods: {
    toggleButton(event) {
      this.toggleText = '324'
    }
  }
}
</script>

<style lang="scss" scoped></style>
