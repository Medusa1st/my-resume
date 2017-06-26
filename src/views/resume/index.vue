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
              <p>GitHub：<a href="https://github.com/Medusa1st">github.com/Medusa1st</a></p>
            </div>
          </div>        
          <div class="profile-content-item">
            <div class="profile-content-item-title">个人介绍</div>
            <hr>
            <div class="profile-content-item-main">
              <p>爱好编程，喜欢研究，保持学习的心态。</p>
              <p>测试软件工程师起家，接触前端之后产生了极大的兴趣，喜欢研究前端方便的知识，虽然欠缺些艺术细胞，但也希望能把页面做得整洁漂亮，有着成为前端大牛的梦想。</p>
            </div>
          </div>
          <div class="profile-content-item">
            <div class="profile-content-item-title">教育背景</div>
            <hr>
            <div class="profile-content-item-main">
              <p>2013.09-2015.05</p>
              <p>东北大学</p>
              <p>计算机（硕士）</p>
              <p>主修课程：计算机控制理论与设计、程序设计方法学、网络互连及Internet技术、计算机视觉技术、智能控制理论与应用。</p>
              <br>
              <p>2007.09-2011.06</p>
              <p>上海工程技术大学</p>
              <p>汽车电子（本科）</p>
              <p>主修课程：汽车概论、数字电子技术、电路分析基础、模拟电子技术、工程项目管理、汽车构造与传动、自动控制理论、现代电力电子学等</p>
            </div>
          </div>
          <div class="profile-content-item">
            <div class="profile-content-item-title">工作经历</div>
            <hr>
            <div class="profile-content-item-main">
              <p>2011.07-2017.05</p>
              <p>上海科世达（管理）有限公司</p>
              <p>测试应用工程师</p>
              <ol>
                <li>终检测试设备程序的设计、更改、调试以及维护，主要工具VisualStudio和MySQL，语言VB.net和C++。</li>
                <li>外购测试设备及夹具的鉴定及验收。</li>
              </ol>
            </div>
          </div>
          <div class="profile-content-item">
            <div class="profile-content-item-title">项目经历</div>
            <hr>
            <div class="profile-content-item-main">
              <p>大众线束盘产品终检设计</p>
              <ol>
                <li>结合大众系列产品的特点，设计和开发能够兼容多种系列产品的终检程序。</li>
                <li>编写程序使其与整条生产线进行ADS通讯，达到自动化测试的目标。</li>
                <li>测试数据保存、分析，并优化生产效率和稳定性。</li>
              </ol>
              <br>
              <p>智能停车页面设计（实验室版，仅供展示）</p>
              <ol>
                <li>使用高德地图js-sdk制作手机html页面，实现用户定位、停车位标记、停车位选择、路线导航、支付等功能。</li>
                <li>实现个人信息和停车历史记录的展示。</li>
              </ol>   
              <p>Demo托管在以下链接<a href="http://medusa1st.me/livepark">medusa1st.me/livepark</a>，或通过手机扫描二维码访问。</p> 
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
</style>
