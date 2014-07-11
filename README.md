UIImage-HR
==========

a category about UIImage class 

### ImageName 
//根据不同设备返回不同图片
(Ojbective-C)
+ (UIImage *)imageMatchSizeWithName:(NSString *)imageName;

### Strech and Resize 
//拉伸图片
(Ojbective-C)
+ (UIImage *)compressImage:(UIImage *)imgSrc toSize:(CGSize)size;
//指定中间区域拉伸图片
+ (UIImage *)strechImageWithName:(NSString *)imageName;
//制定特定区域拉伸图片
+ (UIImage *)strechImageWithName:(NSString *)imageName posX:(CGFloat)x posY:(CGFloat)y;

### ScreenShot 
//截屏
(Ojbective-C)
+ (UIImage *)screenshot;

### AddImage 
//添加水印
(Ojbective-C)
+ (UIImage *)addImage:(UIImage *)image addMsakImage:(UIImage *)maskImage maskFrame:(CGRect)pos;

### Color 
//颜色
(Ojbective-C)
+ (UIImage *)imageWithColor:(UIColor *)color;

### Blur
//模糊 参数0.0~1.0
(Ojbective-C)
+ (UIImage *)blurImage:(UIImage *)src amount:(CGFloat)amount;
