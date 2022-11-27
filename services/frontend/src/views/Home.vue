<template>
  <section>
    <p>Exploiter les pokémon dans notre site Wiki Pokémon</p>

    <div v-if="isLoggedIn" id="logout">
      <p id="logout">Cliquer sur <a href="/dashboard">ici</a> pour accéder la liste des pokémon.</p>
    </div>
    <p v-else>
      <span>Pour accéder dans notre site Wiki Pokémon, vous pouvez : </span>
      <span><a href="/register">Créer un compte</a></span>
      <span> ou </span>
      <span><a href="/login">Se connecter</a></span>
    </p>
  </section>
</template>
<script>

export default {
  name: 'Home',
  computed : {
    isLoggedIn: function() {
      return this.$store.getters.isAuthenticated;
    }
  },
}
</script>
