# 2024B站最值得看的黑客教程 ｜ 网络安全／渗透测试／内网渗透／漏洞挖掘／web安全／kali linux／红队靶场／CTF／信息安全 - P33：实战利用BP挖掘口令漏洞 - 网络安全免费学 - BV1uBsTetEow

接下来okK就到入我们最激动人心的一个时刻了。好吧，就是我们实战漏洞挖掘。O准备好的小伙伴，知前的小伙伴，大家听懂70%到80%就可以了。如果你听懂了7%到80%给我扣波一，接下来立马进行实战。

我们就用刚才的方法现场给你挖两个洞，好不好？觉得okK的，来扣波一，我们准备发车。😊，OK了是吧？好，没有问题。那就发车啊。说李哥，你讲这么多，我还是没懂啊，你能不能给我演示一下对不对啊？

示下演示一下我就懂了，没有问题，对不？似懂非懂也没有关系，好不好啊？然后呢来后面的时候你可以看看笔记啊，接下来讲这个实战是重点，对不对啊？之前东西只能说是一个普及东西啊，来我们来看一波实战啊。

在实战之前啊，我们来看几波案例，好不好？什么叫案例，就是我们用这样的方法挖到过的一些漏洞啊啊，这个漏洞我们来先看一下啊，我不知道有没有看到啊。

这个大家看一下是不是UCUC大家懂不懂是不是UC浏览器UC这属于谁呢？是属于阿里巴巴旗下的一个东西，对不对？好，UC呢啊之前有这样一个页面，看到没？

叫什么叫加入UC它的这样一个欢迎加入我们的这样一个页面，对吧？这里让你输入什么一些什么账户名密码，对不对？然后输入短信验证码，对不对？然后点击下一步啊，就可以去注。😊，注册到他们UC的相关东西了啊。

这是UC的这样一个界面。OK好，那么然后呢我在干嘛的时候呢哎。😊，我在注册的时候，你看啊，我把这里啊写成了一个爱丽丝啊，我点击注册。好，那么UC这里给我弹出一个框，提示该用户名已存在，请用其他用户名。

兄弟们。就这么简单一个案例，请你告诉我它是不是漏洞。是不是漏洞，我在注册的时候，我在这里写了爱丽丝，我点击下一步啊，它立马给我提示一个该用户名已存在。请用其他用户名。是不是漏豆？有人说不是。

还有人说不是我告诉你，他就是一个漏洞。有人说哎，那为什么是呢？😡，那我输入。爱丽丝存在，那我输入鲍勃呢？😡，啊，我输入jack呢我输入1万个名字呢，我是不是能知道他这个系统里面都有多少个人注册了。😡。

对不对？什么张三李四王伟，我最起码知道谁注册了。😡，对不对？那这个漏洞叫什么呢？叫做什么啊，叫做任意用户枚举。😡，是不是这个道理啊？那我既然输入爱丽丝他给我提示存在，那我输入抱抱这提示正常注册。

或者说我输入抱抱，他不提示用户名存在，对不对？它提示其他的O啊，那我就可以通过这点，我看我输入哪个名字，他提示用户已存在，那我是不是就能进行任意用户枚举了，对吧？我不管你是不是假名。

那么这个用户是人家UC上注册的，我就知道你注册的这个用户的用户名是啥的，对不对？是爱丽丝张三李四王8的到底是哪个，对不对？我是不是可以弄一个很长很长的一个表，然后去罗列一下。😡，啊，有人说啊照你这样说。

那什么的，哎，我告诉你还真不是的，不是所有的网站都有这样一个漏洞。那你们说这个漏洞给我多钱？😡，啊，这个漏洞你觉得值多少钱来。😡，把你觉得值多钱的钱打到公屏上，好吧。大家觉得这个东西值多钱？😡，50。

哎，没错，这个漏洞哎50块钱哎，没有问题，大家看一下是不是50块钱。😊，看到没？8个安全币啊，一个大家说一下，一个安全币是10块钱，对不对？那么8个就是80块钱啊，这个漏洞啊就给了我80块钱。

简单不简单？那这个漏洞怎么挖？哎，非常简单嘛，对吧？啊，你看到没？用我们BP的这个工具。我刚刚说了BP是不是可以拦截下来，那我就把爱丽丝那一块啊，让他批量去测一遍嘛。哇，我用1万个，对不对？

我在这里测最终测出来了，大约五六十个账号啊，就直接给了80，就这么简单。😊，啊，80块到手了，你说这个漏洞难不难？😊，啊，是个人都会吧啊，是不是个人都会，你敢说你不会啊，我不相信你不会啊，对不对？

为什么你挖不到园，就是没有人给你讲呀？😡，谁他妈给你讲这些啊，是人家吃饭的家伙呀，对不对？没有人给你讲，你永远不知道这玩意还能值钱，对不对？谁都觉得不难，只是没有人点你，对吧？好，这是第一个案例好不好？

啊，那接下来啊对吧？你们很多人不知道你您说你赚不到你认知之外的钱，对吧？在这个行业里，有的时候挖洞就是那么简单，没有你们想的那么难，对吧？也没有你们想的那么复杂啊，只是大家可能没有人给你讲这些东西。

对不对啊？讲这东西啊，80块好，我们接下来再看一个零倍，零倍，大家听过没有？😊，来零队大家知道不知道啊，零队大家听过没有？就是哎可能没零的就是哎零队没有就是零的就是没有公开的漏洞，叫零日漏洞，对不对？

零日漏洞啊，我接下来给大家看个零队好吧好？你们可能没有见过啊，这个零队呢之前交了CNVD了对吧？CNVD的一个零队啊，我们来看看这个这个零的多少钱啊，这个零的不贵啊，因为它的价值不高啊，就几千块钱吧。

就几千块钱左右这个钱啊，但是我们没有赚钱，我们因为发现零队的一般不能换钱啊，要交给国家，我们最后也是把它交给国家了哈，就得我们发现了这样一个页面。😊，好，来，同学们发现了一个这样的页面，要干什么？😡。

可以用我们的BP去破解他的用户名跟密码暴力破解。那最终破开了没有？of course破开了他的账号密码。😡，看到没？破开了啊，进入到它的这个页面里面来了，对不对？进去了进去之后啊，在里面通过BP挖洞啊。

挖到了一个CQ注入。OK直接给了一张CNVD的证书。简不简难啊，就是这个cQ住难不难，不难，用ciq map一跑就可以了。但是难哪里难在这个页面，你破不开啊，你不知道他的账号密码，你进不去，只要能进去。

😡，狗都能把这个零头挖出来啊，但是你们进不去啊，所以说进店样的页面有几种方法啊，第一个用特权账号啊，这里我就不说了，对吧？如果你是行内人，可能会有一些特权账号，比如美团账号什么进，对吧？在固定网站。

第二种就是我们的硬暴力破解。对，用字典破啊，这里提供一个账号，这里提为密码，试我试他10天半个月，对不对？看他能不能试出来，一个一个试。😊，对不对？我们把常用的这种东西去试一下，是就是一个一个试啊。

叫暴力破解漏洞。对啊，您说字典啥？字典就是存在了很多账号跟密码的1个TST文件。我们用BP带着这个文件一个一个往这个框里面去试，对不对？啊，当然我们不是用手势ABC我们是用BP自动去试，懂不懂？

自动自动自动啊，它先账号先是A密码先是B先C，然后一个一个试，对不对？你只用睡个觉，第二天起来看一下哪个成功了okK就可以了，明白吗？我们BP刚才给大家讲了，应出的模块是不是批量注册批量修改。

批量跑的这样一个功能啊，它是批量的。那么批量就能干嘛，就能去试这个账号密码。😊，啊，明白吗？哎，就一个一个去试啊，有人说哎有没有字典什么，有没有字字典我给大家提供好不好啊？字典我给大家提供。😊，啊。

一个那么这个漏洞啊多钱3000块钱啊，这个漏洞如果在卖这个这个CQ注入的这个零队的话，得3000块啊，因为它是一个通用性漏洞，对吧？只要存在这样的一个页面，对吧？里面都会有这个CQ注入漏洞啊。

所以这个如果我们卖的话，可以卖到3000，但是我们没有卖好吗？兄弟们啊我们没有卖对？没有卖这个东西啊好，我们接下来再看第二个漏洞啊，第二个漏洞也是一张CNV的证书啊，这个漏洞它是一个弱口令，对吧？

也是后台有个账号密码啊，他的账号叫叉。然后我们直接进入到这个东西了。那么进入机之后啊，直接发现了他们集团的相关东西啊，比如说他们啊党委工作部人力资源部财务管啊。

采购系统、生产管理市场部技术部一公司一公司、二公司分公司，对不对？等相关东西的一些什么信息啊，里面包含了什么李哥在这给打码了，对不对啊？组织单位名称手机号对不对？序号管理者名称家庭住址等身份证号啊。

里面包含这些东西啊，就我们。😊，进了这个集团之后，发现了这些集团的所有人的身份证号、手机号等相关东西。这个漏洞也给了一张CNVD证书。好，有没有人知道CNVD是啥的？😡，有人入口令就是密码比较薄弱。

有没有人知道CV啥了，不知道是吧？好，不知道李哥给你看一个今天的一个文章，你们有没有听过衡水中学？😡，我我告诉你们的东西啊，叫什么，你们就叫输到了起跑线上，对吧？就是讲句那讲一句真心话，对不对？

就是输到起跑线，你真输输到起跑线，对不对？衡水中学大家听过没有？😡，哎，我给大家看下衡水中区的人啊。😊，来，我们看下衡水中学啊。衡水中学的衡水中学有一个公众号来，我们衡水中河北衡水中学，你们都不知道。

操这个这玩意叫什么？北大清华的基地啊，是个高中啊，里面可研就一一个班里60个人啊，58个人都能考上清华北大，对吧？就这样一个学校，对吧？很屌啊，之前你的这个学校里面做那些试卷，对不对？来。

我们看一下衡水中学在昨天对不对？发布了一个文章来，我给大家看这个文章啊，这个文章我们来看一下啊。😊，啊，是不是昨天来往下翻啊，看看来这个文章来。😊，太酷了。

衡水中学刘泽林荣获多个国家信息安全共享漏洞平台原创证明，就这个玩意儿看到没？这是干嘛的？就是他挖到了一个漏洞，交给了国家信息安全公防平台，然后拿了这三张证书。OK那么李哥刚才给你讲的是啥？😊。

这两个漏洞他也拿到了这两个证书。理解没啊？然后他这个小伙伴还挺屌，对吧？还获得了公安局啊等相关东学的一些通报。你们可以去看一下这个文章啊，这是衡水中学发的，对不对？刘泽英才高二呀，对不对？

高二人家都可以挖洞了，这就叫做什么差距，对不对？你大四了，还在啊打游戏呢啊，都毕业了还在考虑啊，我要干嘛呢啊，人家高中的时候就会挖洞就会拿奖项了，对不对？明白吗？这就叫差距，对的啊。

大二大二是不是啥都不懂对吧？讲真家话你都还不如一个高中生啊，原因什么原就是你们的这个消息太滞后了，对吧？那么这个同学他一定是什么？家庭条件好的，对吧？他家庭条件好，他才能知道网络安全啊，对不对？

家里都看家里如果父母不支持，他什么网络安全，对吧？天天就是。😊，语数英对不对，对不对啊？一些好学校，人家一边这些资源比较好，对吧？啊，OK来我们就不不说了啊。好，我们来看一下刚才给大家看这两个案例。

这个案例啊，CVD证书原创的啊，还有这张案例，对不对？也是CVD原创的，跟衡水中学的小伙伴拿到的是一模一样的啊，只不过它的漏洞类型不一样啊，但是证书都是一模一样的啊。刚第一个案例是我们我啊哇漏洞时候啊。

给到一个钱啊，一个奖金，对吧？好，那么这些东西挖洞都可以互多或号给你带来钱或者一个奖金这样的东西啊。那么接下来我们就来实操一下啊，我们就来看一下啊，关于账号密码都有哪些漏洞应该如何去挖啊。

接下来发车了啊，李哥把案例给你讲完了，为什么要给你讲案例啊，原就是让你觉得这个东西它是真实存在的，对不对？如果我只实操，你会觉得要这玩意有啥用，对不对啊，不是没啥用，是你不知道啊。😊，来。

我们来看一下啊，关于账号的密码漏洞有哪些啊，有用户枚举，就是刚才给大家看到哎枚举他的用户，对吧？第二个有弱口令，就是他的口令可能是他的密码，口令就是密码，密码可能是123456。

密码可能是ABC密码可能是什么键键盘前几位键盘后几位，对不对？这种常见的一些人类习惯的密码，叫做弱口令密码，还有个就是它的密码可能会泄露在了一些啊这个代码里面啊，被我们察觉到这些都是关于账号密码的漏洞。

那么关于账号密码漏洞，我们应该如何去挖啊，李哥在这里给大家演示一波，好不好？好，首先你要挖账号密码移洞啊，接下来要讲的就是一个什么实战的相关东西了啊，我们可以借助这个什么百度高级搜索。😊，啊。

在这里再给大家提醒一遍啊，非法挖洞不是没有授权挖洞是违法行为啊。😡，我在这里只给你演示，不给你挖啊，挖的时候我会用其他方法去挖啊。😡，好，百度高级搜索啊。我们搜一个什么呢？哎，比如我们搜一个后台管理。

后台管理一般都要账号密码才可以进他的后台，对不对？好，我们把它放在网页标题中，点击这个后台管理，百度一下。okK好，我们回到搜到很多后台管理。来，我们一一打开去看一下。😊，看看这些网站。

我们能不能去进行漏洞挖掘啊。

![](img/967e469aaa6fcf5de388e10a4f2294ed_1.png)

好，第一个这个系统好，在这里先提说一下兄弟们啊，我们先不考虑这个验证码。如果有这个图片验证码，短信验证码懂不懂？先不要考虑啊，我们因为我们现在还没有教图片验证码怎么绕短信验证码怎么绕。

我们先找一些没有验证码的一些平台。OK这个非常多，对不对？大家往下去找一找啊。😊。

![](img/967e469aaa6fcf5de388e10a4f2294ed_3.png)

哎，再往下找找啊，比如说。来，再往下这个页数稍微往后翻一翻啊，这哔哩哔哩后台管理系统啊，哔哩哔哩的这个后台应该哎这这不是这这个文章啊。😊，好，后台管理没有，不是讲后台登录。哎，我们搜到后台登录，哎。

后台登录一搜是不是搜出来很多了。来，我们一个一个打开，像这种对吧？我们先绕过，因为它有验证码，对不对？我们先找一些没有验证码的，这个没问题，这个东西可不可以搞，没有问题，可以搞。因为它们没有验证码。

对不对？我们就可以随便搞它啊，可以试它的密码。哎，比如说我们在这试一下A的密啊，密码123啊，点击登录。😊，啊，它提示用户名或密码错密，对不对啊，那么他那我就要一个试了，对不对？一个个去试好，这个可以。

对吧？好，再打开多打开几个，我们来看一下啊。😊，这个也不行啊，再打开这个这个。这个来这个。好，这个李哥就打开打开少打开几个啊。好，来，这个是不是也可以来，我们来看一下，你看手机号跟用户名啊。

叫我也不知道这是哪个网站，对不对？好，他需要你提供手机号，比如说我提供一个用户名O对B密码先随便输123点击登录。😊。



![](img/967e469aaa6fcf5de388e10a4f2294ed_5.png)

有反应吗？啊，还在反应中啊，那我们再要看下一个。啊，这不可能登进去了吧。哎，这里提示登录信息不正确，对不对？啊？没有关系，哎，这里扫码的对吧？哎，这里也有账号密码，对吧？

我们在这种网页里面去找会找到能有很多这种关于后台登录的这样一个东西啊，明白吗？我们都可以去测啊，那由于这个太多了，像这个也可以测。像像这个你看账号密码都写到这里啊，这个呢就属于新泄露啊，你直接点登录。

直接登进去啊，这个其实用户不存在是吧？啊，这个没有关系啊，好，那这里非常多，需要大家一个去排查，对不对？那李哥在这里给大家挑几个比较那个啥比较典型的案例，对不对？

因为我已经我在这个课就是我被这节课的时候，我用了差不多2小时，把这里全部每个后台都给你看了一遍啊，那么我整理出来两个比较有这样一个代表性的网站，对吧？给大家去瞅一眼啊。😊。



![](img/967e469aaa6fcf5de388e10a4f2294ed_7.png)

好，首先我们来看第一个网站啊。😊，好。来打开这个网站，你看这个网站，你只要打开了，对不对？它直接提示什么账号demo密码，123456。那这个漏洞叫什么？是不是就叫账号密码泄露漏洞，就是你不需要干嘛。

不需要改它的账号密码直接弹出来了，或者说直接写在了它的源代码里面。😡，对不对？来，我们说一下这个D。DEMO。



![](img/967e469aaa6fcf5de388e10a4f2294ed_9.png)

啊，这个搜不出来，我们只能F12去搜，对不对？好来，我们样式编辑器啊，我们在这个呃。😊，来，这里搜一下啊。ctrol shift将F搜一下啊，来DEMO。看到没？是不是直接搜出来了？😡。

看他的账号密码是不是就是在他这个网站的。GS语言里面账号密码给弹出来了，那你直接demo一下什么，登进去就可以了啊。DEMO密码多少？123456是不是直接点击登录？😡，看到没？

是不是直接登录他的网站了啊，并且他前台的博客地址也是能看到这是一个女孩子的博客，对不对啊？她可能自己写的安全意识比较差啊，她用的第三方的框架啊，这个有一些漏洞，对吧？啊，是个人的一些东西，对吧？啊。

包括他一些啊会员开单的一些地址，对吧？这些都是他自己搞的对吧？😊。

![](img/967e469aaa6fcf5de388e10a4f2294ed_11.png)

![](img/967e469aaa6fcf5de388e10a4f2294ed_12.png)

是不是啊啊也是说这个是不是用于演示的啊，不是用于演示的，这是他正正八经的后台数据是吧？每这个2023年是不是还有这个访问量呢，对吧？他的权限里面还有他的用户，他有两个用户，对不对？一个是。

一个是演示账号demo啊，个也是他的一个用户，包括这里有他的电子邮箱，对不对啊？这是他这个女孩的真正的一个东西吧？不是他假的啊，不是演示里面是有数据的，刚刚给你看了，这人家的数据，对不对啊。

人数据都是在里面了，对吧？啊，有人说这个东有没有用啊，这个东西没啥用啊，也没人没有人收这个东西啊，没有人收这个东西啊，这是我们讲了一个什么比较就是直观一个案例，什么案例呢？就是他这个账号密码直接泄露了。

对吧？好，那我们再看第二个案例啊，给大家找到一个案例这个案例叫一个用户枚举案例啊，😊。

![](img/967e469aaa6fcf5de388e10a4f2294ed_14.png)

来看这个案例叫新零售社团的一个这样的东西，对不对？好，这个社团也是我在网上搜的，对不对？好，我现在不知道他账户，也不知道他的密码，对不对？那我现在想要搞怎么搞，我先输all me啊，为什么李哥说哎。

李哥，你为什么要输all me？O因为all me是大家最常用的一个东西，对不对？就是你为什么。😊，就是中国人，对不对？张王李昭嘛，这些姓氏最多的对吧？像all的命一般是账号最多的，对不对？

你看我们输入all的命，在这里输入123，随便输，我们点击登录。

![](img/967e469aaa6fcf5de388e10a4f2294ed_16.png)

大家看一下这里提示什么东西。

![](img/967e469aaa6fcf5de388e10a4f2294ed_18.png)

来先看一下我输all的 me，我然后我输123，这里提示什么，是不是提示密码错误。好，那我在这里再输百里的名字。😡，百里好，我再输入123，点击登录。好，这里提示什么？啊，提什么？用户不存在或被禁用。

好，由此可以证明这个网站是不是存在一个用户枚举漏洞。那么我既然已经知道他叫min，那我就可以测他有没有demo，有没有test，对不对？哎。

都没有等这些相关账号testt2一2等相关这些人类比较符合人类习惯了，随手一个输的这样的一个账号，对吧？我知道这个账号之后呢，我是不是就紧接着可以去搞他的密码，一般demo的密码。

test的密码都比较简单，一输就进去了，对不对？好，这是一个新零售社区的对不对？好，那你现在想要知道他有多少个账号怎么办，哎，是不是要进行抓包，是不是要进行爆破好。

那接下来李哥就给你演示一下怎么抓包怎么搞不破，怎么去查看好不好？当然我现在不能直接拿这个网站演示，那就属于违法了，对不对？那李哥会打开自己本地的一个环境，对吧？给你去演示一下。

用我们刚才的BP去把这个环境给他。😊。

![](img/967e469aaa6fcf5de388e10a4f2294ed_20.png)

原封不动的浮现出来。

![](img/967e469aaa6fcf5de388e10a4f2294ed_22.png)

好，来，我们启动这个蓝后然，我们打开我们的BP，对不对？好。😊，把这些关掉啊。没事，这里就1000人，哎，人多眼杂嘛，对吧？哎，3W点皮。😊，啊，要是的话啊，你自己回家，你自己试去啊。😊，行不行啊？来。

我先把这个网站给它打开啊。😊，好，打开这个网站。打开网站啊。好，那么这个这个是什么东西啊？这是个什么东西啊？这是一个漏洞的靶场平台，对不对哈？那么这个漏洞靶场平台可能时说啊，李哥我不会安装没有关系啊。

一会儿呢我们会在那个课前笔记里面把这个靶场如何安装，会给你写到里面来，你只要去按照那个教程去安装就行了，对不对？好，那我们先点击这个暴力破解啊，这里有一个暴力破解啊，我们就以这里来充当账号跟密码，好吧？

假如说我们已经知道他要的密了，对不对？现在我们不知道它的密码，对不对？我们随便输个7777啊，然后怎么办呢？输入的密码的时候O兄弟们现在看一下怎么去做啊。好，先点击先把这个拦截关闭掉，对不对？

打开浏览器，输入你想要的东西，不要直接点击登录，对不对？先点击拦截啊，登录。好，那么这个时候数据包就会被拦截到这里面来，对不对？好，那拦截里面就包含了什么啊，我们要。😊。

登录的账号跟登录的密码是不是密码是不是77777啊？那一会儿只要便利这个777，我把77改改成123456789的很多100个对吧？试一遍啊，当然你用手势比较慢，我们要用这个BP去试。那怎么去试。好。

大家记住啊，首先把鼠标放到这个空白区域啊，右键鼠标右键，记住啊，是右键啊，右键，然后会弹出一个这样的东西，然后点击这个发送到 in出的这个东西里面，我说了 in出的是不是批量爆破，批量测试啊。

一定要把这个数据包发送到这个什么 in出的这个模块里面来。😊，好，然后我们右键发送in出的，然后这块变红，我们把这个电红点一下好吧？大家来看啊，那么这个就是音出的模块。好，那接下来怎么选啊。

我们先清除这个配load的啊，我们把这个777啊，这几个字，先给它用鼠标啊干嘛啊，给它圈出来，对不对？会不会圈哎，先圈出来，圈出来之后点击这个什么添加配漏的位置啊，一定要点击这个东西，对不对？

就是把这个T7给它标记上啊，我们要点击。😊，来点完之后可以看到这个77这一块，对不对？来。是不是被标记了，前后会用这个符号给它打上标记。那么一会儿我们的字典就会批量去改这里这里面的一些内容啊，这是标记。

对不对？标记把它标记住，对不对啊？然后我们点击什么点击这一块这个payload的。😊，啊，点这个配load的好，配load好，再然后干嘛呢？哎，我们选在这里面选择一个密码啊，比如这里有一些简单的密码啊。

它提供了这么多密码，对不对？😊，哎，是不是提供这么多密码？好，我们可以多选几个啊。😊，你看是不是有一些密码，哎，我们可以多选几个哎。😊，短文本哎，用户名对不对？可以多选几个OK然后干嘛呢？

然后直接点击开始攻击啊，那么这个东西呢也可以干嘛呢？也可以添加，就是你也可以有自己的一个密码字典。好，什么叫自己的密码字典呢？来给大家展示一下好吧，就是因为你的这个BP自带的这个字典，可能不强大。

对不对？那么李哥在这里给大家准备了什么一些啊我自己的一些字典哈，在工具里面是不是有个百里收集的这些字典啊，这里面包含了什么东西，大家看一下啊。😊，包含了这么多字典啊，有用户名，有账号。

有参数字典、密码字典，对不对？密码，你看有这么多啊，5000的1万的啊啊000的对吧？这里面都是常用的一些密码，看到吗？哎，就在里面写出来了，对不对？我们直接把这个导进去就可以了啊。如果大家想导入的话。

怎么导，哎，也教大家一下，对不对？😊，好，点击这个什么先把那我先把它删了，对不对？啊？清空好，点击这个从文件夹加载，对不对？啊，点击加载好，那么把你刚才的这个。😊，密码这个什么字典啊。选中啊。

找到这个密码啊，这里我们选择多少个？我们选择1000个，好吧，选1000个，对不对？点击确定。好，那这1000个密码就进来了哈。好，然后呢，我们点击什么开始攻击。😊，啊，看一下来。

你们看一下这边的这速度，来看下这个速度啊，快不快。😊，快不快？868900多了，对不对？1000多了，对不对？一共1340个啊。如果说你用手去测啊，完了，对不对？一共用时啊，也就不过几秒钟的时间。

对不对？我们已经测完了1000多个密码了。好，那么怎么证明哪个是登录成功的呢？哎，怎么证明是登录成功的呢？😊，来给大家演示一下啊。还是这句话。怎么证明是否登录成功呢？好，我们还是回到这刚才这个案例。

对吧？好，我们完回到这里ad me123点击登录。😊。

![](img/967e469aaa6fcf5de388e10a4f2294ed_24.png)

![](img/967e469aaa6fcf5de388e10a4f2294ed_25.png)

啊，他提示什么，密码错误。okK我们来说其他的。😡，啊，他提示啊用户名不存在。好，OK那怎么证明他成功了呢？如果用黑眼睛来看，如果针对于这个网站证明他成功的就是代表提示了密码错错误，对不对？

就代表这个用户是存在的，对不对？如果提示这个就代表这个用户不存在啊，那么在。这个BP里面怎么看啊，我们来看一下这个字的长度跟这个字的长度肯定是不一样的对吧？就是正确的跟错误的长度是不一样的。

错误的统一是这个长度，正确的统一是这个长度，对不对？比如这个长度是4位，这个长度是几位，1234567899位，对不对？所以说我们就可以看这个数据里面的返回的长度。如果长度是4位，就代表成功了。

长度是9位，代表就失败了，是不是哎，就这样可以去进行一个判断。同样我们在BP里面就可以看这个长度。😊。



![](img/967e469aaa6fcf5de388e10a4f2294ed_27.png)

来，我们来看一下。15111。这还有个多少？3588。来，我们来看下这个长度啊，151113508735111啊，底下全是111。所以你不用猜这个111肯定是错误的，对不对啊，这么多才111这么常啊。

这个3578是不是正确的。来，我们来点开看一下，看它的响应。是不是200okK啊，来看下它的渲染页面，看到没？这里提什么？Logging success。是不是登录成功？那么登录失败。

我们来看一下它的页面里面提示什么。user name or password word不存在啊，那我们再去看这个111啊，这个空。啊。

这个空也是提什么user name of password word不存在。对不对？那这个是成功的，它的长度是35087，这个是失败的，它的长度是35111，对不对？所以由这样长度。

我们就可以判断出来什么它是否成功，还是否失败，对吧？有人说哎，那后面还有呢，对吧？来，我们来看下后面的啊。啊，哎，放到最后。哎，没了是吧，没了啊，就这几个。是不是啊就这几个啊，就通过它的返回长度去看啊。

那那现在同学们使用方法，现在大家看会了没有？没有，就是听懂了没有？听懂了给李波扣个扣个一啊。刚才我们的这种漏洞啊，给你看到的那些漏洞，包括我们挖到的这漏洞，都是用这样的方法挖的。



![](img/967e469aaa6fcf5de388e10a4f2294ed_29.png)

把它先抓包勾选出用字典跑一下，抓包勾选住，用字典跑一下，抓包用勾选住用字典跑一下。包括UC这个80块钱漏洞，就是这样一模一样的挖出来的啊，包括刚才给大家看到一些案例，对吧？都是这样挖出来的啊。

没有什么高深的技巧。在这里要注意的是什么？就是字典平时去积累一下就可以了，对不对？那么今天你们能不能挖可以没有问题，你们打开百度搜索，对不对？在这里是可以搜什么后台登录后台管理啊，然后登录吧。

搜这些关于登录啊验证等相关的关键字，对吧？然后把它放到这个仅网页标题中选中这个框，百度一下，就能搜索出来很多很多登录页面，对不对？然后干嘛呢？啊，然后就可以一个个去找了。

看哪个网站会有相同的漏洞就可以了。好吧。那今天我们讲的是什么，讲的只是账号密码，对不对？并没有去讲什么，并没有去讲说哎李哥我没有我并没有去讲那个验证码，对吧？验证码名。😊，明天会讲对吧？

我们可以看到明天李哥是不是还给你准备了一个课，大家来看一下。😊。

![](img/967e469aaa6fcf5de388e10a4f2294ed_31.png)

明天我们讲的是什么漏洞来，就是说遇到这些验证码怎么办？手机验证码，8位三位对不对？我能爆破吗？我除了爆破，怎么去转样转发，怎么去进行为绑定认证，怎么去进行回显，对吧？怎么去进行什么短信轰炸，对吧？

这些漏洞我们会讲啊，不要着急，我们都是一个循序渐进的过程，好不？O那么在最后的最后再给大家说一下，因为我的刚才QQ到QQ盗号不是这样的啊，QQ盗号跟它的原理不一样。如果说你想学QQ的号。

后面我们专门可以我给你开节课，你看我能不能把你的号盗了，只要你敢扫码，我就可以盗你的号，好吧？没有问题，非常简单，你还不知道，对不对？我给你试试到我们公司的号，我跟你说我们公司100人。

我最起码可以保证我能到50个人的号。😊，因为因为什么人说啊你那么牛逼啊，因为我试过。😡，因为我真是你们不信是吧？好，不信记着，下次如果说我开到号客了，你实时关注啊，你看我能不能把大家的号。

当然我现在给你讲了，我说我能把你号盗了，你肯定说我不信。😊，不是你有防范意识就不行，对不对？你必须在一个不知不觉，没有任何防范意识下，对不对？把号盗了，这样才行，对吧？但是我跟你讲了，你就意思。

我给你点个啥，你不点，那你扫一啥，我不扫啊，那你干啥，我不干啊，那你谁来了都没有，对不对啊？等下次吧，等会我备好了，因为我之前在去年讲过一次啊。😡，这就是那个东西吧，哎有点弄起来有点复杂。

还要配合一些社工，配合一些这个二维码，对吧？还要配合一些话术，还要做一些图，对吧？要把假的给做成真的一样啊，就是那样骗啊，就是骗啊。好。😊。

