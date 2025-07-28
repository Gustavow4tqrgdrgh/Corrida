function setup() {
  createCanvas(400, 400);
}
let xJogador1 = 0
let xJogador2 = 0

function draw() {
  background(220);
textSize(40);
  text("Jogador 1", xJogador1, 100);
  text("Jogador 2",xJogador2, 300);
  rect(350,0,10,400);
  xJogador1 = xJogador1 + random (5);
  xJogador2 = xJogador2 + random (5);
}
