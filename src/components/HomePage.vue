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
    height: auto;
}

.topPage {
    display: flex;
    justify-content: center;
}

.bottomPage {
    display: flex;
    justify-content: center;
}


@media (max-width: 600px){
    .topPage{
        display: flex;
        flex-direction: column;
    }
}

@media (max-width: 600px){
    .bottomPage{
        display: flex;
        flex-direction: column;
    }
}

</style>