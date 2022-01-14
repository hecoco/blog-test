## 增删改查

### 查
cat a.txt  输入/查看文件全部内容  
head a.txt  输入/查看文件前十行内容  
head a.txt -n 25  输入/查看前25行内容  
tail a.txt  输入/查看文件后10行内容  
tail a.txt -n 25  输入/查看文件后25行内容  
less  

### 增
touch a.txt    创建一个空文件    如果文件存在则更新文件最后修改时间  
touch a.txt b.txt    创建多个空文件  
echo 这里是一段内容 > a.txt 创建一个有内容的文件  
echo 这里是一段内容 >> a.txt    创建一个有内容的文件或在该文件后面追加内容  
echo -e “有内容的文件\n有内容的文件” >> a.txt    创建一个有内容的文件或在  该文件后面追加内容（可换行，注意要加上引号否则无效）
mkdir a    创建一个空文件夹  
mkdir a b    创建多个空文件夹  
mkdir -p a b c d e    创建层级文件夹  
cp a.txt b.txt    复制文件  
cp -r a b    复制文件夹  

### 删
rm a.txt    删除文件  
rm -r a    删除文件夹  

### 改
mv a.txt b.txt    重命名文件名/文件夹名  
mv a.txt 路径    移动文件/文件夹  

tldr cp 一个命令最常用形式  

组合命令&&或 ;  
&&    执行完第一个任务后才能执行下面的任务 报错则取消执行  
;        执行全部命令 不管有有没有报错  