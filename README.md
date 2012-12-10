#GuestBean4Android
Common methods for android developer.


#OverView
| Class                     | Description   |
| ------------              | ------------- |
| GB_BitmapUtils.java       | ...           |
| GB_BitmapEffectUtils.java | …             |

#Example
#### **GB_BitmapUtils.java**

* 获得GB_BitmapUtils实例
  		
		GB_BitmapUtils bitmapUtils = new GB_BitmapUtils();
	
* Bytes数组转换为Bitmap类型对象
		
		bitmapUtils.bitmap2Bytes(bitmap);
	
* Drawable转换为Bitmap类型对象
	
		bitmapUtils.bitmap2Drawable(bitmap);
		
* 将Bytes数组转换为Bitmap类型对象

		bitmapUtils.bitmapFromBytes(data);

* 将Drawable转换为Bitmap类型对象

		bitmapUtils.bitmapFromDrawable(drawable);
			
* 设置Bitmap尺寸
	
		bitmapUtils.bitmap2Resize(bitmap, width, height);
			
* 设置Bitmap圆角
	
		bitmapUtils.bitmap2Round(bitmap, roundPx);
			
* 设置Bitmap倒影
	
		bitmapUtils.bitmap2ReflectionImage(bitmap, reflectionImageDistance);
			
* 设置Bitmap图片水印

		bitmapUtils.bitmap2WatermarkImage(bitmap, watermark);
			
* 设置Bitmap文字水印

		bitmapUtils.bitmap2WatermarkText(bitmap, text, textColor, textSize, x, y, isHorizentalCenter);


#### **GB_BitmapEffectUtils.java**

* 获得GB_BitmapEffectUtils实例

        GB_BitmapEffectUtils bitmapEffectUtils = new GB_BitmapEffectUtils();
        
* 设置Bitmap对象的亮度

        bitmapEffectUtils.setBrightness(bitmap, brightness);
        
* 设置Bitmap对象的RGB

        bitmapEffectUtils.setRGB(bitmap, red, green, blue)；

* 设置Bitmap对象的老照片效果 

        bitmapEffectUtils.oldRemeberBitmap(bitmap)；



