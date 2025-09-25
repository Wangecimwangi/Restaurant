<script setup>
const menuItem= {
        name: 'The Clubhouse Snadwich',
        image: "/images/menu/aigars-peda-a_iKAg00LN4-unsplash.jpg",
        price: 950,
        description: 'A delicacy made of bread,beef and cheese.',
        category:'Sides'
    }

</script>

<template>
    <v-container fluid class="d-flex fill-height" align="center">
        <v-row>
            <V-col md="6">
                <v-card  class="pa-6 rounded-lg" justify="center">
                    <v-img :src="menuItem.image" cover height="500"></v-img>
                </v-card>
            </V-col>
             <V-col md="6">
                <v-card class="pa-6 rounded-lg" justify="center">
                    <v-card-title>({menuItem.name})</v-card-title>
                    <v-card-subtitle>({menuItem.price})</v-card-subtitle>
                    <v-card-text>({menuItem.description})</v-card-text>
                    <v-card-text>Quantity <v-text-field></v-text-field></v-card-text>
                    <v-card-actions>
                        <v-btn color="teal-darken-3">Order</v-btn>
                    </v-card-actions>
                </v-card>
            </V-col>
        </v-row>
    </v-container>
</template>