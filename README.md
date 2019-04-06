# 双二极管钳位电路的原理  

如图，水平的线是受保护的节点。当该点电压超过Vcc+0.7V时，上面的二极管导通；而当该点电压小于-0.7V时，下面的二极管导通。因此，该点电压被钳制在Vcc+0.7V—— -0.7V之间。

![啦啦啦啦啦](https://github.com/lyh523329053/Clamp-Circuit/tree/master/pic/DualDiodeClamp.jpg "这是一个markdown插入的图片的标题")  
双二极管钳位电路的原理
对于正常的二极管，其正向电阻约为几千欧，反向电阻为几百千欧 (一般应大于 200 千欧），而场MOS管一般内阻都在10M——1000G欧，所以二极管的内阻远小于场效应管的电阻。如果电压过高，高于Vcc+Vd（二极管导通压降），上面的二极管导通，输出电压钳位于Vcc+Vd；如果电压过低，低于0-Vd（二极管导通压降），下面的二极管导通，输出电压钳位于-Vd。
