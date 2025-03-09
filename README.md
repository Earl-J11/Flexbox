# Flexbox
#stle.css
:root {
    --clr-dark:#0f172a;
    --clr-light: #f1f5f9; 
    --clr-accent: #e11d48;
}

*,
*::before,
*::after {
    box-sizing: border-box;
}

body{
    margin: 0;
    padding: 0;
    line-height: 1.6;
    word-spacing: 1.4px;
    font-family: 'Roboto', sans-serif;
    color: var(--clr-light);
    display:  flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    width: 80%;
    height: 700px;
    margin: 0 auto;
    border: 10px solid var(--clr-dark);
}

.item {
    width: 150px;
    height: 150px;
    background-color: palevioletred;
    padding: 1em;
    font-weight: 700;
    color: var(--clr-light);
    text-align: center;
    border: 100px solid var(--clr-accent);
    border-radius: 10px;
}
  
.container {
    display: flex;
    /* flex-direction: column; */
   /* justify-content: space-evenly; */
    align-items: flex-start;
   /* flex-wrap: wrap; */
   /* align-content: flex-start; */
   /* gap: 1em; */
}

.item-1{
    order: 1;
}
.item-3{
    /*flex-grow: 1;*/
   /* flex-shrink: 0; */
   /* flex-basis: 0; */
   /* flex: 1; */
   /* align-self: baseline; */
    order: -1;
}

