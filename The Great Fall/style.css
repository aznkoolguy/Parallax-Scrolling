@import "compass/css3";

@import "compass/css3";

/* custom styles */
body{
  font-family: open-sans, sans-serif;
  overflow-x: hidden;
  color: white;
  background: black;
}

h2, h3{
  position: relative;
  text-transform: uppercase;
  font-family: open-sans-condensed, sans-serif;
  font-size: 3rem;
  font-weight: 100;
  letter-spacing: .1em;
  margin: 0 0 .5rem 0;
  text-shadow: 0px 5px 10px rgba(0, 0, 0, 0.5);
}

h3{
  font-size: 1.5rem;
}

a{
  text-decoration: none;
  font-size: 1.5rem;
  font-weight: 500;
  
  &:hover{
    color: white;
  };
}

ol{
  font-size: 3rem;
  text-transform: uppercase;
  list-style-type: decimal;
}

li{
  line-height: 1.5;
}

.slide{
  position: relative;
  display: flex;
  display: -webkit-flex;
  -webkit-flex-direction: column;
  -webkit-align-items: center;
  -webkit-justify-content: center;
  -moz-flex-direction: column;
  -moz-align-items: center;
  -moz-justify-content: center;
  width: 100vw;
  height: 100vh;
}

figure{
  position: relative;
  padding: 50px 80px;
  width: 400px;
  opacity: 0;
  -webkit-clip-path: polygon(180.758px 85.892px, 180.128px 88.285px, 181.837px 90.958px, 185.885px 90.958px, 189.752px 90.536px, 191.281px 91.381px, 195.329px 90.677px, 195.329px 87.651px, 196.138px 85.462px, 192.001px 83.922px, 188.898px 85.462px, 186.874px 83.922px, 183.366px 85.462px);
  @include transition(-webkit-clip-path 1s, opacity .2s);
  
  canvas{
    position: absolute;
    top: 0;
    @include transform(scale(0));
    @include transition(-webkit-transform .5s);
  }
  
  &.in{
    opacity: 1;
    -webkit-clip-path: polygon(-105.931px 17.51px, -131.035px 112.902px, -62.898px 219.517px, 98.479px 219.517px, 252.684px 202.683px, 313.649px 236.351px, 475.026px 208.295px, 475.026px 87.651px, 507.301px 0.356px, 342.338px -61.049px, 218.616px 0.356px, 137.927px -61.049px, -1.933px 0.356px); 
    
    canvas{
      @include transform(scale(1));
    }
    
    figcaption{
      opacity: 1;
      -webkit-clip-path: polygon(-105.931px 17.51px, -131.035px 112.902px, -62.898px 219.517px, 98.479px 219.517px, 252.684px 202.683px, 313.649px 236.351px, 475.026px 208.295px, 475.026px 87.651px, 507.301px 0.356px, 342.338px -61.049px, 218.616px 0.356px, 137.927px -61.049px, -1.933px 0.356px); 
    }
  }
  
  &.right{
    float: right;
    
    canvas{
      left: 0;
    }
    
    figcaption{
      border-left: 2px solid white;
      text-align: left;
    }
  }
  
  &.left{
    float: left;
    
    canvas{
      right: 0;
    }
    
    figcaption{
      border-right: 2px solid white;
      text-align: right;
    }
  }
}

figcaption{
  position: relative;
  padding: 0 10px;
  z-index: 1;
  text-transform: uppercase;
  font-family: open-sans-condensed, sans-serif;
  font-size: 1.3rem;
  opacity: 0;
  -webkit-clip-path: polygon(180.758px 85.892px, 180.128px 88.285px, 181.837px 90.958px, 185.885px 90.958px, 189.752px 90.536px, 191.281px 91.381px, 195.329px 90.677px, 195.329px 87.651px, 196.138px 85.462px, 192.001px 83.922px, 188.898px 85.462px, 186.874px 83.922px, 183.366px 85.462px);
  @include transition(-webkit-clip-path 1s, opacity 1s);
  
  p{
    line-height: 1.5; 
  }
}

.section{
  width: 100vw;
  height: 100vh;
}

.slide{
  -webkit-box-sizing: border-box;
  padding: 1rem;
}

#title{
  margin: auto;
}

#scroll-btn{
  position: fixed;
  bottom: 0;
  left: 50%;
  margin-left: -54px;
  opacity: 1;
  @include transition(opacity .2s);
  @include transform(translateZ(0));
  
  &.out{
    opacity: 0;
  }
}

#ground{
  top: 0;
  left: 0;
   position: fixed;
  width: 100%;
  height: 100%;
}

#deck{
  z-index: 2;
}
