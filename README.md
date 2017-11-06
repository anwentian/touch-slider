# touch-slider
A basic JavaScript slider plugin.
# How to use?
1. Call slider.js and slider.css

``` bash
<link rel="stylesheet" href="slider.css">
<script src="slider.js" ></script>

```
2. HTML structure
``` bash
<div  id="banner">            
  <div class="carousel" >
    <ul class="carousel-list">
      <li class="carousel-item" >Your stuff here.</li>
      <li class="carousel-item" >Your stuff here.</li>
      <li class="carousel-item" >Your stuff here.</li>                         
    </ul>
  </div>  
  <ol class="carousel-indicators">
    <li class="carousel-generic active"></li>
    <li class="carousel-generic"></li>
    <li class="carousel-generic"></li>           
  </ol>         
</div>
```
3. Init plugin
``` bash
<script>
    new Slider({banner: "banner", width: 320, height:180,autoSlide:true});
</script>

```
# Options
<table>
  <tr>
    <th>option</th>
    <th>default value</th>
    <th>description</th>
  </tr>
  <tr>
    <td>banner</td>
    <td>"banner"</td>
    <td>Slider container's id</td>
  </tr>
  <tr>
    <td>width</td>
    <td>320</td>
    <td>Set width</td>
  </tr>
  <tr>
    <td>height</td>
    <td>180</td>
    <td>Set height</td>
  </tr>
  <tr>
    <td>autoSlide</td>
    <td>true</td>
    <td>Enable/disable automatic slide</td>
  </tr>
  
</table>
