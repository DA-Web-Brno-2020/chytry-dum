<template>
  <div id="app">

    <header>
      <h1>Chytrý dům</h1>
    </header>

    <main>

      <!--
        Sem vložit komponentu <seznam /> se seznamem všech světel.
        Komponenta musí mít prop, do kterého předáš seznam světel z data.
        A musí reagovat na událost zevnitř komponenty, když se klikne
        na jedno ze světel a má se zobrazit jeho detail.
        Nezapomeň komponentu dole nejprve naimportovat a zaregistrovat pro použití.
      -->


      <!--
        Sem vložit komponentu <detail /> s ovládáním jednoho světla.
        Komponenta musí mít jeden prop, do kterého předáš objekt
        světla, jehož detail se má zobrazit.
        Nezapomeň komponentu dole nejprve naimportovat a zaregistrovat pro použití.
      -->

    </main>

  </div>
</template>



<script>

// Tady nezapomeň naimportovat komponenty ze složky components

export default {
  components: {
    // Zde nezapomeň zaregistrovat naimportované komponenty
    detail: Detail
  },

  data: function() {
    return {
      // v poli svetla máš připravený seznam světel
      // každé světlo má název a true/false hodnotu, zda je zapnuté nebo ne
      svetla: [
        {
          nazev: 'Obývací pokoj',
          zapnuto: false
        },
        {
          nazev: 'Ložnice',
          zapnuto: true
        },
        {
          nazev: 'Dětský pokoj',
          zapnuto: false
        },
        {
          nazev: 'Koupelna',
          zapnuto: false
        },
        {
          nazev: 'Kuchyně',
          zapnuto: true
        },
        {
          nazev: 'Chodba',
          zapnuto: false
        },
        {
          nazev: 'Záchůdek',
          zapnuto: false
        }
      ]
    }
  }

}
</script>




<style>

</style>
