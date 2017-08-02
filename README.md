# jquery-xImage


### 一、在页面引入jquery.xImage.js

### 二、调用方式根据需求来选择，一共提供了如下几种：

#### style 0: 
```
$('#ImageBox0 img').xImage({  
	animated : 'fade'  
}); 
```

#### style 1:
```
$('#ImageBox1 img').xImage({  
	ImageNav : '#ImageNav1 li',  
	ImageTit : true,  //打开图片标题显示
	ImageBoxParent : '#ImageCon1',  //父级
	animated : 'none'  
}); 
```

#### style 2:
```
$('#ImageBox2 img').xImage({  
	ImageNav : '#ImageNav2 li',
	ImageTit : true,
	ImageBoxParent : '#ImageCon2', 
	animated : 'fade',
	autoPlay : false
}); 
```

#### style 3:
```
$('#ImageBox3 img').xImage({  
    ImageNav : '#ImageNav3 li',
	ImageTit : true,
	ImageBoxParent : '#ImageCon3',
	animated : 'left',
	overEvent : false
}); 
```

#### sytle 4:
```
$('#ImageBox4 img').xImage({  
	ImageNav : '#ImageNav4 li',
	prevBtn : '.ImagePrev',
	nextBtn : '.ImageNext',
	animated : 'top'
}); 
```

#### sytle 5:
```
$('#ImageBox5 img').xImage({  
	ImageNav : '#ImageNav5 li',
	animated : 'fade'
});
```

此为版本1.0，如果在调用过程中发现问题，欢迎来邮告知：lunali_me@163.com。


