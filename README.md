#frame_test
# this is a frame_test project 
#wiki
# https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000

#1->安装git工具 
	sudo apt-get install git
#2->设置开发者的名字
	git config --global user.name "you name"
#3->设置开发者的邮箱
	git config --global user.email "email@example.com"
#4->在工程文件下创建版本库
	git init
#5->把文件加到版本库中临时内存中
	git add <file_name>
#6->提交文件到版本库中
	git commit -m "my commit"
#7->创建远程仓SSH KEY(以github为例)
	ssh-keygen -t rsa -C "youremail@example.com"
	//在用户主目录 .ssh 里面有id_rsa 和 id_rsa.pub两个文件
#8->将id_rsa.pub内容传到github上

#9->添加远程仓
	git remote add origin git@github.com:moduleclub/frame_test.git 
#10->推送master分支到github
	git push origin master
	
