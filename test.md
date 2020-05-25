使用工具：blind-watermark

https://github.com/linyacool/blind-watermark

添加水印：
python3 encode.py --image cat.png --watermark rxt.png --result cat_wm.png 

提取水印：
python3 decode.py --original cat.png --image cat_wm.png --result rxt_res.jpg

注：多次尝试发现此工具对png图片的处理效果比对jpg图片好，许多jpg图片无法再还原出清晰水印，故此次实验使用png图片。
