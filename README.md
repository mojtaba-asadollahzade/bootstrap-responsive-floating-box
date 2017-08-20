# Responsive Bootstrap Floating Boxes
This is a plugin to make boxes with diffrent heights float normally on screen with responsive behavior
![screen shot of persian calendar](https://github.com/mojtaba-asadollahzade/bootstrap-responsive-floating-box/blob/master/demo/screen_shot.png)

### Usage

Include the **bootstrap-floating-box.min.js** files into your 
page.

After that you can have multiple divs within a div with diffrent heights :

```html
<div class="row item-container">
      <div class="col-xs-12 item" style="height: 250px;background: #3498db;"></div>
      <div class="col-xs-12 item" style="height: 350px;background: #e74c3c;"></div>
      <div class="col-xs-12 item" style="height: 200px;background: #27ae60;"></div>
      <div class="col-xs-12 item" style="height: 340px;background: #2ecc71;"></div>
      <div class="col-xs-12 item" style="height: 230px;background: #d35400;"></div>
      <div class="col-xs-12 item" style="height: 300px;background: #2c3e50;"></div>
      <div class="col-xs-12 item" style="height: 320px;background: #f39c12;"></div>
      <div class="col-xs-12 item" style="height: 280px;background: #16a085;"></div>
      <div class="col-xs-12 item" style="height: 175px;background: #1abc9c;"></div>
  </div>
```

Now use the code below to float the boxes in a responsive way : 

```html
<script type="text/javascript">
  $('.item-container').FloatingBox({
      target : '.item',
      xs : 1,
      sm : 3 ,
      md : 4 ,
      lg : 4 ,
      xlg : 12,
      margin: 10
  });
</script>
```
The **target** is the items to float,The **xs**,**sm**,**md**,**lg**,**xlg** parameters are the number of columns corresponding to bootstrap **col-xs**,**col-sm**,**col-md**,**col-lg** and **col-xlg** columns.

After that you are good to go, you can also follow the demo included to get started.

At the end I've to thank :
* **[Maciej Gurban](https://github.com/maciej-gurban)** - *Responsive Bootstrap Toolkit*.
