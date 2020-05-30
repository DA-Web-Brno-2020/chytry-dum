<template>
	<div class="svetla">
		<!--
			Prvek <div class="svetlo"> pod tímto komentářem (a všechno, co obsahuje)
			musíš opakovat pro každé jednotlivé světlo.

			Tj. přidáš na ten <div> direktivu v-for, ve které budeš postupně procházet
			seznam všech světel a vypisovat jejich data. Nezapomeň si ve v-for získat
			i index prvku v poli. Bude se ti hodit, až budeš muset rodičovské komponentě
			sdělit, na kolikáte světlo v poli se kliklo.

			Určitě tedy musíš na <div class="svetlo"> přidat zároveň událost click,
			která bude volat funkci. Tato funkce vytvoří vlastní událost a pomocí ní pošle do
			rodičovské komponenty index prvku, na který se kliklo (= jehož detail se má zobrazit).
			Ve funkci se tedy bude volat this.$emit('nazev-udalosti', posilanaData)
		-->
		<div class="svetlo">

			<div class="svetlo-ikona">
				<!--
					V obrázku níže musíš dynamicky měnit zdroj obrázku.
					Je-li světlo zapnuté, budeš zobrazovat obrázek '/images/light-on.svg'
					Je-li světlo vypnuté, budeš zobrazovat obrázek '/images/light-off.svg'
				-->
				<img src="/images/light-off.svg">
			</div>


			<div class="svetlo-nazev">
				<!--
					Zde místo textu "Podkroví" zobrazuj název světla.
				-->
				Podkroví
			</div>

		</div>

	</div>
</template>



<script>
export default {

}
</script>

<style>

</style>