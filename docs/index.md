<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- displays site properly based on user's device -->

    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="./images/favicon-32x32.png"
    />

    <title>Frontend Mentor | NFT preview card component</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Outfit">
    <link
      rel="stylesheet"
      href="https://fonts.google.com/specimen/Outfit"
    />
    <link rel="stylesheet" href="style.css" />
    <style>
      * {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  top: 0;
  font-size: 100%;
  font-style: inherit;
  font-family: "Outfit";
}
.container {
  display: flex;
  justify-content: center;
  place-items: center;
  background-color: hsl(217, 54%, 11%);
}
.card {
  max-width: 300px;
  margin: 40px;
  padding: 20px;
  border-radius: 1rem 1rem;
  background-color: hsl(216, 50%, 16%);
}
.hero {
  padding-bottom: 1rem;
}
/* .image-box:hover{
    width: 260px;
  height: 260px;
    background-color: hsl(178, 100%, 50%);
    color: hsla(178, 100%, 50%, 0.7);
} */
.hero-img{
    width: auto;
  height: 260px;
  border-radius: 10px;
}
.image-box {
  width: auto;
  height: 260px;
  border-radius: 10px;
}
h2{
    padding-bottom: 1rem;
    font-family: "Outfit";
    font-weight: 500;
}
h2,
.name {
  color: hsl(0, 0%, 100%);
}
h2:hover{
    color: hsl(178, 100%, 50%);
}
.name:hover{
    color: hsl(178, 100%, 50%);
}
.details > p {
    font-size: 15px;
    font-weight: 100;
    padding-bottom: 1rem;
  color: hsl(215, 51%, 70%);
}
.icon{
    font-size: 3px;
    /* height: auto;
    width: 12px; */
    padding: 0;
}
.eth-clock{
    padding-bottom: 1rem;
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: space-between;
}
.ethereum {
    color: hsl(178, 100%, 50%);
    display: flex;
    justify-content: center;
}
.padded{
    padding-left: 5px;
    font-size: 15px;
    font-weight: 200;
}
.line {
  color: hsl(215, 32%, 27%);
}
.countdown {
  color: hsl(215, 51%, 70%);
  display: flex;
  justify-content: center;
}
.creator {
  display: flex;
  justify-content: left;
  padding: 10px;
  align-items: center;
}
.avatar {
  width: 25px;
  height: auto;
  background-color: white;
  padding: 0.75px;
  border-radius: 50%;
  margin-right: 4px;
}
.attribution {
  font-size: 11px;
  text-align: center;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}
@media only screen and (max-width: 375px) {
   .card{
       width: 300px;
       max-width: 375px;
    } 
    .container{
        max-width: 375px;
    }
}
    </style>
  </head>
  <body>
    <main class="container">
      <div class="card">
        <div class="hero">
            <div class="image-box">
                <img
                  src="images/image-equilibrium.jpg"
                  alt="Hero Image"
                  class="hero-img"
                />
                
            </div>
          </div>
        <div class="details">
          <h2>Equilibrium #3429</h2>
          <p>Our Equilibrium collection promotes balance and calm.</p>
        </div>
        <div class="eth-clock">
          <div class="ethereum">
            <img
              src="images/icon-ethereum.svg"
              alt="Ethereum icon"
              class="icon"
            />
            <span class="padded"> 0.041 ETH </span>
          </div>
          <div class="countdown">
            <img src="images/icon-clock.svg" alt="Clock icon" class="icon" />
            <span class="padded"> 3 days left </span>
          </div>
        </div>
        <hr class="divider" />
        <div class="creator">
          <img src="images/image-avatar.png" alt="Avatar" class="avatar" />
          <p>

            <span style="color: hsl(215, 51%, 70%)"> Creation of </span>
            <span class="name">Jules Wyvern</span>
          </p>
        </div>
        <div class="attribution">
          Challenge by
          <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
            >Frontend Mentor</a
          >. Coded by <a href="#">Rahmlad</a>.
        </div>
      </div>
    </main>
  </body>
</html>

