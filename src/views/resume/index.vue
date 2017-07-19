<template>
    <div id="cp-resume">
        <div class="profile-title">
            <div class="profile-title-photo"><img src="../../assets/profile-photo.jpg"></div>
            <h1>你好，我是王宇伟</h1>
        </div>
        <div class="profile-content-lists">
          <div class="profile-content-item">
            <div class="profile-content-item-title">基本信息</div>

            <hr>
            <div class="profile-content-item-main">
              <p>籍贯：上海</p>
              <p>年龄：28</p>
              <p>出生年月：1989/8/10</p>
              <p>政治面貌：党员</p>
              <p>手机：17717323281</p>
              <p>邮箱：<a href="mailto:littlemeidusha@163.com">littlemeidusha@163.com</a></p>
              <p>GitHub：<a href="https://github.com/Medusa1st">github.com/Medusa1st</a>
              </p>
              <p>个人网站：<a href="http://medusa1st.me/">medusa1st.me</a></p>
            </div>
          </div>        
          <div class="profile-content-item">
            <div class="profile-content-item-title">个人介绍</div>
            <hr>
            <div class="profile-content-item-main">
              <p><b>爱好编程，喜欢钻研，持续学习。</b></p>
              <p>测试软件工程师起家，基于对web开发的喜爱，希望转向前端。</p>
              <p>自学前端半年，喜欢研究前端方面的知识，有着成为前端大牛的梦想。</p>
              <p>毕业后的工作经历，让我习惯于阅读英语的文档，让我深知人脉关系和沟通能力的重要性，让我在编程中找到了乐趣。</p>
            </div>
          </div>
          <div class="profile-content-item">
            <div class="profile-content-item-title">教育背景</div>
            <hr>
            <div class="profile-content-item-main">
              <div class="in-line-info">
                <p>2013.09-2015.05</p>
                <p>东北大学</p>
                <p>计算机（硕士）</p>
              </div>
              <p>主修课程：计算机控制理论与设计、程序设计方法学、网络互连及Internet技术、计算机视觉技术、智能控制理论与应用。</p>
              <br>
              <div class="in-line-info">
                <p>2007.09-2011.06</p>
                <p>上海工程技术大学</p>
                <p>汽车电子（本科）</p>
              </div>
              <p>主修课程：汽车概论、数字电子技术、电路分析基础、模拟电子技术、工程项目管理、汽车构造与传动、自动控制理论、现代电力电子学等</p>
            </div>
          </div>
          <div class="profile-content-item">
            <div class="profile-content-item-title">工作经历</div>
            <hr>
            <div class="profile-content-item-main">
              <div class="in-line-info">
                <p>2011.07-2017.05</p>
                <p>上海科世达华阳汽车电器有限公司</p>
                <p>测试软件工程师</p>
              </div>
              <ol>
                <li>终检测试设备程序的设计、更改、调试以及维护。</li>
                <li>根据产品特性，编写测试模块以实现测试需求。</li>
              </ol>
            </div>
          </div>
          <div class="profile-content-item">
            <div class="profile-content-item-title">项目经历(不分先后)</div>
            <hr>
            <div class="profile-content-item-main">
              <p><b>大众线束盘产品终检设计</b></p>
              <ul>
                <li>结合大众系列产品的特点，设计和开发能够兼容多种系列产品的终检程序。</li>
                <li>编写程序使其与整条生产线进行ADS通讯，达到自动化测试的目标。</li>
                <li>测试数据保存、分析，并优化生产效率和稳定性。</li>
              </ul>
              <p>收获经验：实现了一个产品的完整的测试程序，对一个项目的整体搭建和模块化编程有了更深入了理解。</p>
              <br>
              <p><b>个人网站</b>（业余项目）</p>
              <ul>
                <li>我在阿里云上的个人服务器网站:<a href="http://medusa1st.me">medusa1st.me</a></li>
                <li>服务器环境：ubuntu16.04 + nginx + mysql + php7</li>
              </ul>
              <p>收获经验：对前端项目的部署以及后端服务器的基本操作、常用工具和环境搭建有了基础的理解。</p>
              <br>
              <p><b>智能停车页面设计</b></p>
              <ul>
                <li>使用高德地图js-sdk制作手机html页面，实现用户定位、停车位标记、停车位选择、路线导航、支付等功能。</li>
                <li>实现个人信息和停车历史记录的展示。</li>
              </ul>
              <p>收获经验：对前端框架有了更深的理解，认识到了项目的重构、优化、兼容性的重要性。并学会了编写基础后端代码、创建json、ajax传递。</p>
              <p>Demo托管在以下链接<a href="http://www.liveparkchina.com">http://www.liveparkchina.com</a>，需通过微信扫描二维码访问。</p> 
              <div class="barcode"><img src="../../assets/project-demo1.png"></div>
            </div>
          </div>

        </div>
    </div>
</template>

<script>
  export default {
    name: 'resume',
    data(){
      return{
        msg: ''
      }
    }
  }
</script>

<style>

#cp-resume{
  max-width: 640px;
  background-color: #fff; 
  margin: 2rem auto;
  padding: 3rem;
  text-align: center;
  box-shadow: 1px 1px 2px #888888;
}

.profile-title{
  padding-bottom: 1rem; 
}
.profile-title h1{
  font-size: 1.5rem;
}

.profile-title-photo{
  width: 150px;
  height: 150px;
  border-radius: 75px;
  overflow: hidden;
  margin: 0 auto;
}

.profile-title-photo img{
  width: 100%;
  height: 100%;
}

.profile-content-item{
  text-align: left;
  padding-bottom: 2rem;
}

.profile-content-item-title{
  font-size: 1.3rem;
  font-weight: bold;
}

.barcode{
  width: 150px;
  height: 150px;
  overflow: hidden;
  margin: 0 auto;
}

.barcode img{
  width: 100%;
  height: 100%;
}

@media screen and (max-width: 762px) {
  #cp-resume{
    margin: 0 auto;
    padding-left: 1rem;
    padding-right: 1rem;
  }
}

.in-line-info{
  display:flex;
  /*justify-content:space-between;*/
}

.in-line-info p{
  margin-right: 20px;
}
</style>
