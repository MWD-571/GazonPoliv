<template>
    <div class="home-page">
        <HomeSection />
        <InformationSection />
        <WelcomeSection />
        <PlantSection />
        <ServiceSection />
        <GallerySection />
        <RatingSection />
        <ContactSection />
        <MapSection />
    </div>
</template>
<script>
import HomeSection from '../../pages/HomePage/HomeSections/HomeSection.vue'
import InformationSection from './HomeSections/InformationSection.vue';
import WelcomeSection from './HomeSections/WelcomeSection.vue';
import PlantSection from './HomeSections/PlantSection.vue';
import ServiceSection from './HomeSections/ServiceSection.vue';
import GallerySection from './HomeSections/GallerySection.vue';
import RatingSection from './HomeSections/RatingSection.vue';
import ContactSection from './HomeSections/ContactSection.vue';
import MapSection from './HomeSections/MapSection.vue';
export default {
    components: {
        HomeSection,
        InformationSection,
        WelcomeSection,
        PlantSection,
        ServiceSection,
        GallerySection,
        RatingSection,
        ContactSection,
        MapSection
    }
}
</script>