# CTF-Web历年考题精讲教程 从入门到精通 - P8：网鼎杯2020 玄武组 WEB题SSRFME解题 - 黑客入门101 - BV14YtkebEbY

大家好，我是安妮。今天我们。嗯。给大家做一个视频，这是我们的王顶梅全武组的SSI蜜这道题目的天0。那么我是我是安女儿，那么。呃，这道棋挺难的，当时的话大概有不到20支队伍可以解出来的。啊。

那么首先呢我们来访问一下我的网站。

![](img/286cec3d6ec98a2c7038f3d880888523_1.png)

我的网站啊是一个。

![](img/286cec3d6ec98a2c7038f3d880888523_3.png)

做一个培训的做培训的啊，价格价格现在的话是2300啊2300。那么呢这里面啊有差不多有。2323章的内容23章内容大家可以过来学习一下啊，感兴趣的可以过来学习。啊，这里面都比较详细的比较详细的。

还有这里面还有5个项目，5个项目。这5个项目的话，假如你做完了，你可以到任何一家公司里面上班，都说你有什么问题啊。那么推荐作业呢啊我们都我们都会推荐啊，只要你有能力啊，通过通过我们的审核。

我们都会安排你到。回来公司都上班。啊。啊，大家假如感兴趣的话，可以过来。啊，我过来了解，或者是过来学习。好了，我们先到这里了，回到主题。不要读题啊，所以这道题是怎么解的？这道题的话是首先。

首先啊要过绕过这道题给大家先讲一下思路吧。这道题挺难的啊。首先呢你要要过这个条件判断，访问访问这个目录，就是网站目录下的这个呃文件。这个文件的话会有那点密码。啊，利用这个啊。SSFF吧，这个还有。

这个谁也来打这个ra。还要还要用到readis读同漏洞L反弹下了。还有。挺难啊，条件也的话也是比较很苛刻的。那么这里他一因为这里的话，它是一个环境来搭店啊，它可能跟跟打比赛的时候，他有点出入啊。

但是这个出入的话可能就是权线上的出入啊，基本上和它一样的。好了，那么当时的代码呢，我就已经拿下来了啊，拿下来了。我们。我们今天有靶场，有把机。然后大家想如想要这个靶机的话，可以问我要，可以问我要。

我都是可以免费的共享出来啊。那么首先啊首先。首先呢我们来访问一下这个网站，对吧？这个晚站就是。当时的A些代码当些代码。那这里给大家分析一下啊，再给大家分析一下。这里首先呢首先啊他判断是否有11过来。

有11过来的话就是。要做什么？在这里的话咬牙不入空的话就会。来到这个函数来到这个函数，这个函数去哪里？这个函数的话就会来到这里。然后这里之后啊，它这里有个URL检测，有没有URL检测啊，大家看一下。

这里的话是获取ho，就是获取这里的内容。原后这里我们。我们传递啊11。天啊。然后说这样子。对吧这里他会获取到这里的内容啊，还到这里的内容完后放到他IB。在这里可以播的话。谁这里呀。这里因查。

范围能的范围。大家看一下，这里找一个返回抽的话。打约。这里的话检查套IP的话。这里假如它输出出来的话，下面这个地方是不会执行的。所以的话这里我们要过它，我们要要过这这一道，要过这个条件。

就上面这个条件要要过它，还有。这里吧这里面的话就会去什么呀？这里放进剧柄之后，或几过几天的过几天的。好了，按那这边的话，他还会进行这个判断。而进行这个C判断。啊，一也会判断。那么这个怎么要。

最主要是要这个地方，最主要要这个地方就可以了。要到这个地方的话，后面的话都还很简单的。那这个得怎么样啊？首先呢这边我们可以看一下，这里的话是17。0。0。1，还有内网的。内网的都不行啊，内网的都不行。

对吧。那我们可以用这个0。0。0。0。对吧再看一下，他要我们访问。访问这个文件啊，等下我们访问这个文件。那么这里的文件我们因为呢我们的目录它插在ISSRF里面啊。那么当时的环境是音变环境啊。

然后现在的话，因为啊因为我们这里还有其他的爬槽，这里有PR爬查，我就反它放到二层目录啊，都一样的。大家访问一下这里就好了。这里的话就会访问到这个页面啊，再看这里假如这边呢你直接访问就不行了，再看一下。

这里直接访问就不行了。因为它这里有个本地的。本地的验证啊。有个本地的验证，你这边看不到的。所以你要通过通过这里啊判断它是127的0。0。1，就本地的，它才能打开这个源代码，用这个函数来打开源代码。

我们就可以看到这个源代码了。好，大家看一下这里有什么？这里有个readd要忘SSM63P9对吧？这边的话就是一个readd密码。所以呢我们要访问访问什么访问它的。啊，63啤9有没有？法问下的6379。

有没有。真的有没有read好，我们。反问一下。63D9。6379。啊，这里。再稍等一下，这里的话反正可能有点慢。我拿到这边来访问你。好，大家看这里的话应该是可以访问得到的。那么我们用其他协议。

这里的话有有这个。DICT协议我们用这个协议来访问看一下。对吧大家看到这个是肯定是可以大家看到这里肯定是有有什么有这个re的，对吧？用这个BICT的协议来访问，我们也看到它是有反应信息的。

因为大家看到这里有个什么呀，都AUTH那这里的话它肯定就是一个。呃。肯定是要登录认证的，登录认证的。而且这个redies它只能本地访问啊，不能从我们外部去访问的。

对吧所以呢我们只我们只能结合RSSRF的这个。这个。啊。这个配合我们的一些协议来达到。来打这个readding。好了，那这边怎么来打啊，对吧？怎么来打？那首先这边的话呢，我们先来打开。



![](img/286cec3d6ec98a2c7038f3d880888523_5.png)

嗯，这里的话。好了。我们先的。先来用到这个条本。对吧这里有个脚本，这个脚本的话呢大家可以到网上去找这个用来做这个。用来做这个。



![](img/286cec3d6ec98a2c7038f3d880888523_7.png)

呃，权限获取的。这里用到的漏洞是组成的这个组层漏洞啊REC其中REC。远程。就行命令的。这个漏洞啊来打到这个小。好了，那首先这这两步啊这两步呢我们已经。这两部门已好了。那么接下来的话呢，我们要。



![](img/286cec3d6ec98a2c7038f3d880888523_9.png)

要在本地啊。首先要爬起身来运行一下这个条本。好，下边有杠H。好。那么还有一个做什么？还有照相机。这里的话是6379。637。好了。那这里啊我们假如我们这个readd的话，它可以远程访问了。

我们直接填在这边填写他的IP地址就可以了。因为呢现在它不行，先不现在它不行，所以的话呢我们。

![](img/286cec3d6ec98a2c7038f3d880888523_11.png)

![](img/286cec3d6ec98a2c7038f3d880888523_12.png)

![](img/286cec3d6ec98a2c7038f3d880888523_13.png)

需要用一些协议用一些协议。同步啊同步我们的。

![](img/286cec3d6ec98a2c7038f3d880888523_15.png)

伪叫ready是的。数据啊。好。其他的原理是什么？他的原理就是嗯。它原理的话就是把这个一他P点SO同步到我们的。同步到我们的ready上面，然后进进行这个命令执行。他的原理就是这样的，具于怎么来做。

大家可以看一下我怎么来做的。那这边。这边的话我们先127。0。0。1。啊，这里我们。当H有了吧，没后。这里ho的话呢，我们不能写远程的。因为呢远程的话，它的IP是被开放的，所以的话这边我们要用本地的。

这里的话。那这里的IP可以这里的端口可以不写了啊，默然的话就是6379。那么第二个的话就是我们的这台IP。啊这里是11145啊。好了，这里的话我们给他一个 IDD。那这里的话我们。也可以不给他的。

不给他这个。还不给他这个。二端口长部位的话是2100，大概2100。那这边呢我们这样的话就可以了。那，这里还有。啊，这样就可以了吧。好，我们。所你聊翻未。你ose。这应该写了交了一个。然后好了。

这样就可以了。大家看啊，现在的话呢我们。等下。他会像我们这个来。做这个请求啊做这个请求。对吧。好了，那么现在的话这样就可以了。那我们。



![](img/286cec3d6ec98a2c7038f3d880888523_17.png)

来到。啊。

![](img/286cec3d6ec98a2c7038f3d880888523_19.png)

这里的话需要一些协议啊。首先呢这里的话一些设置我们的目录。那这里的。这里的话是什么呀？我给大家分析一下啊。



![](img/286cec3d6ec98a2c7038f3d880888523_21.png)

我来打开这个不吧，给大家分析一下这些语句有啥意这啥什么意思啊？好了，给大家分析一下这个语句。首先这个语句啊，大家看可以用抵扣11，大家看一下这里这里是什么呀？大看再再抵扣一下。对吧他这边的话它是万堂。

那么在在这个red里面啊，它换行的话是用这个。啊，先我们这个0。连 a。0D0AR申行这个。这换行了，大家看他这边的话需要经过一一个编码，还要经过一次编码。还有警问这边吗？对吧来看一下这里的。

首先这边的话是。是什么呀？用这个。呃，各个协议啊来登录它登录它之后呢，他设置这个目录啊，这个目录。那当时当时王品飞的目录啊，他网站目录他是不能行的。所以的话他我我们先测置查目录，测试完目录之后呢。

我们进行退除啊，这里的话就是他的一个意思。那所以我们。

![](img/286cec3d6ec98a2c7038f3d880888523_23.png)

在这边的话呢，我们可以先设置一下它的目录。

![](img/286cec3d6ec98a2c7038f3d880888523_25.png)

好，对吧？这里是OK的，OK就可以了。

![](img/286cec3d6ec98a2c7038f3d880888523_27.png)

这就是这个目录有什么用呢？就是说当时我们我们同步这个。

![](img/286cec3d6ec98a2c7038f3d880888523_29.png)

SO文件的时候，它就可以导入到前人屏幕录上，导出到其人屏幕录上了啊。

![](img/286cec3d6ec98a2c7038f3d880888523_31.png)

好啦。这边呢我们。

![](img/286cec3d6ec98a2c7038f3d880888523_33.png)

接下来的话呢，我们要做什么操作啊？这里的话呢我们把这个IP地址改一下，这个IP的话应该是个。我们看一下我们这个服务器啊。这个主服务器啊组头啊let。这个是从我们的卡利是主，所以的话呢我们。

的IP的话就是我们的要素。所以呢我们。要在这里更改一下它的。带俾啲。啊，这里的。好，这里的这里12112100的话，就插的这个端口。这里的话改改这两个就可以了。好，这里呢我们。



![](img/286cec3d6ec98a2c7038f3d880888523_35.png)

呃，设置差的EWBSO。还有同步啊。那么这里的话我也可以拿到这边来给大家看一下它是什它是什么意思啊。

![](img/286cec3d6ec98a2c7038f3d880888523_37.png)

![](img/286cec3d6ec98a2c7038f3d880888523_38.png)

再家看一下这里面。啊，所以说这个地方这边登录之后啊，我们设计一下这个。啊，这个文件啊，然后把它从这里的话是设置重复了。



![](img/286cec3d6ec98a2c7038f3d880888523_40.png)

在重复。这是我们的。主的reds服务器啊是145，然后它的端口是2100NC统。好了，这里的话就可以了。



![](img/286cec3d6ec98a2c7038f3d880888523_42.png)

然后把这里。把它同样的来到这边来执行。好，再按一下，按一下的话就会出现这个。这表示的话已经是成复成功。好了，那么接下来的话，我们这边呢。



![](img/286cec3d6ec98a2c7038f3d880888523_44.png)

我们这边也要进行这个ent。En头。end之后啊，他这边。他这个主服务器会向我们客户端发送一些信息啊，这边的话呢我们也要。我们也要按这个安全键啊，不然的话它这边可能会卡住啊，可能会卡住。好。

这边我们confire configurefi现。

![](img/286cec3d6ec98a2c7038f3d880888523_46.png)

第P票这里的话我们已经做了这个操作了啊。对吧我们做已经做了一个操作了。

![](img/286cec3d6ec98a2c7038f3d880888523_48.png)

那么呢我们。这边你要按这个ent键。

![](img/286cec3d6ec98a2c7038f3d880888523_50.png)

![](img/286cec3d6ec98a2c7038f3d880888523_51.png)

好了，这边他会进行这个导入啊，这边的话呢，我们也同认了。

![](img/286cec3d6ec98a2c7038f3d880888523_53.png)

抖咗咁冇啊。阿豆都冇得。好，这里表示OK那就OK了。

![](img/286cec3d6ec98a2c7038f3d880888523_55.png)

那么再来一下这个关闭这个主头。关闭这个主窗啊，这边的话呢我们也看一下。啊是不是就关闭重中。啊，对吧？也是关闭总通，所以的话这边也是要关闭这个主通的。



![](img/286cec3d6ec98a2c7038f3d880888523_57.png)

好，这里也是OK了。那么接下来的话呢，我们要做什么呢？

![](img/286cec3d6ec98a2c7038f3d880888523_59.png)

那么我们看一下。这面的话他会导出。

![](img/286cec3d6ec98a2c7038f3d880888523_61.png)

WDBpro所以的话这边也要导入。好了。这边应该打出它了，导入这个数据库了啊。RDB很多接下来的话呢，我们可以反弹。



![](img/286cec3d6ec98a2c7038f3d880888523_63.png)

开玩笑。这里的板弹胶的话也是。

![](img/286cec3d6ec98a2c7038f3d880888523_65.png)

下新进行修改啊，我们。先来监清一下，这里的端口是666啊。那么这边的话呢，我们也。要做一下这个。电时加 l。666。这里要反，这边的话就要监听了。然后我们执行下面这条命令的时候啊，它会反弹过来。



![](img/286cec3d6ec98a2c7038f3d880888523_67.png)

这里的话应该是14。

![](img/286cec3d6ec98a2c7038f3d880888523_69.png)

呃，应该是145，然后这边的话重新重新来就行。

![](img/286cec3d6ec98a2c7038f3d880888523_71.png)

好了。这边的话呢我们看一下。看一现在打回球会做什么，要把费。再去执行。啊会执行这个，然后删除它对吧？

![](img/286cec3d6ec98a2c7038f3d880888523_73.png)

我们来看一下。好，大家看到这边的话卡住了，就表示反弹弹功了。

![](img/286cec3d6ec98a2c7038f3d880888523_75.png)

我们来看我们来看一下。这里面的对吧？这边的话已经反弹成功了，我们看一下一D。好了，接下来的话呢我们切换一下。啊，可议T会。好了，对吧。太好了，看一下我们的IP。14144啊，这是我们的readd服务器。

对吧？看不下来的话，那我们来list。好，历史这个跟目录，然后呢我们就可以做什么了。哦。

![](img/286cec3d6ec98a2c7038f3d880888523_77.png)

打开这个文件啊，或者是我们先看一下它是不是一个目录啊这个文件。听嘛。大家看一下这里的。这里的。好的目录。那这边。再看到他这个文件啊，所以的话我们先直接直接查看就可以了。哦，这里的话他应该在看。好。

那最终的话就个flag的话就这样的。但这这个flag的话就是我自己写的啊。那当时的话肯定肯定不是这样的。好了，那这就是这个。呃，屏幕的一个。电气眼。先不信息啊。那么这里有什么不懂的，大家可以私聊我。



![](img/286cec3d6ec98a2c7038f3d880888523_79.png)

因为这个地方的话可能大家有有点不理解啊，这里的话我没有讲清楚。这里有个地方就是这里有啥用，这里有什么用？其实我们这边啊。我们这边大家看是访问这个17。0。1的，因为呢这边我们不是一个read服务器。

我们只是天气啊。这个脚本的话需要讲这个脚本呢，它需要需要你传入1个IIP进去的。你不传入的话，它就是失效的失效的。那么这边我的化是江听这个江津这个6379的化就是。仲才这里生效啊刚才这里生效。

而且我们这边的话，我们可以看到它这个readdis服务器，它像我们客户端会发送什么，在发送这些数据啊。帮的这些数据，那这种的话也是一种协议啊，也是一种协议啊。那原来的话这个脚本是。

原来这个脚本是怎么样的？就是这里填写你远程的rediesredies的这个IP地址然后。重步SO文件E他BSO文件然后执行命令的。那现在的话就是我们这边的话作为一个祝福。



![](img/286cec3d6ec98a2c7038f3d880888523_81.png)

![](img/286cec3d6ec98a2c7038f3d880888523_82.png)

register registerister这个主服务器啊，要我们用这个ISSIF啊。ISF作为一个这台144利用这个。SSF的这个漏洞啊来重步啊，重步我们的这个服务器啊，把这个。



![](img/286cec3d6ec98a2c7038f3d880888523_84.png)

把这个E叉BSO文件啊重步到我们这个ge里面，然后再进行再执行反弹命令反弹命令。所以的话我们就看到这个效果了。



![](img/286cec3d6ec98a2c7038f3d880888523_86.png)

![](img/286cec3d6ec98a2c7038f3d880888523_87.png)

吓。那么可以看到我们的天笔目录，有一个。有1个E叉BSO这个文件啊，大家看这可以看得到的。啊。

![](img/286cec3d6ec98a2c7038f3d880888523_89.png)

然后他的解析的话就是这样子。也就是这样子，大家就是说想要这个环境的话，可以联系我，可以加上我的这个微这个微信号啊，可以加上我们这个微信号。那么需要培训的话，也可以呃来联系我来。



![](img/286cec3d6ec98a2c7038f3d880888523_91.png)

然后联系我，我们都是比较质量比较高的一些培训啊。

![](img/286cec3d6ec98a2c7038f3d880888523_93.png)

说的价格也不是特别贵，23002300。好了，那么我们今天的课程就到这里，有什么不懂的可以私聊我。拜拜。



![](img/286cec3d6ec98a2c7038f3d880888523_95.png)