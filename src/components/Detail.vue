<template>
	<div class="detail">
		<div class="detail-inner">

			<div class="detail-ikona">
				<!--
					V obrázku níže musíš dynamicky měnit zdroj obrázku.
					Je-li světlo zapnuté, budeš zobrazovat obrázek '/images/light-on.svg'
					Je-li světlo vypnuté, budeš zobrazovat obrázek '/images/light-off.svg'
				-->
				<img src="/images/light-on.svg">
			</div>

			<h2 class="detail-nazev">
				<!--
					Zde místo textu "Podkroví" zobrazuj název světla
					jehož detail zobrazuješ.
				-->
				Podkroví
			</h2>

			<div class="detail-buttons">
				<!--
					Níže jsou dvě tlačítka.
					Kliknutím na Zapnuto světlo zapneš, kliknutím na Vypnuto zase vypneš.
					Tj. na obě tlačítka musíš přidat událost click a něco v ní dělat.

					Podle toho, zda je světlo zapnuté nebo vypnuté, tak na příslušné
					tlačítko dynamicky přidej třídu "aktivni".

					Tj. například, když bude světlo zapnuté, mělo by výsledné HTML vypadat takto:
					<button class="aktivni">Zapnuto</button>
					<button>Vypnuto</button>
				-->
				<button>Zapnuto</button>
				<button>Vypnuto</button>
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