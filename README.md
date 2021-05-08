# ESN-Awards
<h2>ESN Awards 2021</h2>
 <meta name="description"
      content="The ESN Awards are given for extraordinary achievements in ESN every year in 14 categories"
    />
<h3>Site made using Angular 9<br>
<a id="myBtn" href="https://awards.esn.org"><a></h3>
 <style>
  #myBtn {
  color:#2e3192;
  }
  #myBtn:hover {
  color:grey;
  animation: myBtnslow $btnspeed ease-in-out infinite;

  size: 90%;}


#myBtn{
  animation: myBtnup $btnspeed ease-in-out infinite;
}
#myBtn:after {
  transform: rotate(90deg)
}

@keyframes myBtnup {
  0% { 
      opacity: 1;
      right: 0.6%;

      top: 84%;
      transform: rotate(90deg) translate(10px);
  }
  61% {
      opacity: 0.02;
   right: 0.6%;

      transform: rotate(90deg)translate(10px);
  }

  81% {
    opacity: 0.3;
  right:0.6%;
 // right:5%;

    transform: rotate(90deg)translate(10px);
}
  100% { 
      opacity: 1;
      right: 0.6%;
      transform: rotate(90deg)translate(10px);
  }
}
  </style>
