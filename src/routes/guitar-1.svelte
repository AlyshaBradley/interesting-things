<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
  </script>
  
  <Header />
  <Nav />
  
  <h2>GUITAR 1</h2>

  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse posuere
    sed augue ut hendrerit. Proin in enim feugiat velit efficitur tempus vel vitae
    elit. In efficitur odio non lorem maximus dapibus. Ut euismod dolor risus, et
    placerat urna bibendum in. Integer aliquet nulla nec dui laoreet elementum.
    Fusce non sollicitudin eros. Maecenas fermentum eleifend nunc vel condimentum.
    Pellentesque massa risus, mollis vitae eros vitae, varius dignissim tellus.
    Nunc sem mauris, tempus in vulputate eu, accumsan semper felis. In posuere
    purus id lectus pulvinar, sit amet blandit neque sagittis. Nunc eget mollis
    ipsum, at luctus arcu. Ut fringilla lectus mi, nec aliquet arcu cursus sed.
    Sed dui magna, dapibus eget eros eu, malesuada imperdiet odio. Etiam porta,
    felis sit amet consectetur aliquet, justo nisl mollis quam, ut faucibus sapien
    libero vitae risus. Aliquam dictum lorem sed viverra varius. Quisque sed lacus
    id lorem tempor finibus. In tristique sapien nisl, at accumsan neque lobortis
    aliquet. Interdum et malesuada fames ac ante ipsum primis in faucibus.
    Pellentesque imperdiet elit lorem, consequat convallis odio venenatis eget.
    Vivamus sed sapien sit amet odio tincidunt egestas. Aenean vel lorem
    hendrerit, feugiat nunc in, accumsan lectus. Maecenas volutpat faucibus velit
    eu tempus. Maecenas vitae placerat dolor. Praesent venenatis diam in mi cursus
    sagittis. Sed non bibendum dolor, in pellentesque mauris. Sed aliquam arcu sed
    mi iaculis, sit amet posuere metus suscipit. Curabitur sed rhoncus sem. Proin
    malesuada dolor a lectus tempus lobortis.
  </p>
  
  <style>
    /* LAYOUT */
    :global(Header) {
      grid-area: h;
    }
    :global(Nav) {
      grid-area: n;
    }
    :global(main) {
      grid-area: m;
    }
    :global(Footer) {
      grid-area: f;
    }
  
  
    :global(#svelte) {
      display: grid;
      grid:
        " h   h  " auto
        " n   .  " auto
        " n   m  " auto
        " f   f  " auto
        / 1fr 3fr;
    }
  </style>
  