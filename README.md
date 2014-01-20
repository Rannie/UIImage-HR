UIImage-HR
==========

a category about UIImage class 

#pragma mark - ImageName
//根据不同设备返回不同图片
+ (UIImage *)imageMatchSizeWithName:(NSString *)imageName;

#pragma mark - Strech and Resize
//拉伸图片
+ (UIImage *)compressImage:(UIImage *)imgSrc toSize:(CGSize)size;
//指定中间区域拉伸图片
+ (UIImage *)strechImageWithName:(NSString *)imageName;
//制定特定区域拉伸图片
+ (UIImage *)strechImageWithName:(NSString *)imageName posX:(CGFloat)x posY:(CGFloat)y;

#pragma mark - ScreenShot
//截屏
+ (UIImage *)screenshot;

#pragma mark - AddImage
//添加水印
+ (UIImage *)addImage:(UIImage *)image addMsakImage:(UIImage *)maskImage maskFrame:(CGRect)pos;

#pragma mark - Color
//颜色
+ (UIImage *)imageWithColor:(UIColor *)color;

#pragma mark - Blur
//模糊 参数0.0~1.0
+ (UIImage *)blurImage:(UIImage *)src amount:(CGFloat)amount;
