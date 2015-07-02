---
layout: post
title: 在Github上搭建Blog
date: 2015-06-28
categories: code
---


1.模版

	[原始](https://github.com/waynezhang/blog.git)

	[水渍](https://github.com/Ethanol)

	[Blog](https://ethanol.github.com)
			
				
2.DNS

	[DNSPOD](https://www.dnspod.cn/Domain#jianwei.me)
	
	[Godaddy](https://www.godaddy.com/)
	
	[域名解析](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/)
	
	[Github-Pages-Basic](https://help.github.com/categories/github-pages-basics/)
	
3.开始动手

	3.1 切换RubyGems源(http://ruby.taobao.org/)
		$ gem sources --remove https://rubygems.org/
		$ gem sources -a https://ruby.taobao.org/
		$ gem sources -l
		*** CURRENT SOURCES ***

		https://ruby.taobao.org
		请确保只有 ruby.taobao.org
				
	3.2 Jekyll(http://jekyllrb.com/)
		$ gem install jekyll 
		$ jekyll new blog-site
		$ cd blog-site
		$ jekyll serve
	
	3.3 Push
		
		$ git clone your-repositories
		$ jekyll new blog
		$ mv /blog/* .
		$ git add .
		$ git commit -m 'init'
		$ git push
		$ .........input your username & password
		Done!...
	
