# Styleguide

Hier is onze styleguide uit figma.

### Colors
Wij hebben 6 kleuren vastgesteld als huisstijlkleuren. Deze komen het meest voor in de website. Aangezien alleen de kleurnaam al veel zegt over wat voor Custom Properties het zijn vonden we het duidelijk genoeg om alleen de naam van de kleur te gebruiken in plaats van bijvoorbeeld, `--main-color-white: ...`. De achtergrond van de website wordt wit en de elementen worden afgewisseld met verschillende kleuren van de kleurenschema.

In de code hebben we dat in de body als volgende toegepast:

    /* background color */
      --background-color: #fff;


    /* section colors */
      --section-color-1: #fff;
      --section-color-2: #F9EAC3;
      --section-color-3: #FBC97E;
      --section-color-4: #F26E21;
      --section-color-5: #4E7141;
      --section-color-6: #5F2300;
      --section-color-7: #000;


    /* text colors */
      --text-color-1: #fff;
      --text-color-2: #F9EAC3;
      --text-color-3: #F26E21;
      --text-color-4: #4E7141;
      --text-color-5: #5F2300;
      --text-color-6: #000;

![image](https://github.com/user-attachments/assets/c9c5d877-4306-4237-b90a-61cd3aaf2f42)

***
### Typography
We houden 1 lettertype aan in de gehele website om de rust te bewaren, we hebben wel een backup lettertype voor als de eerste niet wilt werken in alle browsers.
Daarnaast hebben we 4 opties voor de grootte van een tekst. Omdat we het hier belangrijk vonden dat het duidelijk is waar het over gaat, hebben we de Custom Properties namen zo omschrijvend mogenlijk gemaakt. 

Small: paragraph/<a>/links
medium: h3
large: h2
x-large: h1
      
    /*font*/
      --font-text: "Poppins", sans-serif;
  
      --font-size-small: 1rem;
      --font-size-medium: 1.2rem;
      --font-size-large: 4.5rem;
      --font-size-X-large: 7rem;

![image](https://github.com/user-attachments/assets/c004dace-962e-4238-95f4-c8fb53cc0f56)


***
### Forms 
Onder het kopje Forms kan je zien hoe we de afgeronde hoekjes kunnen toepassen in de code. Om het overzicht te behouden hebben we gelijk in de vormen gezet welke Custom Properties welke vormen aanspreken. De radius-card wordt toegepast op de knoppen van de website en de radius-big-card wordt toegepast op de objecten. De shadow wordt toegepast op de buttons.

    /*forms and more*/
      --radius-card: 1em;
      --radius-big-card: 2em;
      --radius-round: 100%;
      --shadow: hsl(240, 5%, 41%, 0.2) 0px 7px 29px 0px;

![image](https://github.com/user-attachments/assets/8707bd34-4bd9-4740-bb04-af0a58b452da)


## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

