# Process---1

/* 
함수를 호출한다. function call
 주석 처리. 프로세싱이 무시하고 건너뛰게 됩니다.
 */

// 창의 크기 설정
size( 300, 200 );

// red, green, blue
background( 255, 0, 0 );

// point(x, y)
point(150, 100);
point(151, 100);
point(152, 100);
point(153, 100);
point(154, 100);

// line(x1, y1, x2, y2);
line(300, 200, 0, 0);
line(300, 0, 0, 200);

// rect(x, y, w, h);
rectMode(CENTER);
strokeWeight(4);
stroke(0, 0, 255);
rect(150, 100, 50, 50);

// ellipse(x, y, w, h);
// ellipseMode(CENTER);
strokeWeight( 5 );
stroke(0);
noFill();
ellipse(150, 100, 120, 120);

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

void setup(){
  size(600, 300);
  background(255,0,0);
  fill(0);
  textSize(50);
  text("Hello",200,200);

  PFont font = createFont("NanumGothic", 3)
  textFont(font);

  text("Hello",200,300);
}

void draw(){

}

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

void setup(){
  size(600, 300);
  background(255);
  PImage img = loadImage("apple.jpg");
  image(img, 20,50, 200, 100);
}

void draw(){

}
