#frame_test
# this is a frame_test project 
#wiki
# https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000

#1-> install git tools
	sudo apt-get install git
#2->set developer name
	git config --global user.name "you name"
#3->set developer email 
	git config --global user.email "email@example.com"
#4->create git enviroment in project 
	git init
#5->add files to repository stage 
	git add <file_name>
#6->commit files to current repository branch
	git commit -m "my commit"
#7->create repository SSH KEY(github)
	ssh-keygen -t rsa -C "youremail@example.com"
	//在用户主目录 .ssh 里面有id_rsa 和 id_rsa.pub两个文件
#8->push id_rsa.pub file to github

#9->add remote repository 
	git remote add origin git@github.com:moduleclub/frame_test.git 
#10->push master repository to github
	git push origin master
	
