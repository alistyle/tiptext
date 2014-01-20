# tiptext

---

提示组件

---

## 演示
<link type="text/css" rel="stylesheet" media="screen" href="src/tiptext.css">

### ali-tiptext 文本
````html
<p class="ali-tiptext ali-tiptext-message">
    <i class="ali-tiptext-icon iconfont" title="提示">&#xF046;</i>
    提示 - message
</p>
<p class="ali-tiptext ali-tiptext-error">
    <i class="ali-tiptext-icon iconfont" title="出错">&#xF045;</i>
    出错 - error
</p>
<p class="ali-tiptext ali-tiptext-warning">
    <i class="ali-tiptext-icon iconfont" title="警告">&#xF047;</i>
    警告 - warning
</p>
<p class="ali-tiptext ali-tiptext-success">
    <i class="ali-tiptext-icon iconfont" title="成功">&#xF049;</i>
    成功 - success
</p>
<p class="ali-tiptext ali-tiptext-question">
    <i class="ali-tiptext-icon iconfont" title="疑问">&#xF04A;</i>
    疑问 - question
</p>
<p class="ali-tiptext ali-tiptext-stop">
    <i class="ali-tiptext-icon iconfont" title="阻止">&#xF048;</i>
    阻止 - stop
</p>
<p class="ali-tiptext ali-tiptext-wait">
    <i class="ali-tiptext-icon iconfont" title="等待">&#xF04B;</i>
    等待 - wait
</p>
````

### ali-top-container 区块
````html
<div class="ali-tiptext-container ali-tiptext-container-message">
    <p class="ali-tiptext ali-tiptext-message">
        <i class="ali-tiptext-icon iconfont" title="提示">&#xF046;</i>
        提示 - message
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-error">
    <p class="ali-tiptext ali-tiptext-error">
        <i class="ali-tiptext-icon iconfont" title="出错">&#xF045;</i>
        出错 - error
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-warning">
    <p class="ali-tiptext ali-tiptext-warning">
        <i class="ali-tiptext-icon iconfont" title="警告">&#xF047;</i>
        警告 - warning
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-success">
    <p class="ali-tiptext ali-tiptext-success">
        <i class="ali-tiptext-icon iconfont" title="成功">&#xF047;</i>
        成功 - success
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-question">
    <p class="ali-tiptext ali-tiptext-question">
        <i class="ali-tiptext-icon iconfont" title="疑问">&#xF04A;</i>
        疑问 - question
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-stop">
    <p class="ali-tiptext ali-tiptext-stop">
        <i class="ali-tiptext-icon iconfont" title="阻止">&#xF048;</i>
        阻止 - stop
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-wait">
    <p class="ali-tiptext ali-tiptext-wait">
        <i class="ali-tiptext-icon iconfont" title="等待">&#xF04B;</i>
        等待 - wait
    </p>
</div>
````

### ali-tip-container 区块(带关闭按钮)
````html
<div class="ali-tiptext-container ali-tiptext-container-message">
    <p class="ali-tiptext ali-tiptext-message">
        <i class="ali-tiptext-icon iconfont" title="提示">&#xF046;</i>
        提示 - message
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ali-tiptext-close iconfont">&#xF028;</div>
</div>
<div class="ali-tiptext-container ali-tiptext-container-error">
    <p class="ali-tiptext ali-tiptext-error">
        <i class="ali-tiptext-icon iconfont" title="出错">&#xF045;</i>
        出错 - error
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ali-tiptext-close iconfont">&#xF028;</div>
</div>
<div class="ali-tiptext-container ali-tiptext-container-warning">
    <p class="ali-tiptext ali-tiptext-warning">
        <i class="ali-tiptext-icon iconfont" title="警告">&#xF047;</i>
        警告 - warning
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ali-tiptext-close iconfont">&#xF028;</div>
</div>
<div class="ali-tiptext-container ali-tiptext-container-success">
    <p class="ali-tiptext ali-tiptext-success">
        <i class="ali-tiptext-icon iconfont" title="成功">&#xF047;</i>
        成功 - success
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ali-tiptext-close iconfont">&#xF028;</div>
</div>
<div class="ali-tiptext-container ali-tiptext-container-question">
    <p class="ali-tiptext ali-tiptext-question">
        <i class="ali-tiptext-icon iconfont" title="疑问">&#xF04A;</i>
        疑问 - question
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ali-tiptext-close iconfont">&#xF028;</div>
</div>
<div class="ali-tiptext-container ali-tiptext-container-stop">
    <p class="ali-tiptext ali-tiptext-stop">
        <i class="ali-tiptext-icon iconfont" title="阻止">&#xF048;</i>
        阻止 - stop
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ali-tiptext-close iconfont">&#xF028;</div>
</div>
<div class="ali-tiptext-container ali-tiptext-container-wait">
    <p class="ali-tiptext ali-tiptext-wait">
        <i class="ali-tiptext-icon iconfont" title="等待">&#xF04B;</i>
        等待 - wait
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <p class="ali-tiptext ali-tiptext-follow">
        此服务支付宝不收取任何费用。此服务支付宝真的不收取任何费用。
    </p>
    <div class="ali-tiptext-close iconfont">&#xF028;</div>
</div>
````

### 带上箭头
````html
<div class="ali-tiptext-container ali-tiptext-container-message">
    <div class="ali-tiptext-arrow ali-tiptext-arrowup">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ali-tiptext ali-tiptext-message">
        <i class="ali-tiptext-icon iconfont" title="提示">&#xF046;</i>
        提示 - message
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-error">
    <div class="ali-tiptext-arrow ali-tiptext-arrowdown">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ali-tiptext ali-tiptext-error">
        <i class="ali-tiptext-icon iconfont" title="出错">&#xF045;</i>
        出错 - error
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-warning">
    <div class="ali-tiptext-arrow ali-tiptext-arrowleft">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ali-tiptext ali-tiptext-warning">
        <i class="ali-tiptext-icon iconfont" title="警告">&#xF047;</i>
        警告 - warning
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-success">
    <div class="ali-tiptext-arrow ali-tiptext-arrowup">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ali-tiptext ali-tiptext-success">
        <i class="ali-tiptext-icon iconfont" title="成功">&#xF049;</i>
        成功 - success
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-question">
    <div class="ali-tiptext-arrow ali-tiptext-arrowdown">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ali-tiptext ali-tiptext-question">
        <i class="ali-tiptext-icon iconfont" title="疑问">&#xF04A;</i>
        疑问 - question
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-stop">
    <div class="ali-tiptext-arrow ali-tiptext-arrowleft">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ali-tiptext ali-tiptext-stop">
        <i class="ali-tiptext-icon iconfont" title="阻止">&#xF048;</i>
        阻止 - stop
    </p>
</div>
<div class="ali-tiptext-container ali-tiptext-container-wait">
    <div class="ali-tiptext-arrow ali-tiptext-arrowleft">
        <em>◆</em>
        <span>◆</span>
    </div>
    <p class="ali-tiptext ali-tiptext-wait">
        <i class="ali-tiptext-icon iconfont" title="等待">&#xF04B;</i>
        等待 - wait
    </p>
</div>
````