<nav>
    <ul>
        <li class="dropdown">
            <a href="#">Classes</a>
        </li>
        <li><a href="/">Home</a></li>

    </ul>
</nav>
<slot />
<style>
    :global(body) {
        font-family: Arial,ui-sans-serif,system-ui,sans-serif,"Apple Color Emoji","Segoe UI Emoji",Segoe UI Symbol,"Noto Color Emoji";
        padding: 0;
        margin: 0;
    }
    nav {
        background-color: rgba(50, 50, 50, 0.8);
        text-transform: uppercase;
        
        position: fixed;
        left: 0;
        top: 0;
        width: 100%;
        overflow: hidden;
        z-index: 1000;
    }
    nav ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
    nav ul li {
        float: right;
    }
    nav ul li a {
        display: block;
        color: white;
        text-align: center;
        padding: 20px 16px; 
        text-decoration: none;
        font-size: 15px; 
        letter-spacing: 1px; 
    }
    nav ul li a:hover {
        color: lightgray;
    }
</style>
