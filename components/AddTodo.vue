<template>
  <div class="text-center mt-12">
      <v-dialog v-model="addtododialog" width="500">
        <template v-slot:activator="{ on }">
          <v-btn depressed outlined color="red" v-on="on">
            <v-icon left>mdi-plus</v-icon>Add task
          </v-btn>
        </template>

        <v-card>
          <v-card-title primary-title>Add task</v-card-title>
          <v-divider></v-divider>

          <v-card-actions>
            <v-text-field label="What do you wanna do?"></v-text-field>
            <div class="flex-grow-1"></div>
            <v-btn class="red" outlined @click="addtododialog = false">Add task</v-btn>
          </v-card-actions>
        </v-card>
      </v-dialog>
    </div>
</template>

<script>
export default {
  data() {
    return {
      addtododialog: false
    };
  }
};
</script>

<style>
</style>

