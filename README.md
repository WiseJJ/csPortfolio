# Jonny's ACS Projects

* _WebPage_ [here](https://wisejj.github.io/VacationPage/chinaPage/)
* _Lightning_ [here](https://wisejj.github.io/lightning2/)
* _Dice_ (Bug with array lists) [here](https://wisejj.github.io/dice3/)
* _Chemotaxis_ (Bug with array lists) [here](https://wisejj.github.io/chemotaxis4/)
*_StarField_ (Bug with array lists) [here](https://wisejj.github.io/starfield5/)
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
