
### 文件操作
scp上传 `scp local_file user@123.123.123.123:/xhome/xxx`
scp下载 `scp user@123.123.123.123:/xhome/xxx.x .`

zip压缩 `zip -r out.zip in.dir1 in.dir2 ...`
zip解压 `unzip out.zip`
tar解压 `tar -zxvf xxx.tar.gz`
jar解压 `jar -xvf xxx.jar`

**shallow size输出文件大小并排序**: `ls -lS -h`; `ls -lS -h | head -n 20`
**deep size 排序**: `du -sh *| sort -h`

### top
**pid内线程占用**: `top -Hp pid`
**pid启动的时间**: `ps -p pid -o lstart`


### JVM
**加载过的类**: `jcmd pid PerfCounter.print | grep appClassLoadCount`


### 程序安装
**配置环境变量**
1. `vim ~/.bashrc`
2. `export PATH=$PATH:/home/username/app/sbt/bin`


### mac open
**通过chrome打开某文件** `open -a "Google Chrome" xxx.html`