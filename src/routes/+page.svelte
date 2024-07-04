<script lang="ts">  
    
  import abouth from '../img/photo_5422819102726151849_x.jpg';
  import Layout from "./_layout.svelte";
  
 
</script>


<body>
    <Layout></Layout>
    <section id="profile">
        <div class="section__pic-container">
            <img src={abouth}
                alt="" style="border-radius: 50%;">
        </div>
        <div class="section__text">
            <p class="section__text__p1">Hello, I'm</p>
            <h1 class="title">Polina Kostikova </h1>
            <p class="section__text__p2">Innopolis University Student</p>
        </div>
    </section>

</body>

<style>

@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap");

* {
  margin: 0;
  padding: 0;
  font-family: "Poppins", sans-serif;
}


#profile {
    display: flex;
    justify-content: center;
    gap: 5rem;
    height: 80vh;
}

.section__pic-container {
    display: flex;
    height: 400px;
    width: 400px;
    margin: auto 0;
}

.section__text {
    align-self: center;
    text-align: center;
}

.section__text p {
    font-weight: 600;
}

.section__text__p1 {
    text-align: center;
}

.section__text__p1 {
    font-size: 1.6rem;
    margin-bottom: 1rem;
}

.title {
    font-size: 3rem;
    text-align: center;

}

#profile {
    display: flex;
    justify-content: center;
    gap: 5rem;
    height: 80vh;
}

.section__pic-container {
    display: flex;
    height: 400px;
    width: 400px;
    margin: auto 0;
}

.section__text {
    align-self: center;
    text-align: center;
}

.section__text p {
    font-weight: 600;
}

.section__text__p1 {
    text-align: center;
}

.section__text__p1 {
    font-size: 1.6rem;
    margin-bottom: 1rem;
}

.title {
    font-size: 3rem;
    text-align: center;

}

p {
  color: rgb(85, 85, 85);
}

</style>
