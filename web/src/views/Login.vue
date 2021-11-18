<template>
  <div class="login">
    <form method="post">
      <div class="box">
        <h1>msrXiv Login</h1>

        <input type="email" placeholder="email" v-model="email" class="email" />

        <input type="password" placeholder="password" class="password" />
    <a href="#"><div class="btn">Sign In</div></a>
    <a href="#"><div id="btn2">Sign Up</div></a>
      </div>
    </form>
    <p class="pwdreset">Forgot your password? <u style="color:#f1c40f;">Click Here!</u></p>

  </div>
</template>

<script>

</script>

<style>

.box{
  background:white;
  width:300px;
  border-radius:6px;
  margin: 0 auto 0 auto;
  padding:0px 0px 70px 0px;
  border: #009cbc 4px solid;
}

.email{
  background:#ecf0f1;
  border: #ccc 1px solid;
  border-bottom: #ccc 2px solid;
  padding: 8px;
  width:250px;
  margin-top:10px;
  font-size:1em;
  border-radius:4px;
}

.password{
  border-radius:4px;
  background:#ecf0f1;
  border: #ccc 1px solid;
  padding: 8px;
  width:250px;
  font-size:1em;
}
.email::placeholder{
  color: #aaaaaa
}
.password::placeholder{
  color: #aaaaaa;
}
.btn{
  background:#2ecc71;
  width:125px;
  padding-top:5px;
  padding-bottom:5px;
  color:white;
  border-radius:4px;
  border: #009cbc 1px solid;

  margin-top:20px;
  margin-bottom:20px;
  float:left;
  margin-left:16px;
  font-weight:800;
  font-size:0.8em;
}

.btn:hover{
  background:#1ebc61;
}

#btn2{
  float:left;
  background:#009cbc;
  width:125px;  padding-top:5px;
  padding-bottom:5px;
  color:white;
  border-radius:4px;
  border: #2980b9 1px solid;

  margin-top:20px;
  margin-bottom:20px;
  margin-left:10px;
  font-weight:800;
  font-size:0.8em;
}

#btn2:hover{
  background:#008cac;
}

</style>