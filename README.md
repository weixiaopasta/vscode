VS-code 
保存时（ctrl+s）自动格式化页面内的代码问题解决

是JS-CSS-HTML Formatter在搞鬼，但又不能删掉他，解决措施是

1. 按F1

2. 输入Formatter Config

3. 第一行加入 `"onSave": false,`

4. 保存，搞定
