#Try Flask
###About Flask
>官方網站： [Flask](http://flask.pocoo.org/docs/0.11/)<br>
>#### <ol><li>What is micro:<br><ul><li>Flask 是一个微框架（Micro framework）</li><br><li>The “micro” in microframework means Flask aims to keep the core simple but extensible. </li><br><li>Flask won’t make many decisions for you, such as what database to use. Instead, Flask supports extensions to add such functionality to your application as if it was implemented in Flask itself. </li><br></ul></li><br><li>Flask VS Django:<br><br><ul><li>Django和Flask是GitHub上star数量最多的2个Python web框架。</li><br>  <li>Flask:<br>  <ul><li>Flask确实很“轻”，不愧是Micro Framework，从Django转向Flask的开发者一定会如此感慨，除非二者均为深入使用过</li><br>  <li>Flask自由、灵活，可扩展性强，第三方库的选择面广，开发时可以结合自己最喜欢用的轮子，也能结合最流行最强大的Python库</li><br> <li>非常适用于小型网站,入门简单，即便没有多少web开发经验，也能很快做出网站</li><br>  <li>非常适用于开发web服务的API</li><br>  <li>开发大型网站无压力，但代码架构需要自己设计，开发成本取决于开发者的能力和经验</li><br>  <li>各方面性能均等于或优于Django</li><br>  <li>Flask与关系型数据库的配合使用不弱于Django，而其与NoSQL数据库的配合远远优于Django</li><br>  <li>Flask比Django更加Pythonic，与Python的philosophy更加吻合</li><br></ul>  </li><br> <li>Django:</li><br><ul> <li>Django太重了，除了web框架，自带ORM和模板引擎，灵活和自由度不够高</li><br> <li>Django能开发小应用，但总会有“杀鸡焉用牛刀”的感觉</li><br> <li>Django的自带ORM非常优秀，综合评价略高于SQLAlchemy</li><br> <li>Django自带的模板引擎简单好用，但其强大程度和综合评价略低于Jinja</li><br> <li>Django自带ORM也使Django与关系型数据库耦合度过高，如果想使用MongoDB等NoSQL数据，需要选取合适的第三方库，且总感觉Django+SQL才是天生一对的搭配，Django+NoSQL砍掉了Django的半壁江山</li><br>  <li>Django是Python web框架的先驱，用户多，第三方库最丰富，最好的Python库，如果不能直接用到Django中，也一定能找到与之对应的移植</li><br> </ul><br>  </ul></li></ol>
###Windows下Python+Flask環境配置
>參考教學:  [http://atelier-wini.blogspot.tw/2013/03/python-flask-2.html](http://atelier-wini.blogspot.tw/2013/03/python-flask-2.html)<br>
>官方網站:  [http://flask.pocoo.org/docs/0.11/installation/#windows-easy-install](http://flask.pocoo.org/docs/0.11/installation/#windows-easy-install)<br>
##
###命令提示元
>安裝好python 和 pip 之後，需要安裝Virtualenv。
>###<ul>What is virturalenv
>**virtualenv 也是一個 Python 套件，可以讓你建立、模擬不同情況下的工作環境**。比如說你可能會有一個工作環境是需要C程式的第一版，而另一個工作環境需要第二版，那你就可以建立兩種不同的虛擬工作環境（類似虛擬機器），這可以避免碰上太多不必要的變數，或是製造你需要的變數，來測試你寫的程式是否運作正常。<br>
>##
>安裝virtualenv<br><Br>
>`sudo pip install virtualenv`
>##
>測試virtualenv是否可以正常運作<br><br>
>`mkdir newproject`<br>`cd newproject`<br>`virtualenv venv`<br><br>
>上述是建立了一個newproject的資料夾，然後把工作目錄切到newproject的路徑下，最後開啓虛擬的工作環境。需要輸入以下：<br><br>
>`ven\scripts\activate` //for windows<br><br>
>`. ven/bin/activate`//for Mac OS x and Linux<br><br>
>##
>啓用后，終端機會變成以 Venv 開頭，這就是正在使用虛擬工作環境的意思。
>##
>如果要離開虛擬工作環境的話（記得目錄要切到project資料夾）<br><br>
>`venv\scripts\deactivate` //for Windows<br><br>
>`. venv/bin/deacitvate` //for MAC OS X /LINUX<BR><BR>
>##
