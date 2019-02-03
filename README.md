# Tarea-1
Código de actividades realizados en clases


//Codigo de señal alto
function setup() {
  createCanvas(400, 400);
}
function draw() {
	background(220);
	strokeWeight(40);
	stroke(200,0,0);
	ellipse(200,200,300,300);
	line(100,100,300,300);
}

//Código de 3 líneas
variable1 = 0;
variable2 = 100;
variable3 = 200;
variable4 = 255;
function setup() {
  createCanvas(400, 400);
fill(variable4);
rect(variable1,variable1,variable3,variable3);
line(variable2,variable1,variable2,variable2);
line(variable2,variable2,variable1,variable3);
line(variable2,variable2,variable3,variable3);

function draw() {
  background(220);
}
}

//Código de bandera
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
	fill(1000,0,0)
	rect(0,0,133,400);
	fill(0,1000,0)
	rect(133,0,133,400);
	fill(0,0,1000)
	rect(266,0,133,400);
}
