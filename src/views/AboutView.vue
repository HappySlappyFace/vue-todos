<template>
  <main>
    <div class="about">
      <h1>Todos</h1>
      <p>This is a small project done following a crash course on YouTube.</p>
      <p>The crash course can be found <a href="https://www.youtube.com/watch?v=KTFH4P8unUQ" class="link">here</a> made by
        <a href="https://www.youtube.com/@JohnKomarnicki" class="link">John Komarnicki.</a>
      </p>
    </div>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}

main {
  display: flex;
  flex-direction: column;

  max-width: 500px;
  width: 100%;
  margin: 0 auto;
  padding: 40px 16px;

  .link {
    color: crimson;
    font-weight: 500;
  }

  .about h1 {
    text-align: center;
    margin-bottom: 1rem;
  }
}
</style>
