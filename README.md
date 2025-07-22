<div align="center">
  <img src="https://qsgz.thw.lol/static/image/%E7%8F%AD%E7%BA%A7.jpg" alt="淄博齐盛高级中学" width="200">
  <h1>淄博齐盛高级中学网站</h1>
  <p>学生自制的现代化的学校网站</p>
  
  ![License](https://img.shields.io/badge/License-MIT-blue.svg)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
  ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white)
</div>

## ✨ 项目亮点

- 🎨 现代化UI设计，优秀的动画ui设计
- ⚡ 高性能前端实现，优化用户体验
- 🎓 高仿的专业学校信息展示页面
- 🎯 集成SEO优化，提升搜索引擎可见性

## 🚀 特色功能

### 录取通知书生成器
- 动态生成个性化录取通知书
- 支持自定义学生姓名
- 一键下载高清晰度图片

### 响应式设计
- 完美适配桌面、平板和手机
- 智能调整布局和字体大小
- 触摸友好的交互元素

### 性能优化
- 图片懒加载
- 资源压缩
- 浏览器缓存策略

## 🛠️ 技术栈

### 核心框架
- **HTML5** - 语义化标签，现代化网页结构
- **CSS3** - 响应式布局，动画效果
- **JavaScript (ES6+)** - 交互逻辑实现

### 主要库
- **jQuery** - DOM操作与事件处理
- **html2canvas** - 前端截图功能
- **Font Awesome** - 图标库
- **Google Fonts** - 网页字体

### 开发工具
- **Visual Studio Code** - 代码编辑器
- **Git** - 版本控制
- **Microsoft Edge DevTools** - 调试工具





## 📝 使用说明

1. 克隆本仓库
2. 使用现代浏览器打开 `index.html` 即可查看网站
3. 根据需求修改 `index.html` 中的内容，看完下面的内容可以帮助你快速学会修改网站的内容
4. 更新你的静态资源到 `static` 目录下


## 🎨 网站自定义指南

### 1. 弹窗信息自定义
打开 `index.html` 文件，找到以下部分进行文字自定义：

```html
    <!-- 这是弹窗 -->
    <div class="site-notice" id="siteNotice">
        <div class="notice-content">
            <h2>⚠手机端访问一定要打开浏览器设置里的电脑模式！</h2>
            <div class="notice-text">
                <p>淄博齐盛高级中学录取通知书生成器(BATE)</p>
                <p>可下载，自定义名字</p>
            </div>
            <div class="notice-btn-container">
                <button type="button" class="notice-btn notice-btn-primary" onclick="window.location.href='admission_notice.html'">生成通知书</button>
                <button type="button" class="notice-btn" id="closeNotice" onclick="closeNotice()">关闭</button>
            </div>
        </div>
    </div>
```

### 2. 导航栏标题信息自定义
在 `index.html` 中定位到导航栏部分，可更新文字：

```html
    <!-- 导航栏 -->
    <nav class="main-nav" role="navigation">
        <div class="container">
            <ul>
                <li><a href="/" class="nav-link" aria-label="返回首页">首页</a></li>
                <li><a href="/about" class="nav-link" data-modal="intro">学校简介</a></li>
                <li><a href="/profile" class="nav-link" data-modal="info">学校概况</a></li>
                <li><a href="/leadership" class="nav-link" data-modal="leadership">学校领导</a></li>
                <li><a href="/teachers" class="nav-link" data-modal="teachers">师资队伍</a></li>
                <li><a href="/student" class="nav-link" data-modal="students">学生发展</a></li>
                <li><a href="/features" class="nav-link" data-modal="features">办学特色</a></li>
                <li><a href="/admission" class="nav-link" data-modal="admission">招生简章</a></li>
            </ul>
        </div>
    </nav>

```

### 3. 导航栏窗口内容自定义
在 `index.html` 中导航栏部分下方即是，按需修改，格式：

```html
<div class="modal-container">
        <div class="modal" id="intro-modal">
            <div class="modal-content">
                <span class="close-btn">&times;</span>
                <h2>学校简介</h2>
                <div class="modal-text">
                    <p>淄博齐盛高级中学位于鲁泰大道以北，天津路以东，是2018年由市委市政府批准建设的公办普通高级中学，学校占地132亩，建筑面积68768平方米，各项设施配备全市一流。2021年秋季学期，学校正式投入使用。</p>
                    <div class="gallery-item">
                        <div class="video-container">
                            <iframe src="//www.bilibili.com/blackboard/html5mobileplayer.html?aid=675590858&bvid=BV1TU4y1A72t&cid=410440401&p=1&danmaku=0&autoplay=1&hideDanmakuButton=1&noFullScreenButton=1&fjw=0&muted=1" frameborder="no" scrolling="no" allowfullscreen="true"></iframe>
                        </div>
                    </div>
                    <p>根据市教育局实施集团化办学改革精神，以淄博实验中学为核心校，淄博齐盛高级中学为成员校，进行紧密型集团化办学模式试点。淄博实验中学将淄博齐盛高级中学的建设、发展纳入三年发展规划，实行紧密型管理，实现人财物统筹互补和优质教育资源共享共用，形成集团内学校相互激励、相互促进、共同发展的格局，逐步把淄博齐盛高级中学建设成为全市一流、走在全省乃至全国前列的新型高中学校。</p>
                    <p>目前，两校管理干部和教师已实现互派交流，两校教育教学已实现共同教研、共同备课、同步检测、同步阅卷、同步分析，两校学生已实现学习、社团活动、主题德育活动等资源同步。</p>
                    <p>两校的集团化办学将会持续下去，会更加紧密！</p>
                    <p>建校以来，学校先后获得省级绿色学校、市级无烟学校、区级文明校园、市中小学学生公寓A级单位、百佳青春团队、区级文明校园、市级特色高中学校等荣誉。</p>
                </div>
            </div>
        </div>
```

### 4. 新闻标题与首页展示图片自定义
修改文字与资源依赖：

```html
<div class="modal" id="news1-modal">
            <div class="modal-content">
                <span class="close-btn">&times;</span>
                <h2>淄博齐盛高中2025级高一新生分班结果查询</h2>
                <div class="modal-text">
                    <p>亲爱的2025级新生：         
                    <p>    欢迎你们！淄博齐盛高中2025级分班信息查询系统已经开放，请按学校要求于7月15日上午到学校报到。可通过以下网址进行分班查询：https://query.vzibo.net/query/type/c2ec82ae8ba1b88841289c72705b41ed.html</p>
                    <p class="news-date">发布时间：2025-07-13</p>
                </div>
            </div>
        </div>
```


### 5. 新闻内容自定义
以第一条新闻为例：

```html
<div class="modal" id="news1-modal">
            <div class="modal-content">
                <span class="close-btn">&times;</span>
                <h2>淄博齐盛高中2025级高一新生分班结果查询</h2>
                <div class="modal-text">
                    <p>亲爱的2025级新生：         
                    <p>    欢迎你们！淄博齐盛高中2025级分班信息查询系统已经开放，请按学校要求于7月15日上午到学校报到。可通过以下网址进行分班查询：https://query.vzibo.net/query/type/c2ec82ae8ba1b88841289c72705b41ed.html</p>
                    <p class="news-date">发布时间：2025-07-13</p>
                </div>
            </div>
        </div>
```

### 6. 校园风光图片自定义
```html
    <!-- 校园风光页 -->
    <section class="campus-section">
        <div class="container">
            <h2 class="section-title">校园风光</h2>
            <meta name="keywords" content="淄博齐盛高级中学,校园环境,教学设施,校园风光">
            <div class="campus-gallery">
                <!-- 图片1 -->
                <div class="gallery-item">
                    <img src="./static/image/1.JPG" alt="校园风光1" class="gallery-image">
                </div>

                <!-- 图片2 -->
                <div class="gallery-item">
                    <img src="./static/image/2.JPG" alt="校园风光2" class="gallery-image">
                </div>

                <!-- 图片3 -->
                <div class="gallery-item">
                    <img src="./static/image/3.JPG" alt="校园风光3" class="gallery-image">
                </div>

                <!-- 视频 -->
                <div class="gallery-item">
                    <div class="video-container">
                        <iframe src="//www.bilibili.com/blackboard/html5mobileplayer.html?aid=114755083705660&bvid=BV1RkK6zqEga&cid=25818111057&p=1&danmaku=0&autoplay=1&hideDanmakuButton=1&noFullScreenButton=1&fjw=0&muted=1" frameborder="no" scrolling="no" allowfullscreen="true"></iframe>
                    </div>
                </div>

                <!-- 懒得打了 -->
                <div class="gallery-item">
                    <img src="./static/image/5.JPG" alt="校园风光5" class="gallery-image">
                </div>
                <!-- 懒得打了 -->
                <div class="gallery-item">
                    <img src="./static/image/6.JPG" alt="校园风光6" class="gallery-image">
                </div>
            </div>
            <!-- 正是在下 -->
            <div class="shot-on-caption">
                photo by THW
            </div>
        </div>
    </section>
```


### 7. 页脚内容自定义
以第一条新闻为例：

```html
   <!-- 页脚 -->
    <footer class="site-footer">
        <div class="container">
            <div class="footer-logo">
                <img src="./static/image/13.gif" alt="齐盛高中 Logo 动画" class="footer-logo-img">
            </div>
            <div class="copyright">
                <p>学校咨询电话：3180577,3189080,3180566 | 学校微信公众号：淄博齐盛高级中学</p>
            </div>
        </div>
    </footer>

```


### 图片容器使用示例
```html
                <div class="gallery-item">
                    <img src="在这里填写资源路径" alt="别忘了写" class="gallery-image">
                </div>
```

### bilibili视频嵌入使用示例
```html
                <div class="gallery-item">
                    <div class="video-container">
                        <iframe src="//www.bilibili.com/blackboard/html5mobileplayer.html?aid=自定义&bvid=BV号&cid=这里也要改&p=1&danmaku=0&autoplay=1&hideDanmakuButton=1&noFullScreenButton=1&fjw=0&muted=1" frameborder="no" scrolling="no" allowfullscreen="true"></iframe>
                    </div>
                </div>
```

## ❓︎ 问答
### 为什么做成纯前端网站？
答：在本项目中，采用纯前端实现，1是降低开发复杂度：完整的网站通常包含后端服务、数据库等组件，若要从零构建一个功能完备的后端系统，不仅需要大量时间进行架构设计和接口开发，还需考虑数据格式、安全性、性能优化等问题。2是对于学生而言，云服务器费用过高。而纯前端几乎为零的运维成本显然更合适，虽然纯前端项目在内容更新上不够灵活，但经过了一次大规模代码重构过后，目前直观模块化的html结构使得内容维护的门槛已经大大降低。
## 📄 开源协议

本项目采用 [MIT](LICENSE) 开源协议

---

<div align="center">
    <p>© 2025 THW 版权所有</p>
</div>
