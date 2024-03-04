<template>
    <footer>
        <div class="footer-container">
            <div class="footer-content">
                <div class="footer-logo">
                    <img src="@/assets/Images/logo.png" alt="">
                    <p>There are many variations of passages <br>
                        of lorem ipsum available, but the
                        majority suffered.</p>
                </div>
            </div>
            <div class="footer-explore">
                <h1>Explore</h1>
                <img src="@/assets/Images/line.png" alt="">
                <div class="footer-links">
                    <router-link to="/" class="header-nav-link">Home</router-link>
                    <router-link to="/about" class="header-nav-link">About</router-link>
                    <router-link to="/services" class="header-nav-link">Services</router-link>
                    <router-link to="/projects" class="header-nav-link">Projects</router-link>
                    <router-link to="/news" class="header-nav-link">News</router-link>
                    <router-link to="/shop" class="header-nav-link">Shop</router-link>
                    <router-link to="/contact" class="header-nav-link">Contact</router-link>
                </div>
            </div>
            <div class="footer-news">
                <h1>News</h1>
                <img src="@/assets/Images/line.png" alt="">
                <div class="footer-news-data">
                    <h4>Bringing Food ProductionBack To Cities</h4>
                    <p>July 5, 2022</p>
                    <h4>The Future of Farming,Smart Irrigation Solutions</h4>
                    <p>July 5, 2022</p>
                </div>
            </div>
            <div class="footer-contact">
                <h1>Contact</h1>
                <img src="@/assets/Images/line.png" alt="">
                <div class="footer-links">
                    <router-link to="/" class="header-nav-link">666 888 0000</router-link>
                    <router-link to="/about" class="header-nav-link">needhelp@company.com</router-link>
                    <router-link to="/services" class="header-nav-link">80 broklyn golden street line
                        New York, USA</router-link>
                </div>
            </div>

        </div>
    </footer>
</template>

<style scoped>
.footer-logo p {

    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.footer-links {
    display: flex;
    flex-direction: column;
}

.footer-news-data h4 {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 16px;
}

.footer-news-data p {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 15px;
    color: #EEC044;
}

.footer-links a {
    color: #fff;
    text-decoration: none;
    font-size: 15px;
    margin-bottom: 5px;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.footer-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    color: #fff;
    padding: 20px;
    gap: 40px;
}

.footer-content {
    flex: 1;
}
</style>