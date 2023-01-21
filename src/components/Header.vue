<template>
    <div class="navigation">
        <div class="elements">
            <div class="levo">
                <a href="">Domov</a>
                <a href="">Trgovina</a>
                <a href="">Kontakt</a>
            </div>
            <form action="." method="post">
                <input class="bar" type="text" name="search" id="search" placeholder="Search...">
            </form>
            <div>
                <a href="">Login</a>
                <a href="">Cart</a>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
.navigation {
    background-color: whitesmoke;
    box-shadow: 0 5px 2px -2px rgb(175, 175, 175);
    padding: 20px;
}

.elements {
    align-items: center;
    width: 1024px;
    margin: auto;
    display: flex;
    justify-content: space-between;
}

.levo {
    display: flex;
    gap: 15px;
}

a {
    text-decoration: none;
    color: black;
}
a:hover{
    background-color: rgb(211, 210, 209);
    
}
.bar {
    display: flex;
    height: 40px;
    width: 500px;
    margin-left: 20px;
    background-color: rgb(160, 159, 159);
    border-radius: 20px;
    outline: 0;
    border: 0;
    padding: 3px 16px;
}

</style>
