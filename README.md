# 双二极管钳位电路的原理  

如图，水平的线是受保护的节点。当该点电压超过Vcc+0.7V时，上面的二极管导通；而当该点电压小于-0.7V时，下面的二极管导通。因此，该点电压被钳制在Vcc+0.7V—— -0.7V之间。

  <div align="center"> 
 ![啦啦啦啦啦](\pic\DualDiodeClamp.jpg) 
  
  </div> 

双二极管钳位电路的原理
对于正常的二极管，其正向电阻约为几千欧，反向电阻为几百千欧 (一般应大于 200 千欧），而场


  ![啦啦啦啦啦](https://github.com/lyh523329053/Clamp-Circuit/raw/master/pic/DualDiodeClamp.jpg) 
  

MOS管一般内阻都在10M——1000G欧，所以二极管的内阻远小于场效应管的电阻。如果电压过高，高于Vcc+Vd（二极管导通压降），上面的二极管导通，输出电压钳位于Vcc+Vd；如果电压过低，低于0-Vd（二极管导通压降），下面的二极管导通，输出电压钳位于-Vd。

<center>
<img src="https://github.com/lyh523329053/Clamp-Circuit/raw/master/pic/DualDiodeClamp.jpg" width="50%">

<center>
<img src="https://img-blog.csdn.net/20180727154819408?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MTkyOTUyNA==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" width="50%">
