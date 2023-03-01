<template>
    <div class="leftPage">
        <h3> Monthly Subscription </h3>
        <div class="CustomLineBreak">
            <h1> ${{ valueMonth }} </h1>
            <h3> per month </h3>
        </div>
        <h3> Full access for less than $1 a day </h3>
        <a> <button> Sign Up </button> </a>
    </div>
    
</template>

<script>
export default {
    data(){
        return{
            valueMonth: 29
        }
    }
    
}
</script>

<style scoped>

.leftPage {
    border: 1px solid black;
    background-color: #2cb3af;
    width: 348px;
    height: 300px;
    border-end-start-radius: 10px;
    padding-left: 50px;
    padding-top: 20px;
    display: flex;
    flex-direction: column;
}

.leftPage h2 {
    color: white;
}

.leftPage h1 {
    color: white;
}

.leftPage h3 {
    color: white;
}

.CustomLineBreak {
    display: flex;
    justify-content: flex-start;
}

.CustomLineBreak h3 {
    margin-top: 35px;
    margin-left: 15px;
    color: rgba(199, 199, 199, 0.795);
    font-size: medium
}




</style>