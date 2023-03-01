<template>
  <div class="login">
    <h1>Ulogujte se!</h1>
    <div class="container">
      <div class="row">
        <div class="col-sm"></div>
        <div class="col-sm">
          <form>
            <div class="form-group">
              <h4 for="exampleInputEmail1">Email adresa</h4>
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Enter email"
              />
            </div><br>
            <div class="form-group">
              <h4 for="exampleInputPassword1">Lozinka</h4>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Password"
              />
            </div>
            <button type="button" class="btn btn-primary">Posalji</button>
          </form>
        </div>
        <div class="col-sm"></div>
      </div>
    </div>
  </div>
</template>
