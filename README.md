1.安装node环境,测试：node -v，npm在node安装时会自动安装，测试：npm -v
![image](https://github.com/warplan/test/blob/master/images/1.png)

2.安装grunt命令行工具（cli:command-line interface），npm install –g grunt-cli（grunt-cli中间无空格），测试成功：grunt

![image](https://github.com/warplan/test/blob/master/images/2.png)

出现上图，说明安装成功

3.	建立测试文件夹

![image](https://github.com/warplan/test/blob/master/images/3.png)

package.json文件：

![image](https://github.com/warplan/test/blob/master/images/4.png)

注：name不能为”grunt”

4.	在测试文件夹中安装grunt,命令：npm install grunt –save-dev

![image](https://github.com/warplan/test/blob/master/images/5.png)

5.	举例：安装uglify插件，npm install grunt-contrib-uglify –save-dev

![image](https://github.com/warplan/test/blob/master/images/6.png)

6.	配置Gruntfile.js,在src文件夹下新建testA.js,

![image](https://github.com/warplan/test/blob/master/images/7.png)

7.	执行grunt命令:grunt build

![image](https://github.com/warplan/test/blob/master/images/8.png)

