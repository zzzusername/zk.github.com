<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>赵昆的简历</title>
    <link rel="stylesheet" href="static/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remodal/1.1.0/remodal-default-theme.min.css">
    <style>
        .left-label{
            width: 95px
        }
        .label-value{
            width: auto;
        }
        .container{
            height: auto;
        }
    </style>
</head>

<body>
    <div class="container" id="cv">
        <div class="side">
            <div class="me">
                <div class="portrait"></div>
                <div class="remodal remodal-img" data-remodal-id="portrait-modal">
                    <h3>请输入图片URL地址：</h3>
                    <br/>
                    <input type="text" id="avatar-url">
                    <button data-remodal-action="confirm" class="remodal-confirm">确定</button>
                </div>
                <h1 id="username" >赵昆</h1>
                <h4 id="persona-tag" >web前端工程师</h4>
            </div>
            <div class="profile info-unit">
                <h2 class="info-header"><i class="iconfont icon-person"></i> <span class="info-title">基本信息</span></h2>
                <hr>
                <ul class="info-list">
                    <li>
                        <label class="left-label">姓名</label><span class="label-value">赵昆</span></li>
                    <li>
                        <label class="left-label">学历</label><span class="label-value">大专</span></li>
                    <li>
                        <label class="left-label">毕业院校</label><span class="label-value">黑龙江工程学院</span></li>
                    <li>
                        <label class="left-label">毕业年份</label><span class="label-value">2013</span></li>
                </ul>
            </div>
            <div class="contact info-unit">
                <h2 class="info-header"><i class="iconfont icon-call"></i> <span class="info-title">联系方式</span></h2>
                <hr>
                <ul class="info-list">
                    <li>
                        <label class="left-label">手机</label><span class="label-value">15116965196</span>
                    <li>
                        <label class="left-label">邮箱</label><span class="label-value">zk980398878@163.com</span>
                    <li>
                </ul>
            </div>
            <div class="skill info-unit">
                <h2 class="info-header"><i class="iconfont icon-star"></i> <span class="info-title">技能点</span></h2>
                <hr>
                <ul class="progress-list">
                    <li>
                        <label class="left-label">html/css</label>
                        <progress value="80" max="100"></progress>
                    </li>
                    <li>
                        <label class="left-label">javascript</label>
                        <progress value="70" max="80"></progress>
                    </li>
                    <li>
                        <label class="left-label">jquery</label>
                        <progress value="60" max="100"></progress>
                    </li>
                    <li>
                        <label class="left-label">vue</label>
                        <progress value="60" max="70"></progress>
                    </li>
                </ul>
            </div>
            <div class="stack info-unit">
                <h2 class="info-header"><i class="iconfont icon-build"></i> <span class="info-title">技术栈</span></h2>
                <hr>
                <ul class="stack-list">
                    <li>
                        <label class="left-label">前端</label><span class="label-value">html,css,css3,jQuery、vue.js</span
                            ></li>
                    </li>
                    <li>
                        <label class="left-label">打包工具</label><span class="label-value">gulp,webpack</span>
                    </li>
                    </li>
                    <li>
                        <label class="left-label">代码控制</label><span class="label-value">git,svn</span>
                    </li>
                    </li>
                    <li>
                        <label class="left-label">其他</label><span class="label-value">webstorm, vscode,ps</span>
                    </li>
                    </li>
                </ul>
            </div>
            <div class="code info-unit">
                <h2 class="info-header"><i class="iconfont icon-weixin"></i><span class="info-title">个人微信</span></h2>
                <hr>
                <div class="weixin">
                    <img src="static/image/weixin.png" alt="">
                </div>
            </div>
        </div>
        <div class="main">
            <div class="work info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-work"></i> <span class="info-title">工作经历</span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3>居理新房 2016/10---2019/2</h3>
                        <p>侃家网是一个只做新房交易的网站，成交客户 均来自电话咨询，创办 3年以来公司迅速发展 在北京新房交易场占有一定份额!
                        </p>
                    </li>
                    <li>
                        <h3>北京华诺互动科技有限公司 2015/9---2016/10</h3>
                        <p>互联网外包公司，主要接触一些电商网站项目。
                        </p>
                    </li>
                </ul class="experience-list">
            </div>
            <div class="project info-unit right-list">
                <h2 class="info-header"><i class="iconfont icon-project"></i> <span class="info-title">个人参与项目</span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <h3>侃家网(PC端和移动端)</h3>
                        <h4>责任描述:</h4>
                        <p>
                        1、 主要负责产品需求评审，提供任务排期。 2、 提供div+css页面支持，通用模板提取。 3、 特殊js交互效果实现，与后台进行ajax交互 4、 网页性能测试，优化网页加载性能。
                            <br/>
                        </p>
                        <h5>技术要点:</h5>
                        <p>
                            1、 使用 原生 html css 完成页面布局 2、 使用固定定位 实现 侧边固定效果 3、 使用 Less 完成公共 css 的抽取 4、 使用 css3 完成图片缩放 <br>
                            5、 使用 js 实现 轮播图效果<br>
                            6、 使用了懒加载优化网页<br>
                            7、 使用 Js 实现 倒计时 效果<br>
                            8、 使用iconfont引入矢量字体图标 9、 Swiper 框架 实现 循环轮播 效果<br>
                            10、 使用 jQuary完成导航下的下拉列表 11、 使用cookie存储用户状态信息<br>
                            使用sessionStorage/localStorage 记录用户浏览信息<br>
                        </p>
                    </li>
                    <li>
                        <h3>侃家网(后台系统)</h3>
                        <h4>责任描述:</h4>
                        <p>
                            1、构建静态模板 html+css 2、复杂的js效果，和插件的使用 3、前后台数据交互
                            <br />
                        </p>
                        <h5>技术要点:</h5>
                        <p>
                            1、 使用 rem 解决移动端适配问题 <br>
                            2、 使用js实现后台交互效果<br>
                            3、 使用gulp管理开发目录<br>
                            4、 使用ajax实现前后端的json数据交互 5、 使用Css3 实现 旋转 放大等 动画效果 6、 使用 日期插件完成日期选取和数据交互<br>
                        </p>
                    </li>
                    <li>
                        <h3>侃家网(服务号开发和微信后台管理系统)</h3>
                        <h4>责任描述:</h4>
                        <p>
                            1、搭建vue 开发架构 2、使用微信sdk 完成 微信支付功能 3、处理微信后台返回的数据
                            <br />
                        </p>
                        <h5>技术要点:</h5>
                        <p>
                            1、 使用vue-cli 搭建vue开发环境<br> 2、使用vue-swiper实现动画效果<br>
                             3、使用axios完成前后台数据交互<br> 4、使用html+css构建页面基本结构<br>
                            5、 使用 微信sdk 完成 微信分享，打赏功能。<br> 6、 使用 插件 完成 图片上传功能。
                        </p>
                    </li>
                    <li>
                        <h3>米莱商城(外包项目）</h3>
                        <h4>责任描述:</h4>
                        <p>
                            1、 负责PC端静态页面实现
                            2、 处理兼容性问题
                            3、 对网站进行优化 增加用户体验
                            <br />
                        </p>
                        <h5>技术要点:</h5>
                        <p>
                        1、 手写 html和css实现页面布局<br>
                        2、 使用固定定位实现 侧边固定效果 3、 使用less 共同样式抽取<br>
                        4、 使用jQuery 完成选项卡的切换效果 <br>5、 使用 Js 操作实现图片懒加载 6、使用 iconfont 实现矢量图标<br>
                        7、 使用 css 给图片添加遮罩效果<br>
                        8、 使用Swiper 框架 实现 循环轮播 效果<br> 9、 使用cookie存储用户状态信息。<br>
                        10、 SEO优化
                        </p>
                    </li>
                </ul>
            </div>
            <div class="aboutme info-unit right-paragraph">
                <h2 class="info-header"><i class="iconfont icon-project"></i> <span class="info-title">自我评价</span></h2>
                <hr>
                <ul class="experience-list">
                    <li>
                        <p>
                            三年开发经验 有较强的学习能力; <br>
                            性格开朗 为人诚恳 乐观向上 有较强的适应能力的 有自制力 做事情有始有终 ;<br>
                            工作严谨踏实 认真负责 有较强的共事协作能力;<br>
                        </p>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
