在你存储markdown的git目录下, 用当前git作为图片存储来转换markdown:
md2zhihu your_great_work.md -r .

-d 选项可以用来调整输出目录, 例如:
md2zhihu your_great_work.md -d my_zhihu_works/

如果要使用其他git来存储图片:
md2zhihu your_great_work.md -r git@github.com:drmingdrmer/md2test.git@test