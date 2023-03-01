<template>
    <div id="initialGrade">
        <div class="topPage"> 
            <IntroductionPage/>
        </div>
        <div class="bottomPage"> 
            <RegistrationPage/>
            <WhyUsPage/>
        </div>
    </div>
    
</template>

<script>
import IntroductionPage from './IntroductionPage.vue'
import RegistrationPage from './RegistrationPage.vue'
import WhyUsPage from './WhyUsPage.vue'

export default {
    components: {
        IntroductionPage,
        RegistrationPage,
        WhyUsPage
    }

}
</script>

<style scoped>

#initialGrade {
    background-color: gray;
    width: 100%;
    height: 100%;
}

.topPage {
    display: flex;
    justify-content: center;
}

.bottomPage {
    display: flex;
    justify-content: center;
}

</style>