# curstar.github.io
index是主页
article技术博客
index2是杂文

class. image left 和 image right 和image fit设置了按照原图像大小进行缩放

                    
		.image.fit {
			display: block;
			margin: 0 auto;
     }
      
      @media (min-aspect-ratio: 1/1) and (min-width:1000px) {
        .image{
          max-width: 60%;
        }
      }
      
      @media (max-aspect-ratio: 1/1) and (min-height:1000px) {
        .image {
          max-width: 50%;
        }
      
    }