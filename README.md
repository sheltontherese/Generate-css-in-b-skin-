# Generate-css-in-b-skin-
Generate css in &lt;b:skin>
.flat-icon-button {

  background:transparent;

  border:0;

  outline:none;

  padding:8px;

  cursor:pointer;

  box-sizing:content-box;

  display:inline-block;

  line-height:0;

}

.flat-icon-button,.flat-icon-button .splash-wrapper {

  border-radius:50%;

}

.flat-icon-button .splash.animate {

  -webkit-animation-duration:0.3s;

  animation-duration:0.3s;

}

.flat-button {

  cursor:pointer;

  border-radius:2px;

  padding:8px;

}

.ripple {

  position:relative;

}

.ripple > * {

  z-index:1;

}

.splash-wrapper {

  bottom:0;

  left:0;

  overflow:hidden;

  pointer-events:none;

  position:absolute;

  right:0;

  top:0;

  z-index:0;

}

.splash {

  background:#aaaaaa;

  border-radius:100%;

  display:block;

  opacity:.9;

  position:absolute;

  -webkit-transform:scale(0);

  -ms-transform:scale(0);

  transform:scale(0);

}

.splash.animate {

  -webkit-animation:ripple-effect 0.4s linear;

  animation:ripple-effect 0.4s linear;

}

@-webkit-keyframes ripple-effect {

  100% {

    opacity:0;

    -webkit-transform:scale(2.5);

    transform:scale(2.5);

  }

}

@keyframes ripple-effect {

  100% {

    opacity:0;

    -webkit-transform:scale(2.5);

    transform:scale(2.5);

  }

}
