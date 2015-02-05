在线中英文词典翻译
=====================
##作者：
浙江工业大学-计算机科学与技术学院-刘元祺
##声明：
浙江工业大学应用软件设计竞赛大一作品
本程序的前端使用了开源的Bootstrap前端开发框架、FontAwesome字体图标进行开发。
##实现功能
	*中英文单词互译
	*15000单词储备
	*记录用户最近20个单词查询记录
##环境要求：
	*PHP5或以上
	*MySQL 5.6或更高
	*测试使用Apache2.4.9，未在Nginx等环境下测试。
##关于词库：
	本词库是根据互联网免费提供的txt文件自行整理的数据库。
	使用关键字替换，导入正好的xls文件生成。
	作者整理方式、时间较为仓促，望广大同行指正！

##文件结构
│  index.html 					//首页  
│  README.md 					//说明文档  
│  word.xls 					//单词表整理得到Excel文件  
│  search.php 					//搜索单词  
│  
└─includes						//引用目录  
	│		sql_connect.php 	//数据库连接  
	│		is_chinese.php 		//判断输入内容是否中文
	│		input_decade.php 	//过滤输入内容
	└─font-awesome				//font awesome字体图标
