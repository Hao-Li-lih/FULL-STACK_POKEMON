<template>
  <div v-if="note">
    <p><strong>Nom de pokémon:</strong> {{ note.title }}</p>
    <p><strong>Description :</strong> {{ note.content }}</p>
    <p><strong>Editeur:</strong> {{ note.author.username }}</p>

    <div v-if="user.id === note.author.id">
      <p><router-link :to="{name: 'EditNote', params:{id: note.id}}" class="btn btn-primary">Changer les informations</router-link></p>
      <p><button @click="removeNote()" class="btn btn-secondary">Supprimer</button></p>
    </div>
  </div>
</template>


<script>
import { mapGetters, mapActions } from 'vuex';
export default {
  name: 'Note',
  props: ['id'],
  async created() {
    try {
      await this.viewNote(this.id);
    } catch (error) {
      console.error(error);
      this.$router.push('/dashboard');
    }
  },
  computed: {
    ...mapGetters({ note: 'stateNote', user: 'stateUser'}),
  },
  methods: {
    ...mapActions(['viewNote', 'deleteNote']),
    async removeNote() {
      try {
        await this.deleteNote(this.id);
        this.$router.push('/dashboard');
      } catch (error) {
        console.error(error);
      }
    }
  },
};
</script>
