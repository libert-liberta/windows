# Windows11のコンテキストメニューを旧仕様に戻す方法  
https://qiita.com/www-tacos/items/d23b24f5af8687f2db88  
## 旧仕様に変更する場合  
`reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`  
## Windows11の仕様に戻す場合  
`reg.exe delete "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f`  
