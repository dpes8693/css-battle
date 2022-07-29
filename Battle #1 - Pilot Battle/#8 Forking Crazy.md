# 叉子

`:nth-child()`

```html
<div class="container">
  	<div class="sticks">
  		<div></div>
      	<div></div>
        <div></div>
      	<div></div>
        <div></div>
      	<div></div>
		<div></div>      
  	</div>
	<div class="bassic"></div>
  	<div class="flag"></div>
</div>

<style>
  body{
    margin:0;
    background:#6592CF;
  }
  .container{
    display:flex;
    align-items:center;
    flex-direction:column;
    justify-content:center;
    height:100%;
  }
  .sticks{
    position: absolute;
    display:flex;
  }
  .sticks div{
    width:20px;
    height:110px;
    border-radius:10px;
    margin: 0  0  90px 0
  }
  .sticks div:nth-child(even){
    background:#6592CF;
  }
  .sticks div:nth-child(odd){
    background:#060F55;
  }
  .bassic {
    width: 140px;
    height: 190px;
    margin-top:10px;
    background: #060F55;
    border-radius:80px;
  }
  .flag{
    position:absolute;
    bottom:0;
    height:60px;
    width:20px;
    background: #060F55;
    margin:  0 auto;
  }
</style>
```