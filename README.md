UIImage-HR
==========

a category about UIImage class 

### ImageName (Ojbective-C)
//根据不同设备返回不同图片
+ (UIImage *)imageMatchSizeWithName:(NSString *)imageName;

### Strech and Resize (Ojbective-C)
//拉伸图片
+ (UIImage *)compressImage:(UIImage *)imgSrc toSize:(CGSize)size;
//指定中间区域拉伸图片
+ (UIImage *)strechImageWithName:(NSString *)imageName;
//制定特定区域拉伸图片
+ (UIImage *)strechImageWithName:(NSString *)imageName posX:(CGFloat)x posY:(CGFloat)y;

### ScreenShot (Ojbective-C)
//截屏
+ (UIImage *)screenshot;

### AddImage (Ojbective-C)
//添加水印
+ (UIImage *)addImage:(UIImage *)image addMsakImage:(UIImage *)maskImage maskFrame:(CGRect)pos;

### Color (Ojbective-C)
//颜色
+ (UIImage *)imageWithColor:(UIColor *)color;

### Blur (Ojbective-C)
//模糊 参数0.0~1.0
+ (UIImage *)blurImage:(UIImage *)src amount:(CGFloat)amount;
