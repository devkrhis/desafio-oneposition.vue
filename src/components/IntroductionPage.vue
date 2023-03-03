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
    width: 700px;
    flex-direction: column;
    border: 0px solid black;
    border-top-right-radius: 10px;
    border-top-left-radius: 10px;
    padding-left: 50px;
    padding-top: 20px;
    align-items: flex-start;
    margin-top: 50px;
    

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
    word-wrap: break-all;
    width: 600px;
}

@media (max-width: 700px){
    .topPage{
        width: 200px;
        height: 250px;
        margin-left: 10px;
        display: flex;
        flex-direction: column;
    }

    .firstLine {
        font-size: x-large;
    }

    .secondLine {
    font-size: medium;
}
    .thirdLine{
        width: 150px;
        word-wrap: break-word;
    }
    
}


</style>