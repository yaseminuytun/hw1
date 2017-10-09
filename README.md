# hw1
void setup() {
  // Set Window size
  size(450,450);
}


 void draw() {
   //background(#34C0C6);
   //write text
   fill(#64C634);
   text("hello I'm back", 10, 10);
   
   //draw ellipse with mouse coord.
   //strokeWeight(4);
   //stroke(#C6B134);
   fill(#767463);
   ellipse(mouseX,mouseY,30,30);
   
   //Draw rectangle
   noStroke();
   fill(#764566);
   rotate(radians(30));
   rect(80,80,10,60);
   
   
 }
 
