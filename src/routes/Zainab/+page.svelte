<main>
	<h1>Our team of experts</h1>
	<p>
		Wij zijn enthousiaste studenten die de opleiding FDND (Frontend Design & Development) volgen aan
		de HvA (Hogeschool van Amsterdam)
	</p>
	<article>
		<img src="/Squad2C-Zainab.JPG" alt="Mugshot Zainab" width="100" height="100" />
		<p>F</p>
		<img src="/Squad2C-Akiko.JPG" alt="Mugshot Zainab" width="100" height="100" />
		<p>D</p>
		<img src="/Squad2C-Eva.JPG" alt="Mugshot Zainab" width="100" height="100" />
		<p>D</p>
		<img src="/Squad2C-Lesley.JPG" alt="Mugshot Zainab" width="100" height="100" />
		<p>N</p>
		<img src="/Squad2D-Rukiya.JPG" alt="Mugshot Zainab" width="100" height="100" />
	</article>
</main>

<style>
	main {
		min-height: 100vh;
		background-color: var(--darkpurple);
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		display: flex;
		flex-direction: column;
		justify-content: flex-start;
		align-items: center;
	}

	h1,
	p {
		color: var(--turquoise);
		padding: 1em;
		margin: 0;
		line-height: 1.4;
	}

	article {
		display: grid;
		grid-template-columns: repeat(3, 1fr);
		grid-template-rows: repeat(3, auto);
		gap: 10px;
		padding-top: 2em;
	}

	article img {
		height: auto;
		object-fit: cover;
	}

	article p {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
		padding: 10px;
		text-align: center;
	}
</style>
