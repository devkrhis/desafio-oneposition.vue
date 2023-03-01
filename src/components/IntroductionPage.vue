<template>
    <div class="topPage">
            <p class="firstLine"> Join our community </p>
            <p class="secondLine"> 30-day, hassle-free money back guarantee </p>
            <p class="thirdLine"> Gain access to our full library of tutorials along with expert code reviews.
            Perfect for any developers who are serious about honing their skills. </p>
            
    </div>
    
</template>

<script>
export default {
    data(){
        return {

        }
    }
    
}
</script>

<style scoped>

.topPage {
    background-color: white;
    display: flex;
    flex-direction: column;
    border: 1px solid black;
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    max-width: 750px;
    height: 200px;
    padding-left: 50px;
    padding-top: 20px;
    align-items: flex-start;
    

}

.firstLine {
    color: #6dc0ac;
    font-size: xx-large;
    margin-bottom: 10px;
}

.secondLine {
    color: #d3df98;
    font-size: large;
    margin-bottom: 10px;
}

.thirdLine {
    color: #dcdbde;
    margin-top: 0px;
    margin-bottom: 50px;
}



</style>