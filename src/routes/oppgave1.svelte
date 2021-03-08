<svelte:head>
	<title>IT2 - Oppgave 1</title>
</svelte:head>

<h1>Eksamen høsten 2018</h1>

<p>Trening på problemløsning</p>
<p>Se oppgave1.svelte</p>

<img src="3h18.png" alt="Oppgave">


<script>
	// state
	let valgtFerie;
	let hytter = {
		Granstua: {
			sengeplasser: 4,
			standard: "Høy",
			badstue: true,
			ukepris: 12000,
			bilde: "granstua.jpg",
			jul: "utleid",
			vinter: "utleid",
			paske: "ledig"
		},
		Granbo: {
			sengeplasser: 6,
			standard: "Middels",
			badstue: false,
			ukepris: 15000,
			bilde: "granbo.jpg",
			jul: "ledig",
			vinter: "ledig",
			paske: "ledig"
		},
		Grantoppen: {
			sengeplasser: 8,
			standard: "Lav",
			badstue: false,
			ukepris: 16000,
			bilde: "grantoppen.jpg",
			jul: "utleid",
			vinter: "ledig",
			paske: "utleid"
		},
		Granhaug: {
			sengeplasser: 10,
			standard: "Høy",
			badstue: true,
			ukepris: 30000,
			bilde: "granhaug.jpg",
			jul: "utleid",
			vinter: "ledig",
			paske: "utleid"
		},
	}

	
	// Oppgave 2 og 3: Lag funksjonen som er beskrevet i pseudokode nedenfor

	/*
	funksjon settTilUtleid(hytte, ferie)
		Sett hytte til utleid den aktuelle ferien
	*/


</script>

<!-- Oppgave 1 -->

<!-- Select-element som lar bruker velge ferie -->

<!-- 
	Hvis bruker har valgt ferie: 
		For hytte i hytter:
			Hvis hytten er ledig den aktuelle ferien:
				Vis beskrivelse og bilde av hytten
				Vis en knapp som kaller funksjonen settTilUtleid(hytte, valgtFerie) ved klikk
-->

