<template>
  <div class="main-container" v-show="true" style="display: none;">
    <div class="useful-link no-print">
      <!--<a class="theme-link" href="/index2.html"></a>-->
      <a class="github-button" href="https://github.com/chenghehao" title="我的Github">
        <img src="/static/images/star.svg" alt="Github"><span>Star</span>
      </a>
    </div>
    <section class="section section-header">
      <div class="section-bg section-header-bg"></div>
      <div class="section-bg section-content-bg"></div>
      <div class="container">
        <header class="header">
          <div class="header-box">
            <div class="avatar wow inShow no-print">
              <img src="/static/images/logo.png" alt="logo" class="img-responsive">
            </div>
            <h1 class="name text-center wow inShow no-print">程合浩</h1>
            <h1 class="name text-center hide show-print-block">程合浩</h1>
          </div>
        </header>
        <div class="section-content">
          <div class="content-box">
            <div class="name-slogan">
              <h2 class="wow inShow no-print" data-wow-delay="0.1s">
                <span class="text-light">hehao</span>&nbsp;cheng
              </h2>
              <div class="description wow inShow" data-wow-delay="0.15s">追求专业与卓越前端开发者</div>
            </div>
            <div class="contact-info">
              <div class="row">
                <div class="col-md-6 col-lg-3">
                  <div class="item wow inShow" data-wow-delay="0.3s">
                    <h4>性别</h4>
                    <div class="info">男</div>
                  </div>
                </div>
                <div class="col-md-6 col-lg-3">
                  <div class="item wow inShow" data-wow-delay="0.45s">
                    <h4>年龄</h4>
                    <div class="info">23</div>
                  </div>
                </div>
                <div class="col-md-6 col-lg-3">
                  <div class="item wow inShow" data-wow-delay="0.5s" :href="'mailto:'+userInfo.email">
                    <h4>学历</h4>
                    <div class="info">专科</div>
                  </div>
                </div>
                <div class="col-md-6 col-lg-3">
                  <a class="item wow inShow" data-wow-delay="0.55s" :href="userInfo.website" target="_blank">
                    <h4>经验</h4>
                    <div class="info">毕业两年工作两年</div>
                  </a>
                </div>
              </div>
              <div class="row">
                <div class="col-md-6 col-lg-3">
                  <div class="item wow inShow" data-wow-delay="0.6s">
                    <h4>Phone</h4>
                    <address class="info">17600204766</address>
                  </div>
                </div>
                <div class="col-md-6 col-lg-3">
                  <div class="item wow inShow" data-wow-delay="0.65s">
                    <h4>QQ</h4>
                    <div class="info">1714722134</div>
                  </div>
                </div>
                <div class="col-md-6 col-lg-3">
                  <a class="item wow inShow" data-wow-delay="0.7s" :href="userInfo.website" target="_blank">
                    <h4>我的博客</h4>
                    <div class="info">https://chenghehao.github.io</div>
                  </a>
                </div>
                <div class="col-md-6 col-lg-3">
                  <a class="item wow inShow" data-wow-delay="0.75s" :href="userInfo.github" target="_blank">
                    <h4>Github</h4>
                    <div class="info">https://github.com/chenghehao</div>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="section-bg section-header-bg"></div>
        <div class="section-bg section-content-bg"></div>
        <header class="header">
          <div class="content-box">
            <h2 class="title">介绍&nbsp;/&nbsp;
              <small><i>Intro</i></small>
            </h2>
            <div class="description">介绍一些个人基本情况</div>
          </div>
        </header>
        <div class="section-content">
          <div class="intro">
            <!-- <p v-for="intro in userInfo.intro.content" v-html="intro"></p> -->
            <p>熟悉前端项目构建，有过基于 原生JS 和 vue 的产品开发经验；</p>
            <p>能够编写各种静态页面，实现各种动效；</p>
            <p>精通HTML, CSS, 熟悉HTML5，CSS3，熟悉ES6语法；</p>
            <p>熟练使用原生JS，jQuery，Ajax，能够熟练使用原生JS实现多种交互效果；</p>
            <p>熟练使用Vue.js，有实际开发的单页面应用，了解React.js，了解MVC，MVVM模型；</p>
            <p>熟练使用PS，满足前端开发中的需求；</p>
            <p>熟练使用Git管理代码，Webpack打包管理工具，了解node.js;</p>
            <p>初步学习微信小程序，公众号开发中</p>
          </div>
          <div class="technology">
            <ul class="inline">
              <li><b>用过的技术栈：</b></li>
              <li>scss</li>
              <li>bootstrap</li>
              <li>vue</li>
              <li>git</li>
              <li>node.js</li>
              <li>react</li>
              <li>express</li>
              <li>mongodb</li>
              <li>webpack</li>
              <li>axios</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="section-bg section-header-bg"></div>
        <div class="section-bg section-content-bg"></div>
        <header class="header">
          <div class="content-box">
            <h2 class="title">工作经验&nbsp;/&nbsp;
              <small><i>Experience</i></small>
            </h2>
            <div class="description">不同时期简短的从业经历介绍</div>
          </div>
        </header>
        <div class="section-content">
          <div class="experience">
            <div class="item">
              <div class="row">
                <div class="col-md-5">
                  <div class="time">2016.9</div>
                  <div class="title">好贷网</div>
                  <div class="description">前端开发</div>
                </div>
                <div class="col-md-7">
                  <div class="content">负责好贷网和信贷圈的PC和移动端页面开发，根据产品需求和UI效果图利用Vscode进行标准页面制作；负责金融产品项目的日常维护，和前端新技能探索和优化。</div>
                  <div class="tips">
                    <b>主要业绩：</b>
                    <ul>
                       <li>配合团队规划和实现整个前端的研发到交付流程的的优化，提高了前后端合作效率，实现了真正意义上的前后端分离。</li>
                       <li>公司周年活动时负责负责浮动红包效果实现，效果良好。</li>
                       <li>配合团队推动项目用 vue 重构。</li>
                       <li>做了一些技术分享，协同前端同事做了h5端的项目重构。</li>
                    </ul>
                  </div>
                  <div class="technology">
                    <b>技术栈：</b>
                    <ul class="inline">
                      <Li>node.js</Li>
                      <Li>vue</Li>
                      <Li>scss</Li>
                      <Li>webpack</Li>
                      <Li>bootstrap</Li>
                      <Li>flex</Li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-5">
                  <div class="time">2018.1</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="section-bg section-header-bg"></div>
        <div class="section-bg section-content-bg"></div>
        <header class="header">
          <div class="content-box">
            <h2 class="title">技能&nbsp;/&nbsp;
              <small><i>Skills</i></small>
            </h2>
            <div class="description">我所掌握的工具和技术栈</div>
          </div>
        </header>
        <div class="section-content">
          <div class="row skill">
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">90%</span>Css
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'90%'"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">80%</span>PhotoShop
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'80%'"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">85%</span>JavaScript
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'85%'"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">40%</span>Node.js
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'40%'"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">60%</span>Ajax
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'60%'"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">85%</span>Bootstrap
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'85%'"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">65%</span>React
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'65%'"></div>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="item">
                <div class="text-info">
                  <span class="num text-light">85%</span>Vue
                </div>
                <div class="progress">
                  <div class="progress-bar wow progressShow" :style="'width:'+'85%'"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="section-bg section-header-bg"></div>
        <div class="section-bg section-content-bg"></div>
        <header class="header">
          <div class="content-box">
            <h2 class="title">项目经验&nbsp;/&nbsp;
              <small><i>Experience</i></small>
            </h2>
            <div class="description">近期主要做过的一些项目</div>
          </div>
        </header>
        <div class="section-content">
          <div class="experience">
            <div class="item" >
              <div class="row">
                <div class="col-md-5">
                  <div class="time">2016.09-2017.02</div>
                  <div class="title">信贷圈</div>
                  <div class="description">贷款经理人的信息服务平台</div>
                </div>
                <div class="col-md-7">
                  <div class="content">与好贷官网配合，为贷款经理人提供源源不断的优质好单，同时将贷款申请客户有效匹配给贷款经理人</div>
                  <div class="tips">
                    <b>实现的主要功能：</b>
                    <ul>
                      <li>针对贷款经理人的实名注册及认证</li>
                      <li>贷款订单展示</li>
                      <li>针对注册用户订购网站会员的订单系统</li>
                      <li>信贷经理人常用工具模块</li>
                      <li>各种活动页面</li>
                    </ul>
                  </div>
                  <div class="technology">
                    <b>技术栈：</b>
                    <ul class="inline">
                      <li>node.js</li>
                      <li>vue</li>
                      <li>scss</li>
                      <li>webpack</li>
                      <li>bootstrap</li>
                      <li>flex</li>
                      <li>mongodb</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="item" >
              <div class="row">
                <div class="col-md-5">
                  <div class="time">2017.02-2018.01</div>
                  <div class="title">好贷网</div>
                  <div class="description">一个贷款信息服务平台</div>
                </div>
                <div class="col-md-7">
                  <div class="content">一个信息服务平台正常维护，包括优惠券体验金以及各种不同产品的迭代。以及各种活动页面的制作和实现。</div>
                  <div class="tips">
                    <b>实现的主要功能：</b>
                    <ul>
                      <li>贷款申请</li>
                      <li>贷款机构信息</li>
                      <li>贷款产品</li>
                      <li>活动页面</li>
                    </ul>
                  </div>
                  <div class="technology">
                    <b>技术栈：</b>
                    <ul class="inline">
                      <li>node.js</li>
                      <li>vue</li>
                      <li>scss</li>
                      <li>webpack</li>
                      <li>bootstrap</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="item" >
              <div class="row">
                <div class="col-md-5">
                  <div class="time">个人作品</div>
                  <div class="title">原生JS百度云盘</div>
                  <div class="description">原生JS实现百度云盘基本功能</div>
                </div>
                <div class="col-md-7">
                  <div class="content">为了练习和学习原生JS，仿造的百度网盘，不做任何商业用途，项目源码在Github中的iCloud中存放，欢迎Clone查看作出指点。</div>
                  <div class="tips">
                    <b>实现的主要功能：</b>
                    <ul>
                      <li>文件夹的增删改查</li>
                      <li>文件夹的重命名</li>
                      <li>拖拽选中或取消选中文件夹</li>
                      <li>利用localStorage做了本地存储</li>
                    </ul>
                  </div>
                  <div class="technology">
                    <b>技术栈：</b>
                    <ul class="inline">
                      <li>原生js</li>
                      <li>localStorage</li>
                      <li>json</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="item" >
              <div class="row">
                <div class="col-md-5">
                  <div class="time">个人作品</div>
                  <div class="title">Vue-one</div>
                  <div class="description">One 一个</div>
                </div>
                <div class="col-md-7">
                  <div class="content">喜欢阅读和电影赏析，可能是高中时期学过编导的原因，很喜欢One这款产品，学习和练习vue时仿造学习这个项目，不做任何商业用途，源码在Github的One-vue存放。</div>
                  <div class="tips">
                    <b>实现的主要功能：</b>
                    <ul>
                      <li>动画导航</li>
                      <li>主页推荐</li>
                      <li>文章阅读，影视赏析，音乐分享</li>
                      <li>vue-router实现底部固定导航栏</li>
                    </ul>
                  </div>
                  <div class="technology">
                    <b>技术栈：</b>
                    <ul class="inline">
                      <li>node.js</li>
                      <li>vue</li>
                      <li>scss</li>
                      <li>webpack</li>
                      <li>es6</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="item" >
              <div class="row">
                <div class="col-md-5">
                  <div class="time">个人作品</div>
                  <div class="title">Cnode</div>
                  <div class="description">React实现cnode社区</div>
                </div>
                <div class="col-md-7">
                  <div class="content">学习和练习React,利用cnode开放的api和mongodb实现的cnode社区，不做任何商业用途，源码在Github的React-cnode中存放</div>
                  <div class="tips">
                    <b>实现的主要功能：</b>
                    <ul>
                      <li>雪花飘落效果</li>
                      <li>登陆注册验证</li>
                      <li>文章分类</li>
                      <li>文章详情页</li>
                    </ul>
                  </div>
                  <div class="technology">
                    <b>技术栈：</b>
                    <ul class="inline">
                      <li>node.js</li>
                      <li>vue</li>
                      <li>scss</li>
                      <li>webpack</li>
                      <li>bootstrap</li>
                      <li>flex</li>
                      <li>mongodb</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="section-bg section-header-bg"></div>
        <div class="section-bg section-content-bg"></div>
        <header class="header">
          <div class="content-box">
            <h2 class="title">常逛&nbsp;/&nbsp;
              <small><i>Usually</i></small>
            </h2>
            <div class="description">经常逛的技术或者设计相关网站</div>
          </div>
        </header>
        <div class="section-content">
          <div class="row usually">
            <div class="col-lg-4 col-md-6">
              <a href="https://github.com/chenghehao" target="_blank" class="item">
                <i class="fa fa-github"></i>
                <h3 class="text-light">GitHub</h3>
                <p>分享一些我的小作品 结交志同道合的朋友</p>
              </a>
            </div>
            <div class="col-lg-4 col-md-6">
              <a href="https://www.zhihu.com/people/keep-9-71/activities" target="_blank" class="item">
                <i class="fa fa-github"></i>
                <h3 class="text-light">知乎</h3>
                <p>搜索解决一些疑问 探索新奇</p>
              </a>
            </div>
            <div class="col-lg-4 col-md-6">
              <a href="https://developer.mozilla.org" target="_blank" class="item">
                <i class="fa fa-github"></i>
                <h3 class="text-light">MDN</h3>
                <p>分查阅一些技术文档</p>
              </a>
            </div>
            <div class="col-lg-4 col-md-6">
              <a href="https://juejin.im/welcome/frontend" target="_blank" class="item">
                <i class="fa fa-github"></i>
                <h3 class="text-light">掘金</h3>
                <p>帮助开发者成长的社区</p>
              </a>
            </div>
            <div class="col-lg-4 col-md-6">
              <a href="https://www.jianshu.com" target="_blank" class="item">
                <i class="fa fa-github"></i>
                <h3 class="text-light">简书</h3>
                <p>创作你的创作</p>
              </a>
            </div>
            <div class="col-lg-4 col-md-6">
              <a href="https://codepen.io/" target="_blank" class="item">
                <i class="fa fa-github"></i>
                <h3 class="text-light">CodePen</h3>
                <p>探索和分享好的代码</p>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section no-print">
      <div class="container">
        <div class="section-bg section-header-bg"></div>
        <div class="section-bg section-content-bg"></div>
        <header class="header">
          <div class="content-box">
            <h2 class="title">联系&nbsp;/&nbsp;
              <small><i>Contact</i></small>
            </h2>
            <div class="description">通过这些信息可以联系到我</div>
          </div>
        </header>
        <div class="section-content">
          <div class="contact">
            <div class="row">
              <div class="col-md-6 col-lg-3">
                <div class="item">
                  <h4>Phone</h4>
                  <div class="info">17600204766</div>
                </div>
              </div>
              <div class="col-md-6 col-lg-3">
                <div class="item">
                  <h4>QQ</h4>
                  <div class="info">1714722134</div>
                </div>
              </div>
              <div class="col-md-6 col-lg-3">
                <div class="item">
                  <h4>Location</h4>
                  <div class="info">Beijing·China</div>
                </div>
              </div>
              <div class="col-md-6 col-lg-3">
                <a class="item" :href="'mailto:1714722134@qq.com'">
                  <h4>Email</h4>
                  <div class="info">1714722134@qq.com</div>
                </a>
              </div>
            </div>
          </div>
          <div class="name-slogan">
            <h2 class="wow inShow">
              <span class="text-light">hehao</span>&nbsp;cheng
            </h2>
            <div class="description wow inShow" data-wow-delay="0.05s">追求专业与卓越前端开发者（Ctrl+p可以印本简历，打印时显示真名）</div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>

  export default {
    name: 'front',
    data() {
      return {
        userInfo: {
          exp:[],
          qq:{},
          intro:{
            content:[],
            technology:{
              title:'',
              content:[]
            }
          },
          experience:[{
            tips:{
              title:'',
              content:[],
            },
            technology:[],
          }],
          skill:[],
          project:[{
            tips:{
              title:'',
              content:[],
            },
            technology:[],
          }],
          usually:[],
        },
      }
    },

    methods:{
      calcDate(birthday){
        let birthdayDate = new Date(birthday);
        let todyDate = new Date();
        return todyDate.getYear() - birthdayDate.getYear()
      }
    }
  }
</script>
