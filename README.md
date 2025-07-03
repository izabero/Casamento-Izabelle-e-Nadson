# Casamento-Izabelle-e-Nadson
/* Fonts import já no HTML */

/* Cores principais */
:root {
  --azul-serenite: #6b9ac4;
  --verde-oliva: #708238;
  --branco: #ffffff;
  --cinza-escuro: #333333;
}

* {
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  background-color: var(--azul-serenite);
  color: var(--branco);
  margin: 0;
  padding: 0 20px 40px;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 40px 0 20px;
  font-family: 'Playfair Display', serif;
}

header h1 {
  font-size: 3rem;
  margin-bottom: 10px;
  color: var(--verde-oliva);
}

.highlight {
  font-size: 1.3rem;
  font-style: italic;
  color: var(--branco);
}

section {
  background-color: rgba(0, 0, 0, 0.25);
  margin: 30px auto;
  max-width: 800px;
  padding: 20px 30px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.5);
}

h2 {
  color: var(--verde-oliva);
  margin-bottom: 15px;
  border-bottom: 2px solid var(--verde-oliva);
  padding-bottom: 6px;
}

.gallery .photos {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
  justify-content: center;
}

.gallery img {
  max-width: 250px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.3);
}

.gift-list ul {
  list-style-type: disc;
  padding-left: 20px;
  color: var(--branco);
}

form label {
  font-weight: bold;
  color: var(--verde-oliva);
}

input[type="text"],
input[type="email"] {
  width: 100%;
  padding: 8px 10px;
  margin-top: 6px;
  margin-bottom: 12px;
  border: none;
  border-radius: 5px;
  font-size: 1rem;
}

button {
  background-color: var(--verde-oliva);
  color: var(--branco);
  font-weight: bold;
  border: none;
  padding: 12px 25px;
  border-radius: 5px;
  cursor: pointer;
  font-size: 1.1rem;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #57692a;
}

footer {
  text-align: center;
  margin-top: 50px;
  color: var(--branco);
  font-size: 0.9rem;
}
