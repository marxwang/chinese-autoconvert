Windows上有用ConvertZ可以方便地轉影片字幕檔，但是ConvertZ必須自己指定檔案的編碼，對於多檔轉換時很麻煩，因此做了自動轉檔程式，會自動轉換編碼為UTF-8並加上BOM，還會將詞彙轉成習慣用語。

每個目錄都可有自訂使用者字典。
用法：
```
python g2butf8.py  *.srt 
```
或是
```
 python g2butf8.py 城市獵人*.ssa
```

Windows平台可用現成的exe
```
g2butf8 *.ssa 
```

**因為 Google Code不再提供下載，只能用自己的quota把 Windows binary放到Google Drive**


[g2butf8\_amd64.zip](https://drive.google.com/file/d/0B_twESMPpEmWSEFMTXRSWTBaZWs/view?usp=sharing)

[g2butf8\_win32.zip](https://drive.google.com/file/d/0B_twESMPpEmWdmxyZHVDOUFYemM/view?usp=sharing)