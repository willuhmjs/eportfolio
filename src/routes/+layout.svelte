<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/about-me">About Me</a></li>
        <li><a href="/blog">Blog</a></li>
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
    }
    nav {
        background-color: #333;
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
        background-color: #f9f9f9;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index: 1;
    }
    nav ul li .dropdown-content a {
        color: black;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
        text-align: left;
    }
    nav ul li .dropdown-content a:hover {
        background-color: #f1f1f1;
    }
    nav ul li:hover .dropdown-content {
        display: block;
    }
</style>
