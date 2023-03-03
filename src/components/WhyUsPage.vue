<template>
    <div class="rightPage">
        <h1> Why Us</h1>
        <h3> 
            <p> Tutorials by industry experts </p>
            <p> Peer & expert code review </p>
            <p> Coding exercises </p>
            <p> Access to our GitHub repos </p>
            <p> Community forum </p>
            <p> Flashcard decks </p>
            <p> New videos every week</p>
        </h3>

    </div>
    
</template>

<script>
export default {
    
}
</script>

<style scoped>

.rightPage {
    border: 0px solid black;
    width: 325px;
    height: 300px;
    background-color: #4bbcbf;
    border-end-end-radius: 10px;
    color: #bfebe7;
    padding-left: 50px;
    padding-top: 20px;
    align-items: flex-start;
}

.rightPage h1 {
    color: white;
}

.rightPage h3 {
    font-size: x-small;
}

@media (max-width: 700px){
    .rightPage{
        width: 200px;
        height: 300px;
        margin-left: 10px;
        display: flex;
        flex-direction: column;
        border-end-end-radius: 10px; border-end-start-radius: 0px;
    }
    
    
}

</style>