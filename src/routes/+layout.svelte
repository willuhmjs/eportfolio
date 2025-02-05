<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li class="dropdown">
            <a href="#" class="dropbtn">Classes</a>
            <div class="dropdown-content">
                <a href="/classes/cyse200t">CYSE200T</a>
            </div>
        </li>
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
        background-color: rgba(50, 50, 50, 0.9);
        position: fixed;
        left: 0;
        top: 0;
        width: 100%;
        overflow: hidden;
    }
    nav ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
    nav ul li {
        float: left;
    }
    nav ul li a {
        display: block;
        color: white;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
    }
    nav ul li a:hover {
        background-color: #111;
    }
    nav ul li.dropdown {
        display: inline-block;
    }
    nav ul li .dropdown-content {
        display: none;
        position: absolute;
        background-color: #333;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index: 1;
    }
    nav ul li .dropdown-content a {
        color: #e0e0e0;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
        text-align: left;
    }
    nav ul li .dropdown-content a:hover {
        background-color: #111;
    }
    nav ul li:hover .dropdown-content {
        display: block;
    }
</style>
