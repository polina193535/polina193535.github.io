<script lang="ts">  
</script>
<div class="header">
<nav id="desktop-nav">
        <div class="logo">Personal portfolio website</div>
        <div>
            <ul class="nav-links">
                <li><a href="/">Home</a></li>
                <li><a href="/about">About Me</a></li>
                <li><a href="/experience">Experience</a></li>
                <li><a href="/projects">Projects</a></li>
                <li><a href="/contacts">Contact Me</a></li>
                <li><a href="/comic">XKCD Comic</a></li>
                <li>
                    <div class="bth-container" style="position: relative; top: -5px;">
                    </div>
                </li>
            </ul>
        </div>
</nav>  
</div>

<div class="footer">
    <p class="section__text__p2">Made in Innopolis University</p>
</div>



<slot>
    
</slot>

<style>

@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap");

* {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
}

nav, 
.nav-links {
    display: flex;
}

nav {
    justify-content: space-around;
    align-items: center;
    height: 17vh;
}

.nav-links {
    gap: 2rem;
    list-style: none;
    font-size: 1.5rem;
}

a {
    color: black;
    text-decoration: none;
    text-decoration-color: white;
    transition: all 300ms ease;
}

a:hover {
    color: grey;
    text-decoration: underline;
    text-underline-offset: 0.5rem;
    text-decoration-color: rgb(181, 181, 181);

}

.logo {
    font-size: 2rem;
}

.logo:hover {
    cursor: default;
}


.footer {
    position: fixed;
    bottom: 0;
    
  }

  .section__text__p2 {
    margin: 0;
    padding-left: 40px;
  }

</style>
