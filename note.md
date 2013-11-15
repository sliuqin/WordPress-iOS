## 图片性能
- `+ (UIImage *)imageNamed:(NSString *)name` 缓存图片,但多次用到统一这样图片时,应该使用.
- `+ (UIImage *)imageWithContentsOfFile:(NSString *)path` 不缓存图片,只用一次的图片应该使用该方法载入.
