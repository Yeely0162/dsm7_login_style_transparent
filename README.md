警告！！！ 此脚本只适应DS918+ 7.1.1版本，切勿在其他版本使用 <br>
警告！！！ 此脚本只适应DS918+ 7.1.1版本，切勿在其他版本使用 <br>
警告！！！ 此脚本只适应DS918+ 7.1.1版本，切勿在其他版本使用 <br>
<br>
运行教程：<br>
    0、上传脚本到群晖 <br>
    1、开启ssh并进入群晖后台 <br>
    2、sudo -i  切换Roor用户 <br>
    3、cd 《上传脚本的路径》 可在File Station 右键点击install脚本-属性-位置 获取 <br>
    4、chmod 755 install.sh 赋予脚本运行权限 <br>
    5、./install.sh 运行脚本 <br>
<br>
替换文件存放路径: <br>
    style.css：/usr/syno/synoman/webman/login/dist/style.css <br>
    style.css.gz：/usr/syno/synoman/webman/login/dist/style.css.gz <br>
    1bc43875501e55e5e741e427ca50dbdf.png：/usr/syno/synoman/webman/login/dist/assets/1bc43875501e55e5e741e427ca50dbdf.png <br>
    3.SecureSignInLogin.css：/usr/syno/synoman/webman/3rdparty/SecureSignIn/login-dist/3.SecureSignInLogin.css <br>
    68b2c5f5747c3085bba5dd628b90ae0f.gif：/usr/syno/synoman/webman/3rdparty/SecureSignIn/login-dist/assets/68b2c5f5747c3085bba5dd628b90ae0f.gif <br>
    addc28996dad298560fd62666efd5c0b.gif：/usr/syno/synoman/webman/3rdparty/SecureSignIn/login-dist/assets/addc28996dad298560fd62666efd5c0b.gif <br>
<br>
脚本路径：<br>
    gif: 批准登录动图原文件
    patch：文件补丁
    backups： 第一次替换后生成的目录，里面存放替换文件的备份
    backups(未修改文件)： 给替换过文件，但没保存原文件的用，使用方法重命名删除《（未修改文件）》字段，第一次安装不再备份。
<br>
备注：本人ps菜的扣脚，gif动图存在瑕疵，会ps的大神可自己在在gif目录下载动图修改后替换patch文件中动图