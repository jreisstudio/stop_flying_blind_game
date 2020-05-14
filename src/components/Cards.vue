<template>
  <div id="main" class="container">
    <div class="row">
        <div class="col-md">
            <div class="card">
                <div class="card-body">
                  {{ msg }}
                </div>

            </div>
        </div>

        <div class="col-md">
            <div class="card">
                <div class="card-body">
                  Opa...
                </div>

            </div>
        </div>


    </div>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}

</script>

<style scoped>

</style>