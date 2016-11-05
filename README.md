# OC-NetworkImageSize

##  拓展分类   `UIImage+UIImage_itdCategory.h`
```
#import <UIKit/UIKit.h>

typedef void(^ImageSizeBlock)(CGSize size);

@interface UIImage (itdCategory)

+ (void)itd_sizeOfImageWithUrlStr:(NSString *)imgUrlStr sizeGetDo:(ImageSizeBlock)doBlock;

@end
```
