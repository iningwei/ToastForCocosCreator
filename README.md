## Description
This toast is inspired by [CocosCreator-Toast](https://github.com/jtly1985/CocosCreator-Toast),which is written in js.

Here i have rewrited it in ts,for ts has become more and more used in CocosCreator.

## Usage
Downlod the two ts files into your project,then you can make a toast just by one line code: ``Toast.ShowText("hello,i am jack");``.

Function ``ShowText`` have two default arguments,you can specific how long will the toast be shown and where the toast locationed.

Maybe you have noticed b4 folder,if you builded web or wechat project you should put it under directory:**res/import**。Otherwise ,when it tries to get toast bg texture,it caused 404 error。But all works fine in CocosCreator editor enviroment and localhost browser situation.

If you want get more message about it,you can read the source code.

Any troubles if you got,let me know.