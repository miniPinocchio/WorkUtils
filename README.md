# WorkUtils
工具类集合
从现在开始 常用的工具类都放在这个集合</br>
1.BitmapUtils </br>
  
Android实际开发中，在加载大量图片的时候，比如ViewPager、GridView、ListView中</br>
，加载了大量的比较大图片就容易出现OOM（内存溢出）的异常，这是因为android规定一个应用的最大内存使用上限</br>
，超过了这个值，就会出现OOM。所以我们实际开发中，要想避免OOM出现就要对相应的图片进行压缩处理。</br>
本文即使用了BitmapFactory和BitmapFactory.Option这两个类，对图片进行相应的尺寸压缩处理</br>
