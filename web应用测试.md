#Web应用测试
####导语：
>Web应用测试对于一个web应用来说至关重要。即检查核对当前产品存在哪些方面的问题，在此主要测试内容为内容测试，功能测试，图形测试，界面测试。

##一、内容测试
内容测试用来检验Web应用系统提供信息的正确性、准确性和相关性。

##二、功能测试
功能测试用例：

###1. 首页测试
	* 测试号：01001
	* 测试内容：  
	用户点击打开浏览器后进入网站首页是否可以正常进入首页，首页页面显示是否正常。
	* 前置条件：
	用户系统正常，浏览器正常运行。
	* 测试环境：
	Windows10操作系统和各大主流浏览器。
	* 测试步骤：
	用户打开浏览器，用户在浏览器的地址栏中输入网站首页的URL，进入主页。
	* 预期结果：
	首页内容可以正常呈现给用户，用户可以在首页浏览信息。
###2. 热门功能跳转测试
	* 测试号：02001
	* 测试内容：
	热门页面跳转是否正确，跳转不正确后是否有正确信息提示。
	* 前置条件：
	浏览器正常运行，01001。
	*  测试环境：
	Windows10操作系统和各大主流浏览器。
	* 测试步骤:
	（1）用户打开浏览器，用户在浏览器的地址栏中输入网站首页的URL，进入主页。
	（2）用户点击热门功能按钮，页面跳转。
	* 预期结果：
	跳转正确情况下显示内容，跳转失败显示失败信息。
###3. 热门功能内容测试
	* 测试号：02002
	* 测试内容：
	热门页面跳转后内容显示是否正确。
	* 前置条件：
	浏览器正常运行。01001，02001。
	*  测试环境：
	Windows10操作系统和各大主流浏览器。
	* 测试步骤:
	（1）用户打开浏览器，用户在浏览器的地址栏中输入网站首页的URL，进入主页。
	（2）用户点击热门功能按钮，页面跳转。
	（3）页面跳转后用户浏览页面所显示内容。
	* 预期结果：
	跳转正确情况下内容显示正确，内容排版正确。
###4. 分类功能跳转测试
	* 测试号：03001
	* 测试内容：
	分类页面跳转是否正确，跳转不正确后是否有正确信息提示。
	* 前置条件：
	浏览器正常运行，01001。
	*  测试环境：
	Windows10操作系统和各大主流浏览器。
	* 测试步骤:
	（1）用户打开浏览器，用户在浏览器的地址栏中输入网站首页的URL，进入主页。
	（2）用户点击分类功能按钮，页面跳转。
	* 预期结果：
	跳转正确情况下显示内容，跳转失败显示失败信息。
###5. 分类功能内容测试
	* 测试号：03002
	* 测试内容：
	分类页面跳转后内容显示是否正确。
	* 前置条件：
	浏览器正常运行。01001，03001。
	*  测试环境：
	Windows10操作系统和各大主流浏览器。
	* 测试步骤:
	（1）用户打开浏览器，用户在浏览器的地址栏中输入网站首页的URL，进入主页。
	（2）用户点击分类功能按钮，页面跳转。<br>
	（3）用户根据分类页面所呈现的内容，浏览页面中的信息。
	* 预期结果：
	跳转正确情况下分类页面的内容显示正确，分类内容排版正确。
###6. 历史功能跳转测试
	* 测试号：04001
	* 测试内容：
	历史页面跳转是否正确，跳转不正确后是否有正确信息提示。
	* 前置条件：
	浏览器正常运行，01001。
	*  测试环境：
	Windows10操作系统和各大主流浏览器。
	* 测试步骤:
	（1）用户打开浏览器，用户在浏览器的地址栏中输入网站首页的URL，进入主页。
	（2）用户点击历史功能按钮，页面跳转。
	* 预期结果：
	跳转正确情况下显示内容，跳转失败显示失败信息。
###7. 历史功能内容测试
	* 测试号：04002
	* 测试内容：
	页面跳转后内容显示是否正确。
	* 前置条件：
	浏览器正常运行。01001，04001。
	*  测试环境：
	Windows10操作系统和各大主流浏览器。
	* 测试步骤:
	（1）用户打开浏览器，用户在浏览器的地址栏中输入网站首页的URL，进入主页。
	（2）用户点击历史功能按钮，页面跳转。
	（3）用户查看系统纪录的用户浏览历史的内容信息。
	* 预期结果：
	没有任何浏览记录时显示为空，有浏览记录时显示浏览记录。
### 8.关注测试用例
    * 测试编号：05001
    * 测试内容：
	    关注页面跳转是否正确
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
        (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【关注】按钮
    * 预期结果：
	    成功跳转到关注页面，并显示用户关注的内容
### 9.注册测试用例
    * 测试编号：06001
    * 测试内容：
	    验证系统是否对必填项为空时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
        (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“注册”界面什么都没有输入，直接点击【注册】按钮
    * 预期结果：
	    注册失败，页面重新回到注册页面，并提示“请输入必填项”

    * 测试编号：06002
    * 测试内容：
        验证系统是否对用户名含义非法字符时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123+abc”
        (5)在“密码”文本框输入“abc123456”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn@gmail.com”
        (7)单击【注册】按钮
    * 预期结果：
	    注册失败，页面重新回到注册页面，并提示“用户名含有非法字符”

    * 测试编号：06003
    * 测试内容：
        验证系统是否对密码含有非法字符时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123abc”
        (5)在“密码”文本框输入“abc*123456”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn@gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册失败，页面重新回到注册页面，并提示“密码含有非法字符”

    * 测试编号：06004
    * 测试内容：
        验证系统是否对邮箱格式不正确时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123abc”
        (5)在“密码”文本框输入“abc123456”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn.gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册失败，页面重新回到注册页面，并提示“邮箱地址格式有错误”

    * 测试编号：06005
    * 测试内容：
        验证系统是否对用户名重复时做出正确的响应
    * 测试环境：
    	Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123abc”
        (5)在“密码”文本框输入“abc123456”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn.gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册失败，页面重新回到注册页面，并提示“用户名已被注册，请重新输入”

    * 测试编号：06006
    * 测试内容：
        验证系统是否对用户名长度过长时允许注册
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123abc123456789101112”
        (5)在“密码”文本框输入“abc123456”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn.gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册失败，页面重新回到注册页面，并提示“用户名长度过长”

    * 测试编号：06007
    * 测试内容：
        验证系统是否对密码长度过长时允许注册
    * 测试环境：
    	Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123abc”
        (5)在“密码”文本框输入“abc123456789101112”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn.gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册失败，页面重新回到注册页面，并提示“密码长度过长”

    * 测试编号：06008
    * 测试内容：
        验证系统是否对用户名长度过短时允许注册
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123”
        (5)在“密码”文本框输入“abc123456”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn.gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册失败，页面重新回到注册页面，并提示“用户名长度过短”

    * 测试编号：06009
    * 测试内容：
        验证系统是否对密码长度过短时允许注册
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123abc”
        (5)在“密码”文本框输入“abc”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn.gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册失败，页面重新回到注册页面，并提示“密码长度过短”

    * 测试编号：06010
    * 测试内容：
        验证系统是否对合法输入做出正确的响应 
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)在“用户名”文本框输入“123abc”
        (5)在“密码”文本框输入“abc123456”
        (6)在“验证邮箱”文本框输入：“xsqiu.chn.gmail.com”
        (7)单击【注册】按钮
	* 预期结果：
	    注册成功，自动登录并跳转到主页，并提示“注册成功”

    * 测试编号：06011
    * 测试内容：
        Tab按键是否正确响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“注册/登录”页面中点击【注册】按钮，进入“注册”页面
        (4)将鼠标光标移动到“用户名”文本框内，单击鼠标左键
        (5)点击Tab键
	* 预期结果：
	    光标依次跳转到“密码”、“验证邮箱”文本框和【注册】按钮内

### 6.登录测试用例
    * 测试编号：07001
    * 测试内容：
        验证系统是否对输入合法用户名和密码时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“用户名”文本框输入“123abc”
        (4)在“密码”文本框输入“abc123456”
        (5)单击【登录】按钮
    * 预期结果：
	    登陆成功
	
	* 测试编号：07002
    * 测试内容：
        验证系统是否对输入错误的用户名或者密码时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“用户名”文本框输入“123bbc”
        (4)在“密码”文本框输入“abc123456”
        (5)单击【登录】按钮
    * 预期结果：
	    登录失败，并提示“您输入的用户名或者密码不正确”

    * 测试编号：07003
    * 测试内容：
        验证系统是否对用户名或者密码为空时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)单击【登录】按钮
    * 预期结果：
	    登录失败，并提示“请输入用户名和密码”
	    
	* 测试编号：07004
    * 测试内容：
        验证系统是否对用户名或者密码大小写敏感
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“用户名”文本框输入“123ABC”
        (4)在“密码”文本框输入“abc123456”
        (5)单击【登录】按钮
    * 预期结果：
	    登录失败，并提示“请输入正确的用户名或者密码”
	    
	* 测试编号：07005
    * 测试内容：
        验证系统是否对用户名或者密码中含有全角字符敏感
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)在“用户名”文本框输入“１２３ａｂｃ”
        (4)在“密码”文本框输入“ａｂｃ１２３４５６”
        (5)单击【登录】按钮
    * 预期结果：
	    登录失败，并提示“请输入正确的用户名或者密码”

    * 测试编号：07006
    * 测试内容：
        Tab按键是否正确响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
	* 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中点击【注册/登录】按钮，进入“注册/登录”页面
        (3)将鼠标光标移动到“用户名”文本框内，单击鼠标左键
        (4)点击Tab键
	* 预期结果：
	    光标依次跳转到“密码”文本框和【注册】按钮内

### 8.搜索测试用例
    * 测试编号：08001
    * 测试内容：
        验证系统是否对不输入任何字符，点击搜索按钮时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在主页中直接点击【搜索】按钮
    * 预期结果：
	    搜索出网站所有的视频
	    
	* 测试编号：08002
    * 测试内容：
        验证系统是否对搜索关键词为单个中文、英文、数字时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在“搜索”文本框输入“我”
        (3)点击【搜索】按钮
    * 预期结果：
	    显示与搜索关键相匹配的结果信息

    * 测试编号：08003
    * 测试内容：
        验证系统是否对搜索关键词为中文、英文、数字相互组合时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在“搜索”文本框输入“加勒比海盗3”
        (3)点击【搜索】按钮
    * 预期结果：
	    显示与搜索关键相匹配的结果信息
	    
	* 测试编号：08004
    * 测试内容：
        验证系统是否对搜索关键词大小写敏感
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在“搜索”文本框输入“INCEPTION”
        (3)点击【搜索】按钮
    * 预期结果：
	    显示与搜索关键相匹配的结果信息

    * 测试编号：08005
    * 测试内容：
        验证系统是否对搜索关键词全角字符敏感
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在“搜索”文本框输入“ＩＮＣＥＰＴＩＯＮ”
        (3)点击【搜索】按钮
    * 预期结果：
	    提示“很抱歉，没有找到相关的内容”
	    
	* 测试编号：08006
    * 测试内容：
        验证系统是否对搜索关键词包含特殊字符时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在“搜索”文本框输入“@#”
        (3)点击【搜索】按钮
    * 预期结果：
	    提示“很抱歉，没有找到相关的内容”

    * 测试编号：08007
    * 测试内容：
        验证系统是否对搜索关键词过长时做出正确的响应
    * 测试环境：
	    Windows 10操作系统和各大主流浏览器
    * 测试步骤：
	    (1)打开浏览器，在浏览器的地址栏中输入网站首页的URL，进入主页
        (2)在“搜索”文本框输入“哈哈哈哈哈哈哈哈哈哈哈哈”
        (3)点击【搜索】按钮
    * 预期结果：
	    提示“输入过长”
	
##三、图形测试
在Web应用系统中，适当的图片和动画既能起到广告宣传的作用，又能起到美化页面的功能。一个Web应用系统的图形可以包括图片、动画、边框、颜色、字体、背景、按钮等。图形测试的内容有：

1. 要确保图形有明确的用途，图片或动画不要胡乱地堆在一起，以免浪费传输时间。Web应用系统的图片尺寸要尽量地小，并且要能清楚地说明某件事情，一般都链接到某个具体的页面。
2. 验证所有页面字体的风格是否一致。
3. 背景颜色应该与字体颜色和前景颜色相搭配。
4. 图片的大小和质量也是一个很重要的因素，一般采用JPG或GIF压缩。

##四、界面测试
整体界面的设计应该保证给用户一个舒适感。首先确保每个页面的设计风格一致，其次确保每个页面的的美观性，以及需要思考每个部件的美观效果，以及部件之间的对齐关系。



