# 制作日誌・更新履歴

> Gitのコミットログから自動取得した武士道研究ノートの更新タイムラインです。  
> 日英対訳の考察や制作の進捗、気づきがリアルタイムに反映されます。

<div id="git-blog-container">
  <div id="git-blog-list" class="git-blog-timeline"></div>
  <div id="git-blog-footer" class="git-blog-footer">
    <div id="git-blog-loading" class="git-blog-loading" style="display: none;">
      <span class="git-blog-spinner"></span> ログを読み込み中...
    </div>
    <button id="git-blog-loadmore" class="git-blog-btn" style="display: none;">
      さらに過去の記録を読み込む
    </button>
    <div id="git-blog-end" class="git-blog-end" style="display: none;">
      すべての記録を読み込みました
    </div>
    <div id="git-blog-error" class="git-blog-error" style="display: none;"></div>
  </div>
</div>
