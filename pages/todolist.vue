<template>
  <v-app dark class="mt-12 mx-12">
    <v-content>
      <v-container>
        <v-list>
          <v-list-item v-for="i in 5" :key="i">
            <v-btn height="50px" width="5px"><v-icon>mdi-drag_indicator</v-icon></v-btn><v-text-field disabled=false value=" make todo list app" filled></v-text-field>
          </v-list-item>
        </v-list>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
    data(){
        return{

        }
    }
};
</script>

<style>
</style>