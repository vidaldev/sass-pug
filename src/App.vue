<template lang="pug">
  #container
    #app
      img(src="https://static.platzi.com/media/user_upload/Page%201-d8d869f4-7130-4ae9-9907-2fa809bd136a.jpg")
      h1 {{ msg }}
      form(action="#" method="post")
        div(class="form-section")
          label(class="fs-label") Nombre
          input(class="fs-label" name="nombre" id="nombre" value="Jose Vidal")
        div(class="form-section")
          label(class="fs-label") Usuario
          input(class="fs-label" name="usuario" id="usuario" value="VidalDev")
        div(class="form-section")
          label(class="fs-label") Cargo
          input(class="fs-label" name="cargo" id="cargo" value="FullStack JS")
        button(type='submit' class='btn-action') ENVIAR
    #github_rep
      #gr_box
        #git_text 
          a(href="https://github.com/vidaldev/sass-pug/") Ver el repositorio de este proyecto
        #git_logo
          a(href="https://github.com/vidaldev/sass-pug/") 
            img(src="./assets/logo-github.png")
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Registro estación Platzi'
    }
  }
}
</script>

<style lang="scss" scoped>
  @import url('./scss/main.scss');
</style>
