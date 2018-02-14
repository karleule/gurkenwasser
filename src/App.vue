<template>
    <v-app>
        <v-toolbar>
            <div>
                Welcome to Gurkenwasser
            </div>
        </v-toolbar>
        <v-content>
            <v-container fill-height>
                <v-layout justify-center align-center>
                    Welcome to Gurkenwasser!
                </v-layout>
            </v-container>
        </v-content>
        <v-footer :fixed="fixed" app>
            <span>&copy; 2017</span>
        </v-footer>
    </v-app>
</template>

<script>
export default {
    data () {
      return {
        title: 'Gurkenwasser',
        fixed: false
      }
    }
}
</script>