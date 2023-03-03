<template>
    <div class="leftPage">
        <h3> Monthly Subscription </h3>
        <div class="CustomLineBreak">
            <h1> ${{ valueMonth }} </h1>
            <h3> per month </h3>
        </div>
        <h4> Full access for less than $1 a day </h4>
        <a href="https://www.linkedin.com/in/krhistopher-kauling-novak-b4364712a/" target="Pagina do Linkedin"> <button> Sign Up </button> </a>
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
    border: 0px solid black;
    background-color: #2cb3af;
    width: 325px;
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

.leftPage h4 {
    margin-top: 0px;
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

.leftPage button {
    color: white;
    background-color: greenyellow;
    width: 250px;
    height: 50px;
    border: none;
    border-radius: 10px;
    box-shadow: rgb(38, 57, 77) 0px 20px 30px -10px;
}

.leftPage button:hover {
    transition-delay: 2ms;
    background-color: red;
}

@media (max-width:700px){
    .leftPage{
        width: 200px;
        height: 300px;
        margin-left: 10px;
        display: flex;
        justify-items: center;
        border-end-start-radius: 0px;
        
    }

    .leftPage button {
        width: 150px;

    }

    .leftPage h4 {
        width: 150px;
        word-wrap: break-word;
    }
    
}

</style>