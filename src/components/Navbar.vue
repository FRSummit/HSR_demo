<template>
    <div class="navbar">
        <div class="title-section">
            <span>My Awsome Website</span>
            <span style="margin-left: 20px;">{{ $route.name }}</span>
        </div>
        <div class="menu-section">
            <router-link to="/">
                <button>Home</button>
            </router-link>
            <router-link to="/profile">
                <button>Profile</button>
            </router-link>
            <router-link to="/about">
                <button>About</button>
            </router-link>
            <router-link to="/contact">
                <button>Contact</button>
            </router-link>
        </div>
    </div>
</template>

<style scoped>
.navbar {
    width: 100%;
    padding: 10px;
    text-align: left;
    background: #11d885;
    overflow: hidden;
}
.title-section {
    display: inline-block;
}
.title-section span {
    font-size: 20px;
    font-weight: bold;
    font-family: Arial, sans-serif;
}
.menu-section {
    display: inline-block;
    float: right;
}
.menu-section button {
    border: 2px solid #272727;
    padding: 6px 10px;
    margin: 0 4px;
    width: 100px;
    background: #dedede;
    color: #272727;
    border-radius: 8px;
}
</style>