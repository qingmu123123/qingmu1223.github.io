<!doctype html>
<html lang="zh">
<head>
<meta charset="utf-8">
<title>个人名片</title>
</head>
<body>
<div class="card_a">
  <section>
     <h1>简历</h1>

  <b>
    <p>基本信息
      <p>求职意向：软件开发工程师</p>
    <P>联系电话：123456895</p>
    
    <P>邮箱：3544422474@qq.com</p>
  </b>
  <h1>
    教育背景</h1>
  <o1>
    <li>2010-2016 小学</li>
    
    <li>2016-2019 初中</li>
    <li>2019-2022 高中</li>
    <li>2022-   大学</li>
    </ol>
  <h1>专业技能
  </h1>
  
  <u1>
    <li>掌握一定的编程技术</li>
    <li>熟悉操作系统的基本理论</li>
    <li>了解计算机网络系统</li>
    <li>了解软件工程的理论基础</li>
    <h1>个人评价
  </h1>
  <p>希望翻过这座浪浪山！虽然山的后面还是山，但是沿途的风景总会不同，想要站在山顶领悟从没看到的景色。
    </body>

    </ul>
  </section>
</div>
<style>
 * {
    margin: 0;
    padding: 0
}
 
.card_a {
    width: 800px;
    height: 700px;
    position: absolute;
    left: 50%;
    top: 30%;
    margin-top: -230px;
    margin-left: -400px;
    background: #efe6f1;
    overflow: hidden;
    border-radius: 10px;
}
 
.card_a:before {
    content: "";
    position: absolute;
    width: 400px;
    height: 1000px;
    border-radius: 100%;
    background: linear-gradient(45deg, #8ed3e1 8%, transparent, #efe6f1);
    bottom: -53px;
    left: -87px;
}
 
.card_a:after {
    content: "";
    position: absolute;
    width: 700px;
    height: 700px;
    border-radius: 100%;
    background: radial-gradient(#afdfef, #c8e8f2, transparent 60%, #efe6f1);
    top: -123px;
    right: -352px;
}
 
.card_a section {
    width: 600px;
    position: absolute;
    left: 100px;
    top: 80px;
    z-index: 9;
}
 
.card_a section h2 {
    font-size: 50px;
    letter-spacing: .1em;
    margin-bottom: 66px;
}
 
.card_a section span {
    font-size: 28px;
    font-weight: normal;
    margin-left: 50px;
    letter-spacing: normal;
}
 
.card_a img {
    float: right;
    width: 1344px
}
 
.card_a section ul {
    border-left: #222 3px solid;
    padding-left: 28px;
}
 
.card_a section ul li {
    list-style: none;
    line-height: 563px;
    font-size: 18px;
}
 
</style>
