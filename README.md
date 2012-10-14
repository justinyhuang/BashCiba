BashCiba
========

**_A bash interface to get English&lt;->Chinese translation based on www.iciba.com_**

BashCiba is a little tool helps to translate words between Chinese and English, in your bash environment.  
With the tool you could get translations without leaving your working environment.  
Simply type:

    dict <word>
and you will get the translation.

Example:

English -> Chinese

    $ dict hello
       
    1.  CONVENTION   惯用语
    哈罗;你好 You say ' Hello ' to someone when you meet them. ;
    【语用信息】：formulae
    Hello, Trish...   你好，特里茜。
    Do you want to pop your head in and say hallo to my girlfriend?   你要不要进来和我女友打个招呼？   Hello is also a
    noun.
    The salesperson greeted me with a warm hello .   售货员热情地和我打招呼。

    2.  CONVENTION   惯用语
    （打电话时的招呼语）喂 You say ' Hello ' to someone at the beginning of a telephone conversation, either when you
    answer the phone or before you give your name or say why you are phoning. ;
    【语用信息】：formulae
    A moment later, Cohen picked up the phone. 'Hello?'   过了一会儿，科恩接起电话。“喂？”
    Hallo, may I speak to Frank, please.   喂，我找弗兰克。

    3.  CONVENTION   惯用语
    （用于引起别人注意）喂 You can call ' hello ' to attract someone's attention. ;
    She could see the open door of a departmental office. 'Hello! Excuse me. This is the department of French, isn't
    it?'...   她看到一个系办公室的门开着。“喂！请问，这是法语系，对吗？”
    Very softly, she called out: 'Hallo? Who's there?'   她轻声细气喊道：“喂？有人吗？”'

    $ dict "this is mike, i come from america"
    这是麦克，我从美国来

Chinese -> English

    $ dict 我喜欢你
    1. I Like You

    41. Good For You 为你好  
    42. I Like You  我喜欢你   
    43. You're A Winner 你是赢家
    http://wwww.yzjy.com.cn/blog/u/naicheng/archives/2007/4986.html - 基于131个网页

    2. I Love You
    736 I ll CKBC 梦幻篮球 01－02  737 I Love You  我喜欢你 ！  738 I my me 青春草莓蛋 01－13
    http://post.baidu.com/f?kz=210094409 - 基于35个网页

    3. ILikeYou
    41.GoodForYou为你好  
    42. ILikeYou 我喜欢你   43.You’reAWinner你是赢家
    http://kuailedefeifei.127.blog.163.com/blog/static/437786842008926113427127/ - 基于18个网页

    4. GET READY
    GET READY 加油哦   GET READY 我喜欢你   READY GO！握紧手
    http://zhidao.baidu.com/question/63113515.html - 基于9个网页

    $ dict "这个工具很小巧，也挺好用的"
    This tool is very small, and very good use

BashCiba is based on python so you will need to have Python(2.7 and above) installed on your machine.

Enjoy =)
