void setup() {
  size(640, 360, P3D);
  noFill();
}

void draw() {
  lights();
  background(0);
  
  
  camera(mouseX, mouseY, 220.0, 0.0, 0.0, 0.0, 0.0, 1.0, 0.0); 
  
  stroke(250);
  box(90);
}
