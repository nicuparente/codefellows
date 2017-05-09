# LJ Code 301 - Day 1

Today we went over "Responsive Web Design" which how most modern sites are created. We also covered "SMACCS" that are a set of guidelines that helps organize CSS Rules.

The code demo we covered today shows how media queries work to dynamically detect the width of the screen and apply css rules that modify what is displayed on the screen.
### HTML
```
<h1>Bip Bop Boop</h1>
<ul>
  <li>NUM 1</li>
  <li>NUM 2</li>
  <li>NUM 3</li>
</ul>

```

### CSS
```body{

  background-color: grey;
}

h1{
  background-color: yellow;
  text-align: center;
}


@media screen and (min-width:800px){
  h1{
    background-color:red;
    font-family: Helvetica;
  }

  li{
    display:inline;
  }
}
```
