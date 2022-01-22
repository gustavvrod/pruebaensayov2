<template>
  <main class="container">
    <div class="card row mx-auto" style="max-width: 300px">
      <form class="col-sm">
        <h2>Login Usuarios</h2>
        <div class="form-group">
          <label for="exampleInputEmail1">Email</label>
          <input
            type="email"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">Contraseña</label>
          <input
            type="password"
            class="form-control"
            id="exampleInputPassword1"
          />
        </div>
        <small id="emailHelp" class="form-text text-muted"
          >Ingrese sus credenciales de Usuario.</small
        >
        <button type="submit" class="btn btn-primary">Ingresar</button>
      </form>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style>
</style>