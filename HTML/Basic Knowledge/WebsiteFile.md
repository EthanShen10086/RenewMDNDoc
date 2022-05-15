### get Copyright-free images

use Google's license filter. Click on the Tools button, then on the resulting Usage rights option that appears below.

You should choose the option ==Creative Commons licenses==.

![how to get copyright free img](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like/updated-google-images-licensing.png)

### set up font

[how to set up font](https://developers.google.com/fonts/docs/getting_started)

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Font+Name"> 
```
首先一般会在head标签上link住

然后通过内联或者css选择器模式应用
```css
.css-selector {
font-family: 'Font Name', serif;
}
```

### file dealing

name folders and files completely ==in lowercase with no spaces==.

这里指的是存放文件的文件夹以及文件

web ==servers==, are ==case-sensitive==
服务器是大小写敏感的

web servers, and programming languages do ==not handle spaces consistently==.
服务器也是空格敏感的
Some servers will replace the areas in your filenames with =="%20"== (the character code for ==spaces== in URLs)

It's better to separate words with ==hyphens（连接符）==, rather than ==underscores（下划线）==: 
最好使用连接符命名多媒体文件以及文件夹名
Google search engine treats a hyphen as a word separator but does not regard an underscore that way. 

### website structure

