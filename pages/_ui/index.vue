<template>
  <div>
    <div class="d-flex">
      <ul class="nav flex-column border" style='width: 250px' >
        <li class="nav-item">
          <a class="nav-link" href="/_ui/typography">Typography</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="/_ui/color">Color</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/_ui/spacing">Spacing</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/_ui/border">Border</a>
        </li>
      </ul>
      <div class="flex-grow-1 p-5">
        <NuxtChild />
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>
