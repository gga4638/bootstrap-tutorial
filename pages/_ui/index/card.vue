<template>
  <div>
    <!-- -->
    <h2>Card</h2>
    <div class="row gap-5">
      <div class="col-2">
        <div class="card">
          <div class="card-body">
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
            <a href="#" class="card-link">Card link</a>
            <a href="#" class="card-link">Another link</a>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card">
          <img src="/images/kosign.png" class="card-img-top" alt="image">
          <div class="card-body">
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
     </div>
      <div class="col-2">
        <div class="card">
          <h5 class="card-header">Header</h5>
          <div class="card-body">
            <h5 class="card-title">title</h5>
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
          <div class="card-footer text-muted">Footer</div>
        </div>
      </div>
    </div>
    <!-- -->
    <hr class="my-5" />
    <!-- -->
    <h2>Shadow</h2>
    <div class="row gap-5">
      <div class="col-2">
        <div class="card shadow">
          <div class="card-body">
            <h5 class="card-title">always (default)</h5>
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div
          class="card"
          @mouseover="mouseoverShadow($event, true)"
          @mouseleave="mouseoverShadow($event, false)"
        >
          <div class="card-body">
            <h5 class="card-title">hover</h5>
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">never</h5>
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card shadow2">
          <div class="card-body">
            <h5 class="card-title">hover animate</h5>
            <p class="card-text">가나다라마바사아자차카타파하 ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    }
  },
  methods: {
    mouseoverShadow(event, isMouseOver) {
      if(isMouseOver) event.currentTarget.classList.add('shadow')
      else event.currentTarget.classList.remove('shadow')
    },
  }
}
</script>

<style lang="scss" scoped>
.card.shadow2 {
  -webkit-box-shadow: 0 1px 1px rgba(72,78,85,.6);
  box-shadow: 0 1px 1px rgba(72,78,85,.6);
  -webkit-transition: all .2s ease-out;
  -moz-transition: all .2s ease-out;
  -ms-transition: all .2s ease-out;
  -o-transition: all .2s ease-out;
  transition: all .2s ease-out;
}

.card.shadow2:hover {
  -webkit-box-shadow: 0 20px 40px rgba(72,78,85,.6);
  box-shadow: 0 20px 40px rgba(72,78,85,.6);
  -webkit-transform: translateY(-15px);
  -moz-transform: translateY(-15px);
  -ms-transform: translateY(-15px);
  -o-transform: translateY(-15px);
  transform: translateY(-15px);
}
</style>
