<script lang="ts" setup>
</script>

<template>
    <main class="flex justify-center items-center flex-col p-4">
        <div class="paper-width mb-4">
            <button class="btn btn-primary">
                + New entry
            </button>
        </div>

        <div class="paper">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. At blanditiis dolor dolorem id iusto saepe
                sapiente totam. Animi cum cupiditate deleniti eius inventore magnam nostrum officiis temporibus
                voluptatibus? Adipisci assumenda autem commodi fuga nisi non quisquam reiciendis similique vero
                voluptatem.
            </p>

            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. At blanditiis dolor dolorem id iusto saepe
                sapiente totam. Animi cum cupiditate deleniti eius inventore magnam nostrum officiis temporibus
                voluptatibus? Adipisci assumenda autem commodi fuga nisi non quisquam reiciendis similique vero
                voluptatem.
            </p>

            <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                    allowfullscreen frameborder="0"
                    height="250" src="https://www.youtube.com/embed/8aRor905cCw"
                    title="YouTube video player"
                    width="500"></iframe>
        </div>
    </main>
</template>

<style lang="scss" scoped>
  .paper-width {
    width: 27vw;
    max-width: 1000px;
    min-width: 700px;

  }

  .paper {
    width: 27vw;
    max-width: 1000px;
    min-width: 700px;
    height: calc(27vw * 1.4143);
    max-height: calc(1000px * 1.4143);
    min-height: calc(700px * 1.4143);
    background-color: #fff;
    margin: 0 auto;
    padding: 1cm;
    @apply rounded shadow-lg;

    // Apply style for paragraph
    p {
      @apply mb-4 text-sm text-gray-700;
    }

    // Apply style for iframe
    iframe {
      @apply shadow-sm rounded;
    }
  }
</style>
