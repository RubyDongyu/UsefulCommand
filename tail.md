tail -f filename.txt  打印文件内容，当文件内容增长时，输出增长的内容。

man tail
       -f, --follow[={name|descriptor}]
               output appended data as the file grows;
               an absent option argument means 'descriptor'
       -F     same as --follow=name --retry
