# csPortfolio

* WebPage [here](https://wisejj.github.io/lightning2/)
* Lightning [here](https://wisejj.github.io/lightning2/)
* Dice (has bug only works in processing) [here](https://wisejj.github.io/dice3/)
* Chemotaxis [here](https://wisejj.github.io/chemotaxis4/)
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
