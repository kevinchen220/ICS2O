float cx=100;
float cy=250;
float cspeed=4;

float ssize=300;
float stroke=50;

float lx=751;
float ly=250;

PImage photo;
void setup() {
  size(750, 500);
  //photo=loadImage("captainamerica.png");
}
void draw() {
  background(110);
  //image(photo, 100, 200);
  fill(240, 0, 0);
  ellipse(cx, cy, 150, 40);
  fill(255);
  ellipse(cx, cy-5, 125, 30);
  cx+=cspeed;
  if (cx>=375) {
    cspeed=0;
  }
  //if (cx+75>=width) {
  //  cspeed=-4;
  //}
  //if (cx-75<=0) {
  //  cspeed=4;
  //}
  if (cx>=375) {
    if (ssize>0) {
      ssize+=20;
      //if (ssize<=500) {
      //  fill(0,0, ssize*0.25);
      //  stroke(0,0, ssize*0.25);
      //} else if (ssize<=700) {
      //  fill(0,0, ssize*0.25);
      //  stroke(0,0, ssize*0.25);
      //} else {
      //  fill(255);
      //  stroke(255);
      //}
    }
    fill((ssize-300)/30*9.4+73.26, (ssize-300)/30*4.686+183.27, 255);
    stroke((ssize-300)/30*9.4+73.26, (ssize-300)/30*4.686+183.27, 255);
    strokeWeight(20);
    line(-10, 250, lx, ly);
    noStroke();
    ellipse(375, 250, ssize, ssize);
  }
  if (ssize>=1000) {
    ssize=0;
    lx=-20;
  }
}
