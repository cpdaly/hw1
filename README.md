# hw1
mondrian exercise:

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(240);

	noStroke()
	
	fill(0)
	strokeWeight(2)
	ellipse(60, 60, 55, 55);
	line(80, 250, 80, 250);
	
	stroke(10)
	line(random(25,200), 60, 300, 300)
	line(300, 300, 400, 4)
	
	fill(random(25,200), 204, 0)
	triangle(125, 80, 80, 8, 150, 150)
	random(80, 400)
	triangle(200, 200, 400, 250, 300, 300)
	
	fill(255, 24, 5)
	rect(12, 120, 80, 120);
	
	fill(25, 150, 5)
	rect(250, 350, 250, 350)
	let lineX= 100
	lineX = random(10, 90);
	line(lineX, 120, lineX, height);
	
	lineY = 300
	lineY = random(100,300);
	line(0, lineY, width, lineY)
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
				 
				 }
         
        
        
        
