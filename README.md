# css_battlle_test
<div box></div>
<div eye1>
	<div eye2></div>
    <div eye3>
    	<div eye4></div>
    </div>
	<div eye5></div>
</div>

<style>
  *{
    background:#BAC7CE;
  }
  [box] {
    background:#475862;
    position:fixed;
    width:150;
    height:150;
    transform:rotate(45deg);
    top:-90;
    left:125;
    
  }
  [eye1] {
    position:relative;
    top:122;
    left:242;
    -webkit-box-reflect: left 100px

  }
  [eye2] {
    position:absolute;
    background:#000000;
    width:120;
    height:120;
    border-radius:60px 0 60px 0;
    transform:rotate(15deg)

  }
  [eye3] {
    position:relative;
    background:#5A6042;
    width:100;
    height:100;
    border-radius:50%;
    top:10;
    left:10;
    overflow:hidden;

  }
  [eye4] {
    position:absolute;
    background:#868A64;
    width:100;
    height:100;
    border-radius:50%;
    top:15;
    left:0;

  }
  [eye5] {
position:absolute;
    background:#4E2B24;
    width:30;
    height:30;
    border-radius:50%;
    top:40;
    left:40;
    border:5px solid black;

  }

  
  
</style>
