<template>
  <div>
    <div class="d-flex">
      <div class="accordion flex-shrink-0" id="accordionExample" style='width: 250px'>
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
              Base
            </button>
          </h2>
          <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" style="">
            <div class="accordion-body">
              <ul class="nav flex-column">
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/typography">Typography</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/color">Color</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/spacing">Spacing</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/border">Border</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/shadow">Shadow</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
              Layout
            </button>
          </h2>
          <div id="collapseTwo" class="accordion-collapse collapse show" aria-labelledby="headingTwo" style="">
            <div class="accordion-body">
              <ul class="nav flex-column">
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/grid">Grid</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/card">Card</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/collapse">Collapse</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/tab">Tab</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/dialog">Dialog</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/drawer">Drawer</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
              Component
            </button>
          </h2>
          <div id="collapseThree" class="accordion-collapse collapse show" aria-labelledby="headingThree">
            <div class="accordion-body">
              <ul class="nav flex-column">
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/button">Button & Link</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/card">Input</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="/_ui/collapse">Dropdown</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="headingFour">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
              Others
            </button>
          </h2>
          <div id="collapseFour" class="accordion-collapse collapse show" aria-labelledby="headingFour">
            <div class="accordion-body">

            </div>
          </div>
        </div>
      </div>
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
