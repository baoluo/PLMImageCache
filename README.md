# PLMImageCache
Asynchrone image downloader and cache, written in Obj-C &amp; Swift 

# Usage
        PLMImageCache.sharedInstance.imageForUrl(NSURL(string: "http://upload.wikimedia.org/wikipedia/commons/2/20/Johnny_Appleseed.gif"), desiredImageSize: CGSizeMake(100, 100), contentMode: nil) { (image) -> Void in
            //use image
        }