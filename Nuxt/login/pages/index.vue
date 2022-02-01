<template>
  <div class="login">
    <form action="">

      <div class="boxuser">
        <font-awesome-icon :icon="['fas', 'user']"/>
        <input type="text" placeholder="user" id="user">
      </div>

      <div class="boxpasword">
        <font-awesome-icon :icon="['fas', 'lock']"/>
        <input type="password" placeholder="password" id="password">
      </div>

      <button class="access">Login</button>
    </form>
  </div>
    
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style lang="css">
html{
  width: 100%;
  height: 100%;
  background: #B6D7F5;  
}

.login{
  text-align: center;
  flex-direction: column;
  justify-content: center;
}

input{
  width: 350px;
  height: 40px;
  margin-bottom: 30px;
}

.access{
  width: 100px;
  height: 40px;
  background: transparent;
  border-color: black;
  border-radius: 3px;
}

</style>>

