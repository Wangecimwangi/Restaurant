<script setup>

</script>

<template>
    <!-- Carousel -->
    <v-container>
        <v-row>
            <v-carousel>
                <v-carousel-item src="/images/volkan-vardar-1H30uRC1plc-unsplash.jpg"><</v-carousel-item>
                <v-carousel-item src="/images/public/images/victoria-shes-UC0HZdUitWY-unsplash.jpg"><</v-carousel-item>
                <v-carousel-item src="/images/pablo-merchan-montes-hyIE90CN6b0-unsplash.jpg"><</v-carousel-item>
                <v-carousel-item src="images/siyuan-g_V2rt6iG7A-unsplash.jpg"><</v-carousel-item>
            </v-carousel>

        </v-row>
    </v-container>
    <!-- About -->
    <v-container>
        <v-row>
            <v-card align="center">
                <p class="text-h4"><b>Welcome to Suvaya</b></p>
                <p class="text-h6">Welcome to Suvaya, where timeless tradition meets bold, modern flavors. Nestled in the heart of the city, Suvaya is more than just a restaurant — it’s a celebration of heritage, storytelling, and sensory delight.</p>
                <p class="text-h6">At Suvaya, every dish is a journey. Inspired by ancient spice routes, village kitchens, and forgotten family recipes, our menu blends rustic techniques with contemporary presentation. From slow-cooked curries to fire-grilled vegetables and handcrafted desserts, each plate is designed to awaken the senses.</p>
                <p class="text-h6">Our name, Suvaya, comes from an old word meaning “joyful flavor” — and that’s exactly what we aim to deliver. Whether you're here for a quick lunch or a long, leisurely dinner, our team is dedicated to providing warm service, exceptional taste, and an atmosphere that feels like home.</p>
            </v-card>
        </v-row>
    </v-container>
    <!-- News -->
    <v-container>
        <v-row>
            <v-col md="4">
                <v-card color="teal-darken-3">
                    <v-img 
                    src="/images/public/images/joseph-gonzalez-fdlZBWIP0aM-unsplash.jpg" 
                    class="align-end text-white" 
                    height="200" 
                    cover>
                </v-img>
                <v-card-title>Sample Text</v-card-title>
                <v-card-subtitle> another sample text</v-card-subtitle>
                <v-card-actions>
                    <v-btn> Read More</v-btn>
                </v-card-actions>
                </v-card>
            </v-col>
               <v-col md="4">
                <v-card color="teal-darken-3">
                    <v-img 
                    src="/images/public/images/igor-rand-wfM1Fi-kMaY-unsplash.jpg" 
                    class="align-end text-white" 
                    height="200" 
                    cover>
                </v-img>
                <v-card-title>Sample Text</v-card-title>
                <v-card-subtitle> another sample text</v-card-subtitle>
                <v-card-actions>
                    <v-btn> Read More</v-btn>
                </v-card-actions>
                </v-card>
            </v-col>   
              <v-col md="4">
                <v-card color="teal-darken-3">
                    <v-img 
                    src="/images/public/images/volkan-vardar-1H30uRC1plc-unsplash (1).jpg" 
                    class="align-end text-white" 
                    height="200" 
                    cover>
                </v-img>
                <v-card-title>Sample Text</v-card-title>
                <v-card-subtitle> another sample text</v-card-subtitle>
                <v-card-actions>
                    <v-btn> Read More</v-btn>
                </v-card-actions>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
    <!-- Footer -->
    <v-container>
        <v-row>
            <v-footer class="text-center d-flex flex-column ga-2 py-4" color="deep-purple-lighten-1">
                
                <v-btn icon="'mdi-facebook'" density="comfortable" variant="text" ></v-btn>
                <v-btn icon="'mdi-twitter'" density="comfortable" variant="text" ></v-btn>
                <v-btn icon="'mdi-linkepurple-lighten-1din'" density="comfortable" variant="text" ></v-btn>
                <v-btn icon="'mdi-instagram'" density="comfortable" variant="text" ></v-btn>
                </div>

                <v-divider class="my-2" thickness="2" width="50"></v-divider>

                <div class="text-caption font-weight-regular opacity-60">
                Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet. Mauris cursus commodo interdum. Praesent ut risus eget metus luctus accumsan id ultrices nunc. Sed at orci sed massa consectetur dignissim a sit amet dui. Duis commodo vitae velit et faucibus. Morbi vehicula lacinia malesuada. Nulla placerat augue vel ipsum ultrices, cursus iaculis dui sollicitudin. Vestibulum eu ipsum vel diam elementum tempor vel ut orci. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
                </div>

                <v-divider></v-divider>

                <div>
                {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
                </div>
            </v-footer>
        </v-row>
    </v-container>

<v-container>
    <v-row></v-row>
</v-container>
</template>