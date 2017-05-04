# Part2Exercise
void setup()
{
  size(480,480);
  background(0,255);
  //body
  fill(148,0,211);
  rect(160,160,160,160);
  //ears
  fill(148,0,211);
  triangle(200,100,240,160,160,160);
  triangle(280,100,320,160,240,160);
  //ears layer
  fill(255,200,200);
  triangle(200,130,220,160,180,160);
  triangle(280,130,300,160,260,160);
  //eyes
  fill(255);
  ellipse(200,220,40,80);
  ellipse(280,220,40,80);
  //mouth
  fill(0);
  ellipse(240,285,100,50); 
}
