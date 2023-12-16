<script setup>

</script>

<template>
  <main class="main" >
      <card class="row1">
        <section id="nameBox" class="nameBox">
          <h4>Gage Tranter</h4>
          <h4>SWDV-143</h4>
          <h4>12-15-2023</h4>
          <h4>Journal Entry 2</h4>
        </section>
        <section class="title">
          <h1>Vue Review</h1>
        </section>
      </card>

      <card id="card" class="card">
        <div class="cardTxtWrapper">
          <h2>Framework Summary</h2>
          <p>Working with React, I encountered many conflicting documentations due to the many versions of React. The framework was difficult to manipulate and my static files were especially difficult to link to the page.</p>
        </div>
        <div class="cardImgWrapper">
          <img src="https://i.imgur.com/hw5vCRT.jpeg" class="cardImg"/>
        </div>
      </card>

      <card id="terminalCommands" class="terminalCommands">
        <h2>Vue Project Summary</h2>
        <p>Listed below are a few of the terminal commands used to set up the Vue website</p>
        <p><code>npm create vue@latest</code> -Creates Vue Project Files</p>
        <p><code>npm run dev</code> -Builds the static site in the <strong>dist</strong> folder</p>
        <p><code>npm install</code> -Installs npm dependencies to the Project</p>   
        <p><code>npm run build</code> -Prepares the static site files</p>   
      </card>

      <card id="conversions" class="conversions">
        <h2>CSS to JSX</h2>
        <p><code>class=""</code> converts to <code>class=""</code></p>
        <p><code>style=""</code> converts to <code></code> </p>
        <p>Compared to React, loading static files in Vue was significantly easier to understand, with styles loading in the scoped style rather than linking a css to a module.</p>
      </card>

    </main>
</template>

<style scoped>
/* Styling For Id's and classes */

.nameBox{
  width: 25%;
}

.row1{
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.title{
  width: 75%;
  font-size: 2.5rem;
  color: white;
  text-shadow:
    2px 2px 0 #000,
    -2px 2px 0 #000,
    -2px -2px 0 #000,
    2px -2px 0 #000;
}

.card{
  display: flex;
  gap: 20px;

}

.cardTxtWrapper{
  flex: 1 1 100%;
}

.cardTxt{
}

.cardImgWrapper{
  max-width: 250px;
  
  padding: 1em;
}

.cardImg{
  width: 100%;
  border-radius: 25px;
  overflow: hidden;
  box-shadow: 3px 3px 10px #000;
}

.terminalCommands{
  border-radius: 25px;
  overflow: hidden;
  box-shadow: 3px 3px 10px #000;
}

.conversions{
  border-radius: 25px;
  overflow: hidden;
  box-shadow: 3px 3px 10px #000;
}
</style>