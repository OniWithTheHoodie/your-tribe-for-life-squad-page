<section>
    <h1> Our team experts</h1>
    <p>
        We are a group of students studying FDND (Front-end Design & Development)
        at the HvA (University of Applied Sciences in Amsterdam). 
    </p>  
</section>
   <section class="center">
	<section class="wrapper">
        <article>
            <a href="Akiko">
                <img alt="persoon mugshot" src="./mugshots/Squad2C-Akiko.jpg" />
            </a>
        </article>
        <article>
            <a href="Lesley">
                <img alt="persoon mugshot" src="./mugshots/Squad2C-Lesley.jpg" />
            </a>
        </article>
        <article>
            <a href="Rukiya">
                <img alt="persoon mugshot" src="./mugshots/Squad2D-Rukiya.jpg" />
            </a>
        </article>
        <article>
            <a href="Zainab">
                <img alt="persoon mugshot" src="./mugshots/Squad2C-Zainab.jpg" />
            </a>
        </article>
        <article>
            <a href="Eva">
                <img alt="persoon mugshot" src="./mugshots/Squad2C-Eva.jpg" />
            </a>
        </article>
    </section>
</section>
<style>
    a {
        text-decoration: none;
    }
    img {
        height: 10rem;
        object-fit: cover;
    }
    .wrapper {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(3, 1fr);
        gap: 0;
        max-width: min-content;
    }

    .center {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    article {
        box-sizing: border-box;
        /* margin:0.5rem; */
        max-width: min-content;
        margin:0;
        border-radius: 5rem;
    }
    article:nth-child(1) {
    grid-column: 1 / 2; 
}

article:nth-child(2) {
    grid-column: 3 / 4; 
}

article:nth-child(3) {
    grid-column: 2 / 3; 
    grid-row:2
}

article:nth-child(4) {
    grid-column: 1 / 2; 
    grid-row: 3;
}

article:nth-child(5) {
    grid-column:3 / 4;
    grid-row: 3;
}
/* @media (){

} */
</style>