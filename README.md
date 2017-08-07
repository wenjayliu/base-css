# base-css
##css components 

## 目录
  1. [flex layout](#flex)
  2. [ul li beautify](#ulb)
  3. [js操作cookie](#js-cookie)
  4. [css强制换行/自动换行/强制不换行](#word-wrap)
  

### <a id="flex" name="flex">1. CSS flex layout</a>  
 flex
 
```css


	/*flex layout*/

        /*base*/
       
        .flex {
			display: -webkit-flex;
			display: -webkit-box; /* Chrome 4+, Safari 3.1, iOS Safari 3.2+ */  
			display: -moz-box; /* Firefox 17- */  
			display: -webkit-flex; /* Chrome 21+, Safari 6.1+, iOS Safari 7+, Opera 15/16 */  
			display: -moz-flex; /* Firefox 18+ */  
			display: -ms-flexbox; /* IE 10 */  
			display: flex; /* Chrome 29+, Firefox 22+, IE 11+, Opera 12.1/17/18, Android 4.4+ */  
		}

		/*center*/
		.flexc {
			display: -webkit-flex;
			display: -webkit-box; /* Chrome 4+, Safari 3.1, iOS Safari 3.2+ */  
			display: -moz-box; /* Firefox 17- */  
			display: -webkit-flex; /* Chrome 21+, Safari 6.1+, iOS Safari 7+, Opera 15/16 */  
			display: -moz-flex; /* Firefox 18+ */  
			display: -ms-flexbox; /* IE 10 */  
			display: flex; /* Chrome 29+, Firefox 22+, IE 11+, Opera 12.1/17/18, Android 4.4+ */  
			display: -webkit-flex;
			justify-content:center; 

		}
		/*vertical*/
		.flexz {
			display: -webkit-flex;
			display: -webkit-box; /* Chrome 4+, Safari 3.1, iOS Safari 3.2+ */  
			display: -moz-box; /* Firefox 17- */  
			display: -webkit-flex; /* Chrome 21+, Safari 6.1+, iOS Safari 7+, Opera 15/16 */  
			display: -moz-flex; /* Firefox 18+ */  
			display: -ms-flexbox; /* IE 10 */  
			display: flex; /* Chrome 29+, Firefox 22+, IE 11+, Opera 12.1/17/18, Android 4.4+ */  
			align-items: center;
			-webkit-align-items:center;
			box-align:center;
			-moz-box-align:center;
			-webkit-box-align:center;  
		}
		/*center and vertical*/
		.flexcz {
			display: -webkit-box; /* Chrome 4+, Safari 3.1, iOS Safari 3.2+ */  
			display: -moz-box; /* Firefox 17- */  
			display: -webkit-flex; /* Chrome 21+, Safari 6.1+, iOS Safari 7+, Opera 15/16 */  
			display: -moz-flex; /* Firefox 18+ */  
			display: -ms-flexbox; /* IE 10 */  
			display: flex; /* Chrome 29+, Firefox 22+, IE 11+, Opera 12.1/17/18, Android 4.4+ */  
			display: -webkit-flex;
			justify-content:center; 
			align-items: center;  
		}
	/*flex layout end*/

```

### <a id="flex" name="flex">2.ul li beautify</a>  
	
	offect images /
	
(http://github.com/wenjayliu/base-css/components/ullibeautify.png)

![image](https://github.com/wenjayliu/base-css/blob/master/components/img/ullibeautify.PNG)  
[flex](http://mp.weixin.qq.com/s?__biz=MzAxODE2MjM1MA==&mid=2651552434&idx=1&sn=c166effbc0684c84c701448cc651577d&chksm=8025ad73b7522465b496ac8115ad3d05c72e61e4e60be16a74959dd505c936724f1c660aabf4&mpshare=1&scene=1&srcid=0806STPyV00Fj5RhBn3Q7b45#rd)
