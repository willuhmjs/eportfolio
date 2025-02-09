<nav>
    <ul>
        <li class="dropdown">
            <a href="#">Capstone Courses</a>
            <div class="dropdown-content">
                <a href="/c/cyse368">CYSE 368</a>
            </div>
        </li>
        <!-- <li class="dropdown">
            <a href="#">Principles Courses</a>
            <div class="dropdown-content">
            </div>
        </li> -->
        <li class="dropdown">
            <a href="#">Application Courses</a>
            <div class="dropdown-content">
                <a href="/c/cyse270">CYSE 270</a>
            </div>
        </li>
       
        <li class="dropdown">
            <a href="#">Core Courses</a>
            <div class="dropdown-content">
                <a href="/c/cyse200t">CYSE 200T</a>
            </div>
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
        background-color: #f9f9f9;
    }
    nav {
        background-color: rgba(50, 50, 50, 0.8);
        text-transform: uppercase;
        position: fixed;
        left: 0;
        top: 0;
        width: 100%;
        overflow: visible;
        z-index: 1000;
    }
    nav ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
    nav ul li {
        float: right;
        position: relative;
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
    .dropdown-content {
        display: none;
        position: absolute;
        top: 100%;
        right: 0;
        background-color: rgba(50, 50, 50, 0.9);
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index: 1001;
        min-width: 100%;
    }
    .dropdown-content a {
        color: white;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
        text-align: right;
    }
    .dropdown-content a:hover {
        background-color: rgba(70, 70, 70, 0.8);
    }
    .dropdown:hover .dropdown-content {
        display: block;
    }
</style>
