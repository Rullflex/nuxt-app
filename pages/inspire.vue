<template>
    <v-row>
        <v-col class="text-center">
            <img src="/v.png" alt="Vuetify.js" class="mb-5" />
            <blockquote class="blockquote">
                &#8220;First, solve the problem. Then, write the code.&#8221;
                <footer>
                    <small>
                        <em>&mdash;John Johnson</em>
                    </small>
                </footer>
            </blockquote>
        </v-col>
    </v-row>
</template>

<script>
import { Vue, Component } from 'vue-property-decorator';

@Component
export default class InspirePage extends Vue {}
</script>
