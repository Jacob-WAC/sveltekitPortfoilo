<script lang="ts">

</script>
<nav>
    <a href="/"><h1>J -> J</h1></a>
    <a href="/settings"><p>Information</p></a>
</nav>

    <slot></slot>


<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300&display=swap');

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: rgba(209, 209, 209, 0);
        position: fixed;
        top: 0;
        width: 100%;

        a {
            margin-top: 2vw;
            margin-left: 2vw;
            margin-right: 2vw;
            text-decoration: none;
            color: black; 
            font-family: 'Quicksand', sans-serif;

            :visited {
                color: black;
                text-decoration: none;
                    }           
            
            h1{
            font-size:2.5em;
            
            }

            p{
            font-size: 1.5em;
            margin-top: .2vw;
            
            
            }

            }

    }
</style>