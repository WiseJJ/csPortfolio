# Jonny's ACS Projects

* WebPage [here](https://wisejj.github.io/lightning2/)
* Lightning [here](https://wisejj.github.io/lightning2/)
* Dice (Bug with array lists) [here](https://wisejj.github.io/dice3/)
* Chemotaxis (Bug with array lists) [here](https://wisejj.github.io/chemotaxis4/)
* StarField (Bug with array lists) [here](https://wisejj.github.io/starfield5/)
```Java
 public void lightning1(){
    stroke(255,255,0);
  while(endX<=900){
  endX = startX + (int)(Math.random()*9);
  endY = startY + (int)((Math.random()*60)-30);
  line(startX, startY, endX, endY);
  startX= endX;
  startY = endY;
  }
```
