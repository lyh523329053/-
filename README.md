# 双二极管钳位电路的原理  

>- 当Vin电压超过VrefH + 0.7V时，上面的二极管导通；而当该点电压小于VrefL - 0.7V时，下面的二极管导通。因此，该点电压被钳制在VrefH + 0.7V —— VrefL - 0.7V之间。


>- 双二极管钳位电路的原理
对于正常的二极管，其正向电阻约为几千欧，反向电阻为几百千欧 (一般应大于 200 千欧），而场MOS管一般内阻都在10M——1000G欧，所以二极管的内阻远小于场效应管的电阻。如果电压过高，高于VrefH + 0.7V（二极管导通压降），上面的二极管导通，输出电压钳位于VrefH + 0.7V；如果电压过低，低于VrefL - 0.7V（二极管导通压降），下面的二极管导通，输出电压钳位于VrefL - 0.7V。
 
<center> 
<img src="https://github.com/lyh523329053/Clamp-Circuit/raw/master/pic/DualDiodeClamp.png">
</center>

<div align=center><img src="https://github.com/lyh523329053/Clamp-Circuit/raw/master/pic/DualDiodeClamp.png" style=' width:300px;height:100 px'/>

