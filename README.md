# vuetest

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```


開 http://localhost:8080/feeling
才會有畫面(就是後面要加上/feeling)

## 使用
請看scr/views/Feeling.vue
or
scr/views/Temp.vue
```
Header使用方法
            有以下property
            showBackArrow:Boolean //若不給值,則不顯示
            showRecord:Boolean //若不給值,則不顯示
            showUser:Boolean //若不給值,則不顯示
            showText:Boolean //若不給值,則不顯示
            navText: String 

            例:
            //只有logo
            <Nav/>
            //有logo跟user_icon   
            <Nav showUser=true />  
            //把logo改成想要的字,有返回
            <Nav showBackArrow=ture showText=true navText="測試測試" />    
Footer使用方法:
            如果想要首頁icon有顏色就把showMood改成showHome
            四個圖示分別是: showHome showSchedule showMood showResouce

```
實際使用:
```
<Nav showUser=true showRecord=true />  
<!--把自己部份的code寫在這-->
<Footer showMood=true />
```


內容是可以調整的!
例:(左邊網頁的樣子,右邊code)
 ![image](https://github.com/yoyoLin427/Vue_header_footer/blob/master/messageImage_1620360467867.jpg)
 ![image](https://github.com/yoyoLin427/Vue_header_footer/blob/master/messageImage_1620360517777.jpg)
 ![image](https://github.com/yoyoLin427/Vue_header_footer/blob/master/messageImage_1620360548619.jpg)
 ![image](https://github.com/yoyoLin427/Vue_header_footer/blob/master/messageImage_1620360609127.jpg)
 

## 其他
把自己那部分code寫在 Nav 和 Footer 之間即可
