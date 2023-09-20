# js-escrevenome

function setup() {
  createCanvas(600, 600);
  background("black");
}

function draw() {
  stroke("#2196F3");
  fill("#E91E63")
  
  if(mouseIsPressed){
    rect(mouseX, mouseY, 20, 35);
  }
}
