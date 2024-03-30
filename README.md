<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>菜鸟教程(runoob.com)</title>
<style>
* {
    box-sizing: border-box;
    }
    
    body {
    font-family: Arial;
    padding: 10px;
    background: #f1f1f1;
    }
    
    /* 头部标题 */
    .header {
    padding: 30px;
    text-align: center;
    background-image: url(https://pic3.zhimg.com/v2-9b6d82e2c5cb4d289975d6dd9e5336a6_r.jpg);
    background-repeat: no-repeat;
    }
    
    .header h1 {
    font-size: 50px;
    }
    
    /* 导航条 */
    .topnav {
    overflow: hidden;
    background-color: #333;
    }
    
    /* 导航条链接 */
    .topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    }
    
    /* 链接颜色修改 */
    .topnav a:hover {
    background-color: #ddd;
    color: black;
    }
    
    /* 创建两列 */
    /* Left column */
    .leftcolumn {   
    float: left;
    width: 75%;
    }
    
    /* 右侧栏 */
    .rightcolumn {
    float: left;
    width: 25%;
    background-color: #f1f1f1;
    padding-left: 20px;
    }
    
    /* 图像部分 */
    .fakeimg1 {
        background-image: url(https://picx.zhimg.com/80/33cf1daabd4a20887a76967249c59411_1440w.webp?source=1def8aca);
    background-color: #aaa;
    width: 100%;
    padding: 20px;
    }
    .fakeimg2 {
        background-image: url(https://bkimg.cdn.bcebos.com/pic/cf1b9d16fdfaaf51f3de71a33e1d83eef01f3a29ccdf?x-bce-process=image/format,f_auto/resize,m_lfit,limit_1,w_440);
    background-color: #aaa;
    width: 100%;
    padding: 20px;
    }
    .fakeimg3 {
        background-image: url(https://img0.baidu.com/it/u=1403141158,984231711&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=549) ;
        background-size: 200px;
        background-repeat: no-repeat;
    background-color: #aaa;
    width: 100%;
    padding: 20px;
    }
    .fakeimg4 {
        background-image: url();
    background-color: #aaa;
    width: 100%;
    padding: 20px;
    }
    .fakeimg5 {
        background-image: url();
    background-color: #aaa;
    width: 100%;
    padding: 20px;
    }
    .fakeimg6 {
        background-image: url(https://imagepphcloud.thepaper.cn/pph/image/98/834/59.gif);
    background-repeat: no-repeat;
    width: 100%;
    padding: 20px;
    }
    /* 文章卡片效果 */
    .card {
    background-color: white;
    padding: 20px;
    margin-top: 20px;
    }
    .card1 {
    background-color: white;
    padding: 20px;
    margin-top: 20px;
    background-image: url(https://img0.baidu.com/it/u=1403141158,984231711&fm=253&fmt=auto&app=138&f=JPEG?w=500&h=549) ;
    }
    
    /* 列后面清除浮动 */
    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    
    /* 底部 */
    .footer {
    padding: 20px;
    text-align: center;
    background: #ddd;
    margin-top: 20px;
    }
    
    /* 响应式布局 - 屏幕尺寸小于 800px 时，两列布局改为上下布局 */
    @media screen and (max-width: 800px) {
    .leftcolumn, .rightcolumn {   
        width: 100%;
        padding: 0;
    }
    }
    
    /* 响应式布局 -屏幕尺寸小于 400px 时，导航等布局改为上下布局 */
    @media screen and (max-width: 400px) {
    .topnav a {
        float: none;
        width: 100%;
    }
    }
    </style>
    </head>
    <body>

    <div class="header">
    <h1 style="color: brown;font-family: 幼圆;">保定驴肉火烧</h1>
    <p>天上龙肉地下驴肉</p>
    </div>

    <div class="topnav">
    <a href="#">历史渊源</a>
    <a href="#">营养价值</a>
    <a href="#">传统做法</a>
    <a href="#" style="float:right">相关门店</a>
    </div>

    <div class="row">
    <div class="leftcolumn">
        <div class="card">
        <h2>保定的圆驴肉火烧好吃还是河间的方驴肉火烧好吃？</h2>
        <h5>2015.8.4</h5>
        <div class="fakeimg1" style="height:200px;"></div>
        <p>首先，这两种火烧最直观的区别就是它们的外形不同。保定的驴肉火烧是圆形的，而河间的驴肉火烧则是长方形的。这种区别源于它们的制作方法不同。保定的火烧是将面团抹上油后揉成小圆球状，压b再进行烙制，所以火烧的形状是圆的。而河间的火烧则是将面团抹上油后擀成长方形片，然后进行左右两次对折，用面杖擀薄后再进行烙制，所以火烧的形状是方的。</p>
        <p>其次，这两种火烧的驴肉也有所不同。保定火烧所使用的是酱驴肉，带有浓郁老汤卤汁的独特风味。而河间火烧所使用的是卤驴肉，加入火烧时是凉的。因此，相比之下，保定驴肉火烧更加注重在热的状态下食用。无论是保定火烧还是河间火烧，它们都有着酥脆的外皮和浓郁的香味，令人回味无穷。以上就是我对河北保定驴肉火烧的详细介绍，希望能够为大家带来更深入的了解。</p>
        </div>
        <div class="card">
        <h2>为了那口驴肉火烧，我愿意专门跑一趟保定</h2>
        <h5>2020.11.14</h5>
        <div class="fakeimg6" style="height:200px;"></div>
        <p>你可能还不知道，在河北，保定其实是一座因美食而著名的城市。甚至有一种说法，保定菜基本能代表河北菜。

            美食，才是保定百姓的第一需求。
            
            而保定人最爱的，还是那一口驴肉火烧。
            十个保定人

            十一个是驴瘾患者
            
            “天上龙肉，地上驴肉。”
            
            万万没想到，如此不常见的食材，也逃不开“没有一头驴能走出河北”的命运。
            
            这个河北出品的美食大IP，不仅辐射了华北地区的街头巷尾，在北京于店铺数量上打败了煎饼、包子、肉夹馍。
            
            还频频亮相于各大电影、相声，得到了冯巩、郭德纲、于谦等一众大咖的拥护。
            
            在驴肉火烧中，也是分门别派的，最为人所知的就是保定派和河间派。</p>
        <p>保定的驴肉火烧还必须得趁热吃，甩开腮帮子，撩起后槽牙，大快朵颐。

            肉香而不柴，酥软适口，当老汤汁和油顺着你的嘴角滴下来时，你的脑子里只能剩下一个“爽”字。
        <br>
        “天上龙肉，地上驴肉。”

        万万没想到，如此不常见的食材，也逃不开“没有一头驴能走出河北”的命运。
        
        这个河北出品的美食大IP，不仅辐射了华北地区的街头巷尾，在北京于店铺数量上打败了煎饼、包子、肉夹馍。
        
        还频频亮相于各大电影、相声，得到了冯巩、郭德纲、于谦等一众大咖的拥护。
        
        在驴肉火烧中，也是分门别派的，最为人所知的就是保定派和河间派。<br>
        保定驴肉火烧吃的就是那种驴肉特有的滋味原味，只有当地人做的最正宗，当天煮肉当天卖，各家还有煮肉的秘方。你想要照葫芦画瓢，那可不行。

        一口正宗的驴肉火烧就是保定人的命根，他们的每一天都要从驴肉火烧开始，一天不吃瘆得慌。<br>
        保定的驴肉火烧很是讲究。驴肉得选太行驴，只用老汤卤制，大火攻，小火焖，一共20多道工序、近20个小时的烹制，才能使老汤的滋味完全渗入驴肉。

        火烧也得做得有层次，把控好和面力道的大小和水的多少，那还只是基础。<br>
        等两面烤至八分熟后，将成型的火烧以更高温的非明火继续烘烤，就会形成一层酥脆的外皮，圆饼的肚子也鼓胀起来，外脆里嫩，香酥可口。

        有趣的是，每个保定火烧都会有印章加持，每一个都是独特的店家图腾。<br>
        做的时候捞出一块肉，肋板，蹄筋，拿大刀剁碎。有些人爱吃肥一点的，加上一小块肥肉，用刀平放按住一抹，油汁渗到了肉里面。

        再拿勺子舀上半勺老汤浇在肉上，然后拿一个烫手的火烧皮切开，在火烧的两侧涂抹上驴肉，就大功告成了。</p>
        </div>
    </div>
    <div class="rightcolumn">
        <div class="card">
        <h2>关于保定</h2>
        <div class="fakeimg2" style="height:100px;"></div>
        <p>保定市，河北省辖地级市，国务院批复确定的京津冀地区中心城市之一。 保定市位于河北省中部偏西，太行山东麓，冀中平原西部，地势由西北向东南倾斜。地貌分为山区和平原两大类；东接雄安新区，东南邻沧州市，南接衡水市，西南连石家庄市，西靠山西省，西北与山西省及张家口市交界，北邻北京市，东北与廊坊市毗邻。保定地处京津石金三角，距北京140千米，距天津145千米，距石家庄125千米，总面积1.93万平方千米（不含雄安新区及定州）。截至2022年末，保定市辖5个区、15个县（3个县由雄安新区托管），代管4个县级市（1个市为省直管试点），常住人口914.4万（不含雄安新区及定州）。</p>
        </div>
        <div class="card1">
        <h3></h3>
        <p><br><br><br><br><br></p>
        </div>
        <div class="card">
        <h3>制作工艺</h3>
        <p>驴肉火烧所用的面为死面，店主揉好面后，取适量揉成小馒头一样的面团，然后用擀面杖擀成圆形，放到平底锅里烙，温度不能太高。等火烧基本熟透后，把它放到平底锅下的炉灶中，炉灶是特制的，边上可以放得住火烧。这样，火烧接触更高的温度，却不接触明火。不多久，火烧外面就会有一层酥脆的外皮，咬到嘴里十分得香脆。</p>
        </div>
    </div>
    </div>

    <div class="footer">
    <h2 style="color: red;font-family: 微软雅黑;">驴肉火烧必须是圆的！</h2>
</div>

</body>
</html>
