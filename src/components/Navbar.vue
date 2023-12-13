<template>
    <div>
        <nav>
            <div class="navbar">
                <div class="left">
                    <div class="logo">
                        <a href="">
                            <img src="https://i.postimg.cc/mgn37vDw/aak-high-resolution-logo-black-on-transparent-background1.png"
                                alt="">
                        </a>
                    </div>
                </div>
                <div class="right">
                    <div class="menu">
                        <ul>
                            <li><a href="">Home</a></li>
                            <li><a href="">About</a></li>
                            <li><a href="">Education & Skills</a></li>
                            <li><a href="">Projects</a></li>
                            <li><a href="">Testimonials</a></li>
                            <li><a href="">Contact</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.navbar {
    width: 100%;
    height: 3rem;
    display: flex;
    position: fixed;
    /* border-bottom: 1px solid red; */
}

.left {
    width: 30%;
    height: 100%;
    /* border: 1px solid black; */
    display: flex;
    justify-content: start;
    align-items: center;
    padding-left: 5rem;
}

.right {
    width: 70%;
    height: 100%;
    /* border: 1px solid black; */
}

.left .logo {
    height: 1.2rem;
    width: 30%;
    /* border: 1px solid green; */
}

.logo a img {
    width: 100%;
    height: 100%;
}

/* .logo a img:hover {
    cursor: pointer;
} */

.right .menu {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.menu ul {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    display: flex;
    gap: 2rem;
}

.menu ul li {
    list-style: none;
}

.menu ul li a {
    text-decoration: none;
    color: black;
    font-size: 1.1rem;
}
</style>