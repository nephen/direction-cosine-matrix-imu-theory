# 简介

  本站是对`William Premerlani 和 Paul Bizard`的[Direction Cosine Matrix IMU: Theory](http://api.ning.com/files/BhCgAMpEVgsY6Ag26S3qH9M-vAfI5HDYJWywCrNw5DC5iVUJ8EZMlcymLZ-6A6EaRCl82BVEl-7lwLa8E-z8QedqzNfL-ji1/DCMDraft2.pdf)文章的翻译。
  
####文章用处
ArduPilot的[DCM库算法](https://github.com/ArduPilot/ardupilot/blob/master/libraries/AP_AHRS/AP_AHRS_DCM.cpp#L269)实现参考文章。
  

####参与维护

1. **网页端编辑**（推荐方法：非常简单，只需三步就可以完成你的贡献）

    打开[网页端](https://github.com/nephen/new-embedded-member-learning-guidance)，进入要进行编辑的文件，如下图

    ![edit_drones](images/edit_drones.png)

    或者也可以在浏览在线页面时进行编辑，这样，只要你看到不妥的地方立马可以修改，具体如下图

    ![editpage](images/editpage.png)

    进入编辑页面后，对文件进行修改，修改完成后，提交请求，具体如下图

    ![pull_request](images/pull_request.png)

    检查是否与原有版本有冲突，如果有，解决冲突再提交，没有则提交，具体如下图

    ![open_pull](images/open_pull.png)

    剩下来就是主人的事了，如果没有太大的问题，主人就可以合并分支了，到这你的对本文档的贡献就完成了。

    ![merge](images/merge.png)

	2. 本地编辑（git高级用户推荐）

		相对于网页端编辑，本地编辑只是编辑在本地，后期的提交分支还是得在网页端进行，不过在此之前你得克隆本项目到你的仓库。

		![clone](images/clone.png)

		然后进行如下操作
		
		```sh
		#下载你的项目到本地
		git clone https://github.com/your_github_username/new-embedded-member-learning-guidance.git
		#进入文件夹进行编辑即可，完成后如下
		git add .
		git status
		#这里可以看到你的更改状况
		git commit -m "your comment"
		#添加你的更改备注，让别人知道你干了什么
		git push origin master
		#提交到云端
		```
		到这里为止，还只对你自己的仓库进行了修改，你需要按照上面的方法提交分支到nephen的仓库，可以看出，如果只是少量的更改，建议使用网页端编辑。