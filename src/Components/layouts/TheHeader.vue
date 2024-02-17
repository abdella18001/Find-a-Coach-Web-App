<template>
    <header>
        <nav>
            <h1>
                Find a Coach
            </h1>
            <div>
                <button>All Coaches</button>
                <button>Requests</button>
            </div>
        </nav>
    </header>
</template>

<style scoped>
header{
    background-color: #3D008D;
    padding: 1rem 3.5rem ;

}
nav{
    color: #fff;
    display: flex;
    justify-content:space-between;
    align-items: center;
}
h1{
    margin: 0;
}

button{
    font-size: 16px;
    background-color: transparent;
    border: none;
    color: #ED86E0;
    margin: 0 0.5rem;
    padding: 0.7rem 1.3rem;
    cursor: pointer;
    border: 0.1rem solid transparent ;

}

button:hover,
button:active{
    border-color: #ED86E0 ;
}
</style>