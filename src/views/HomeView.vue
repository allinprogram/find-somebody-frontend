<template>
  <main>
    <div class="chat chat-start">
      <div class="chat-bubble">喜欢的TA在班群分享了一首歌，<br>好好听！好想知道TA的音乐账号！<br>这样就有更多话题了。</div>
    </div>
    <div class="chat chat-end">
      <div class="chat-bubble">
        这还不简单，复制TA发的音乐链接，<br>
        到<a href="https://findneteasecloudmusicuser.nclgclub.com/start" target="_blank">找到TA！</a>，
        就能找得到TA的账号主页啦～<br>QQ音乐、网易云音乐都是支持的！
      </div>
    </div>

    <div class="chat chat-start">
      <div class="chat-bubble">真的吗，我现在就去试试看！</div>
    </div>
    <div class="chat chat-end">
      <div class="chat-bubble">
        不论是聊天中的分享链接，<br>还是分享在朋友圈或者微博的，<br>
        都可以解析喔。
      </div>
    </div>

    <div class="chat chat-start">
      <div class="chat-bubble">すごい！你太厉害了！</div>
    </div>
    <div class="chat chat-end">
      <div class="chat-bubble">
        快去试试呀，等你好消息！<br>
        有问题的话可以直接在<label for="my-modal" class="btn btn-xs btn-success">作者公众号</label>发消息寻求帮助喔。<br>后续站点迁移等消息也会在公众号进行通知，关注不失联！
        <input type="checkbox" id="my-modal" class="modal-toggle" />
        <div class="modal">
          <div class="modal-box">
            <img src="../assets/qr_code.png">
            <div class="modal-action">
              <label for="my-modal" class="btn btn-sm">
                好
              </label>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
