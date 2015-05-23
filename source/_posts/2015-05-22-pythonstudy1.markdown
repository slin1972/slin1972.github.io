---
layout: post
title: "Python 学习"
date: 2015-05-22 02:39:03 +0800
comments: true
categories: [Python]
---

###这段时间有时候会利用空余时间学习Python

####使用的版本是2.7

#####使用requests获取网络资源
	
	GET

	import requests
	
	params = "key1="+value1+"&key2="+value2+"&keyn"+valuen
	
	html = requests.get("http://www.baidu.com",params)
	
	print html.text

	POST
	
	import requests
	
	params ={"key1":"value1","key2":"value2","keyn":"valuen"}
	
	html = requests.get("http://www.baidu.com",params)
	
	print html.text