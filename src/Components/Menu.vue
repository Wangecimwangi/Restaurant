<script setup>

const menu = {
    1:{
        name: 'The Clubhouse Snadwich',
        image: "/images/menu/aigars-peda-a_iKAg00LN4-unsplash.jpg",
        price: 950,
        description: 'A delicacy made of bread,beef and cheese.',
        category:'Sides'
    },
    2:{
        name:'Garlic Garden',
        image:"/images/menu/brooke-lark-oaz0raysASk-unsplash.jpg",
        price: 550,
        description:'Fresh greens with sauteed mushrooms,garlic and herbs.',
        category: 'Salads'
    },
    3:{
        name: 'Street-Style Tacos',
        image:"/images/menu/chad-montano-lP5MCM6nZ5A-unsplash.jpg",
        price:650,
        description:'Soft tortillas filled with seasoned meat,fresh veggies and zesty salsa.',
        category:'Mains'
    },
    4:{
        name:'Tropicana Pizza',
        image:"/images/menu/chad-montano-MqT0asuoIcU-unsplash.jpg",
        price:1200,
        description:'A cheesy classic topped with sweet pineaapple chunksand savory ham for the perfect tropical twist.',
        category: 'Mains'
    },
    5:{
        name:'Fire and Flavor wings',
        image:"/images/menu/george-zheng-0Kbjfwunink-unsplash.jpg",
        price: 750,
        description:'Crispy chicken wings tossed in your choice of sauce.',
        category: 'Mains'
    },
    6:{
        name:'Strawberry Cream Cup',
        image:"/images/menu/karly-gomez-lK1Q5RyD6tc-unsplash.jpg",
        price: 500,
        description:'Layers of silky cream cheese and sweet strawberries.',
        category: 'Desserts'
    },
    7:{
        name: 'Creamy Broccoli Pasta',
        image:"/images/menu/karolina-kolodziejczak-gRtIRzDNZQI-unsplash.jpg",
        price: 1050,
        description: 'Pasta rich in,creamy sauce with tender broccoli florets.',
        category: 'Mains'
    },
    8:{
        name: 'Curry Coast Fish',
        image:"/images/menu/khloe-arledge-ND3edEmzcdQ-unsplash.jpg",
        price: 1300,
        description: 'Tender fish simmered in a rich,spiced curry sauce.',
        category: 'Mains'
    },
    9:{
        name: 'Ocean Rice',
        image:"/images/menu/louis-hansel-mVZ_gjm_TOk-unsplash.jpg",
        price: 1250,
        description: 'Fluffy rice stir-fried with juicy prawns.',
        category: 'Mains'
    },
    10:{
        name:'Tuscan Tomato Salad',
        image:"/images/menu/luisa-brimble-vIm26fn_QKg-unsplash.jpg",
        price: 800,
        description: 'Fresh tomatoes and cherry tomatoes with crunchy bread cubes and herbs in a light dressing.',
        category: 'Salads'
    },
    11:{
        name: 'Homestyle Chicken Spaghetti',
        image:"/images/menu/mae-mu-H5Hj8QV2Tx4-unsplash.jpg",
        price: 1100,
        description: 'Classic spaghetti served with rich soup and a tender piece of chicken.',
        category: 'Mains'
    },
    12:{
        name: 'Fresh Catch Plate',
        image:"/images/menu/martin-widenka-tkfRSPt-jdk-unsplash.jpg",
        price: 1250,
        description: 'A tender piece of fish served with fresh garden salad and a side of dressing or soup.',
        category: 'Mains'
    }
}

</script>

<template>
    <h1>Menu</h1>
    <v-container>
        <v-row>
            <v-col md="3" v-for="item in menu" :key = "item">
                <v-card color="teal-darken-3">
                    <v-img :src="item.image" height="200 .cover"></v-img>
                    <v-row>
                        <v-col md="6">
                            <v-card-title>{{item.name}}</v-card-title>
                        </v-col>
                        <v-col md="6">
                            <v-chip>{{item.category}}</v-chip>
                        </v-col>
                    </v-row>
                    <v-card-subtitle>{{ item.description }}</v-card-subtitle>
                    <v-card-actions>
                        <v-card-title>{{ item.price }}</v-card-title>
                        <v-btn>Order</v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
        </v-row>
    </v-container>


</template>