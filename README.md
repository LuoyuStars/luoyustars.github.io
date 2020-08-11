# luoyustars.github.io
# ---------------
# mode: light | dark | auto
mode: light

# Theme color for customize
# Notice: color value must in double quotes: "#000000"
colors:
  primary: "#0078E7"
  # primary: "#6200ee"
  bg: "#f5f5f5"
  selection_bg: "#8e71c1"
  tag_start_color: "#999999"
  tag_end_color: "#0078E7"
  dark:
    block: "#1b1f2e"
    # block: "#17202A"

# Favicon
# ---------------
favicon: /yun.svg

# ---------------------------------------------------------------
# Sidebar Settings
# ---------------------------------------------------------------

# Posts / Categories / Tags in sidebar.
sidebar:
  src: /js/sidebar.js
  bg_image: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/bg/stars-timing-1.jpg
  bg_position: bottom 1rem center
  tagcloud:
    enable: false
    amount: 20

toc:
  list_number: true
  max_depth: 6
  min_depth: 1
  # placeholder: 很遗憾，咱没写啥目录
  collapse: true

# Social Links.
social:
  - name: RSS
    # set rss in your root config
    # https://github.com/hexojs/hexo-generator-feed
    link: /atom.xml # config.feed.path
    icon: icon-rss-line
    color: orange
  - name: QQ 群
    # https://isux.tencent.com/wp-content/uploads/2016/05/20160512101222609.pdf
    link: https://shang.qq.com/wpa/qunwpa?idkey=c929e704022704d8cced9ec355d44a3fa7ad34aea12cef1de03d75d3d7d5b059
    icon: icon-qq-line
    color: "#12B7F5"
  - name: GitHub
    link: https://github.com/YunYouJun
    icon: icon-github-line
    color: "#6e5494"
  - name: 微博
    link: https://weibo.com/jizhideyunyoujun
    icon: icon-weibo-line
    color: "#E6162D"
  - name: 豆瓣
    link: https://www.douban.com/people/yunyoujun/
    icon: icon-douban-line
    color: "#007722"
  - name: 网易云音乐
    link: https://music.163.com/#/user/home?id=247102977
    icon: icon-netease-cloud-music-line
    color: "#C20C0C"
  - name: 知乎
    link: https://www.zhihu.com/people/yunyoujun/
    icon: icon-zhihu-line
    color: "#0084FF"
  - name: 哔哩哔哩
    link: https://space.bilibili.com/1579790
    icon: icon-bilibili-line
    color: "#FF8EB3"
  # - name: POPI
  #   link: https://www.popiask.cn/elpsycn
  #   icon: icon-questionnaire-line
  #   color: "#525252"
  # - name: 微信公众号
  #   link: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/about/white-qrcode-and-search.jpg
  #   icon: icon-wechat-2-line
  #   color: "#1AAD19"
  - name: Twitter
    link: https://twitter.com/YunYouJun
    icon: icon-twitter-line
    color: "#1da1f2"
  # - name: Telegram
  #   link: https://t.me/YunYouJun
  #   icon: icon-telegram-line
  #   color: "#0088CC"
  - name: Telegram Channel
    link: https://t.me/elpsycn
    # icon: icon-telegram-fill
    icon: icon-telegram-line
    color: "#0088CC"
  - name: E-Mail
    link: mailto:me@yunyoujun.cn
    icon: icon-mail-line
    color: "#8E71C1"
  - name: Travelling
    link: https://travellings.now.sh/
    icon: icon-send-plane-2-line
    color: black

codeblock:
  prismjs:
    light: default
    dark: tomorrow

# Extra links
pages:
  - name: 我的小伙伴们
    url: /links/
    icon: icon-genderless-line
    color: dodgerblue

# pages
# -------
# friend
anonymous_image: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/avatar/none.jpg

albums:
  enable: false
  icon: icon-gallery-line
  src: /js/gallery-decrypt.js

girls:
  enable: false

# Sidebar Avatar
avatar:
  enable: true
  url: /Yun.png
  # If true, the avatar would be dispalyed in circle.
  rounded: true
  # The value of opacity should be choose from 0 to 1 to set the opacity of the avatar.
  opacity: 1
  mickey_mouse: false

# main menu navigation
menu:
  home:
    path: /
    icon: icon-home-4-line
  list:
    - type: archives
      path: /archives/
      icon: icon-archive-line
    - type: categories
      path: /categories/
      icon: icon-folder-2-line
    - type: tags
      path: /tags/
      icon: icon-price-tag-3-line
  custom:
    title: 文档
    path: https://yun.yunyoujun.cn
    icon: icon-settings-line

# archive
archive:
  last_word: 没有更多的黑历史了_(:з」∠)_

wordcloud:
  enable: false
  height: 350

# You can set color for every tag or category.
tags:
  Vue: "#4fc08d"
  Hexo: "#0E83CD"
  CSS: "#5298d1"
  Node.js: "#026E00"
  Git: "#F14E32"
  React: "#61dafb"
  Python: "#3776ab"
  PHP: "#8892BF"
  VS Code: "#0066B8"
  JavaScript: "#F4DF4F"
  TypeScript: "#317AC6"
  Laravel: "#F4645F"

categories:
  笔记: dimgray

# post type
types:
  link:
    color: blue
    icon: icon-external-link-line
  bilibili:
    color: "#FF8EB3"
    icon: icon-bilibili-line
  douban:
    color: "#007722"
    icon: icon-douban-line
  github:
    color: black
    icon: icon-github-line
  netease-cloud-music:
    color: "#C10D0C"
    icon: icon-netease-cloud-music-line
  notion:
    color: black
    icon: icon-notion
  wechat:
    color: "#1AAD19"
    icon: icon-wechat-2-line
  weibo:
    color: "#E6162D"
    icon: icon-weibo-line
  yuque:
    color: "#25b864"
    icon: icon-yuque
  zhihu:
    color: "#0084FF"
    icon: icon-zhihu-line

# post_card
post_card:
  opacity: 0.8

# link
# -------
preload:
  style:
    - /css/hexo-theme-yun.css
  script:
    - /js/utils.js
    - /js/hexo-theme-yun.js

prefetch:
  script:
    - /js/sidebar.js

dns_prefetch:
  # - https://xxx

# do more(TCP handshake...) than dns-fetch
preconnect:
  - https://cdn.jsdelivr.net

# img loading="lazy"
lazyload:
  enable: true

# pjax
pjax:
  enable: false
  src: /js/pjax.js

# stylesheets loaded in the <head>
css:
  - /css/hexo-theme-yun.css

# scripts loaded in the end of the body
js:
  - /js/utils.js
  - /js/hexo-theme-yun.js

# custom your assets in head
head:
  css:
  js:
    base:
    async:
    defer:

# cdn for third-party library (always include)
cdn:
  pre: ""
  # pre: https://cdn.jsdelivr.net/gh/YunYouJun/yunyoujun.github.io
  css:
    yun-markdown-css: https://cdn.jsdelivr.net/npm/star-markdown-css@0.1.19/dist/yun/yun-markdown.min.css
    # github-markdown-css: https://cdn.jsdelivr.net/npm/github-markdown-css@4.0.0/github-markdown.css
  js:
    base:
    async:
      iconfont: //at.alicdn.com/t/font_1140697_stqaphw3j4.js
    defer:

# cdn for third-party library (alternative include)
# please see in _vendors.yml
vendors:

# UI
banner:
  enable: true
  title: 云游君的小站
  src: /js/ui/banner.js
  border: true
  cloud:
    enable: true
    color: "white"
  go_down:
    enable: true
    icon: icon-arrow-down-s-line

# You can import the font you want in the head.
font:
  cdn:
    enable: true
    lib:
      - https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@900&display=swap
  serif:
    family: "'Songti SC', 'Noto Serif SC', STZhongsong, STKaiti, KaiTi, Roboto, serif"
    weight: 900
  sans_serif:
    family: "'PingFang SC', 'Microsoft YaHei', Roboto, Arial, sans-serif"
    weight: 400
  monospace:
    family: "'Source Code Pro', 'Courier New', Courier, Consolas, Monaco, monospace"

# custom your color in fireworks
fireworks:
  enable: true
  src: /js/ui/fireworks.js
  colors:
    - "102, 167, 221"
    - "62, 131, 225"
    - "33, 78, 194"
    # - '3, 28, 95'
    # - '0, 8, 55'

# https://github.com/qrohlf/trianglify
trianglify:
  enable: false
  cell_size: 75
  width: 800
  height: 600
  # https://github.com/qrohlf/trianglify/blob/master/src/utils/colorbrewer.js
  palette: '["YlGnBu", "GnBu", "Purples", "Blues"]'
  opacity: 0.5

cursor:
  enable: false
  default: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/css/md-cursors/pointer.cur
  pointer: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/css/md-cursors/link.cur
  text: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/css/md-cursors/text.cur

smoothScroll: true

# You can see effect in https://scrollrevealjs.org/
scrollreveal:
  enable: true
  targets:
    - .post-card
    - .post-content img

bg_image:
  enable: true
  url: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/bg/stars-timing-0-blur-30px.jpg # recomend image related to your mode
  dark: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/bg/galaxy.jpg
  # blur: 30px
  opacity: 1

# Reward (Donate)
# If enable true, reward would be displayed in every posts and pages by default.
# You can show or hide reward in a specific page throuth `reward: true | false` in Front Matter.
reward:
  enable: true
  icon: icon-hand-coin-line
  comment: I'm so cute. Please give me money.
  # url: https://github.com/YunYouJun/yunyoujun.github.io/issues/96
  methods:
    - name: 支付宝
      path: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/donate/alipay-qrcode.jpg
      color: "#00A3EE"
      icon: icon-alipay-line
    - name: QQ 支付
      path: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/donate/qqpay-qrcode.png
      color: "#12B7F5"
      icon: icon-qq-line
    - name: 微信支付
      path: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/donate/wechatpay-qrcode.jpg
      color: "#2DC100"
      icon: icon-wechat-pay-line
    # - name: paypal
    #   link: https://paypal.com
    #   path: https://www.paypalobjects.com/images/shared/paypal-logo-129x32.svg
    #   color: "#2D70B5"
    #   icon: icon-paypal-line

# Creative Commons 4.0 International License.
# https://creativecommons.org/licenses/
# Available values of license: by | by-nc | by-nc-nd | by-nc-sa | by-nd | by-sa | zero
# You can set a language value if you prefer a translated version of CC license.
# CC licenses are available in 39 languages, where you can find the specific and correct abbreviation you need.
# Valid values of language: deed.zh, deed.en, deed.ja, etc.
creative_commons:
  license: by-nc-sa
  language: deed.zh
  post: true
  clipboard: false

# AddThis Share, See: https://www.addthis.com
# Go to https://www.addthis.com/dashboard to customize your tools.
# add_this_id:

# Post edit
# Dependencies: https://github.com/hexojs/hexo-deployer-git
post_edit:
  enable: false
  url: https://github.com/user-name/repo-name/tree/branch-name/subdirectory-name # Link for view source.

# Footer Settings
# ---------------
footer:
  since: 2019

  # Icon between year and copyright info.
  icon:
    # `heart` is recommended with animation in red (#ff0000).
    name: icon-cloud-line
    # If you want to animate the icon, set it to true.
    animated: true
    # Change the color of icon, using Hex Code.
    color: "#0078E7"

  powered:
    # Hexo link (Powered by Hexo).
    enable: true

  # Beian icp information for Chinese users. In China, every legal website should have a beian icp in website footer.
  # http://www.beian.miit.gov.cn
  beian:
    enable: false
    # icp: 苏ICP备xxxxxxxx号

  live_time:
    enable: false
    prefix: 本博客已萌萌哒地运行
    suffix: (●'◡'●)
    start_time: "2019-04-12T00:00:00"

  # Any custom text can be defined here.
  # custom_text: Hosted by <a href="https://pages.coding.me" rel="noopener" target="_blank">Coding Pages</a>

# Post meta display settings
post_meta:
  item_text: false
  created_at: true
  updated_at: true
  categories: true
  tags: true

# notice pin board
notice:
  enable: false
  content: Thanks for watching my blog.

# third party
# ----------------

# say something
# https://say.elpsy.cn
say:
  enable: true
  # api: https://say.elpsy.cn/sentences.json
  # /data/sentences.json
  api: https://cdn.jsdelivr.net/gh/ElpsyCN/say@gh-pages/sentences.json
  # src is the script
  src: /js/say.js
  # https://developer.hitokoto.cn/sentence/
  hitokoto:
    enable: true
    api: https://v1.hitokoto.cn
    # api: https://v1.hitokoto.cn?c=a&c=b&c=c&c=d&c=k

# you can new JSON file in your blog root folder
# example: source/data/sentences.json
# then set say.api: /data/sentences.json
# Example: https://say.elpsy.cn/sentences.json

# Comments
# -------
comment:
  enable: true
  icon: icon-chat-3-line
  tips:
    - 点击按钮跳转 GitHub Issues 评论。
    - 若没有本文 Issue，您可以使用 Comment 模版新建。

# GitHub Issues Link Button
# https://help.github.com/en/github/searching-for-information-on-github/searching-issues-and-pull-requests
github_issues:
  enable: true
  username: YunYouJun
  repository: yunyoujun.github.io
  filters: is:issue

# Valine
# You can get your appid and appkey from https://leancloud.cn
# More info available at https://valine.js.org
# extend: https://github.com/DesertsP/Valine-Admin
valine:
  enable: false
  appId: # your leancloud application appid
  appKey: # your leancloud application appkey
  placeholder: Just go go # comment box placeholder
  avatar: # gravatar style
  # meta:
  #   - nick
  #   - mail
  #   - link
  pageSize: 10 # pagination size
  # lang: zh-CN
  visitor: false
  highlight: true
  recordIP: false
  # serverURLs:
  # Emoji See: https://valine.js.org/emoji.html
  # emojiCDN: //i0.hdslb.com/bfs/emote/
  # emojiMaps:
  #   tv_doge: 6ea59c827c414b4a2955fe79e0f6fd3dcd515e24.png
  #   more...
  enableQQ: true
  # requiredFields:
  #   - nick
  #   - mail

# MiniValine
# You can get your appid and appkey from https://leancloud.cn
# More info available at https://github.com/MiniValine/MiniValine
minivaline:
  enable: false
  appId: # Your leancloud application appId
  appKey: # Your leancloud application appKey
  # mode: DesertsP # DesertsP or xCss # xCss Style mode needs to import fontawesome@5 https://github.com/YunYouJun/hexo-theme-yun/blob/dev/docs/guide/config.md#其他图标
  # placeholder: Write a Comment # Comment box placeholder
  # math: true # Support MathJax.
  # md: true # Support Markdown.
  # enableQQ: false # Enable QQ avatar API.
  # NoRecordIP: false # Do not record commenter IP.
  # visitor: true # Article reading statistics.
  # maxNest: 6 # Sub-comment maximum nesting depth.
  # pageSize: 6 # Pagination size.
  # adminEmailMd5: de8a7aa53d07e6b6bceb45c64027763d # The MD5 of Admin Email to show Admin Flag.[Just Only DesertsP Style mode] 示例： Admin 邮箱的小写 MD5
  # tagMeta: # The String Array of Words to show Flag.[Just Only xCss Style mode]
  #   - 管理员 # 示例: master tag
  #   - 小伙伴 # 示例: friends tag
  #   - 访客   # 示例: 访客 tag
  # master: # The MD5 String Array of master Email to show master Flag.[Just Only xCss Style mode]
  #   - de8a7aa53d07e6b6bceb45c64027763d # 示例： master 邮箱的小写 MD5
  # friends: # The MD5 String Array of friends Email to show friends Flag.[Just Only xCss Style mode]
  #   - b5bd5d836c7a0091aa8473e79ed4c25e # 示例： friend 邮箱的小写 MD5
  # MiniValine's display language depends on user's browser or system environment
  # If you want everyone visiting your site to see a uniform language, you can set a force language value
  # Available values: en  | zh-CN | (and many more)
  # More i18n info: https://github.com/MiniValine/minivaline-i18n
  # lang:
  # Expression Url.
  # https://github.com/MiniValine/MiniValine/blob/master/.github/FAQ.md#how-to-customize-emoticons
  # emoticonUrl:
  #   - https://cdn.jsdelivr.net/npm/alus@latest
  #   - https://cdn.jsdelivr.net/gh/MiniValine/qq@latest
  #   - https://cdn.jsdelivr.net/gh/MiniValine/Bilibilis@latest
  #   - https://cdn.jsdelivr.net/gh/MiniValine/tieba@latest
  #   - https://cdn.jsdelivr.net/gh/MiniValine/twemoji@latest
  #   - https://cdn.jsdelivr.net/gh/MiniValine/weibo@latest

# http://disqus.com/
disqus:
  enable: false
  shortname: yunyoujun
  count: false

# https://github.com/SukkaW/DisqusJS
disqusjs:
  enable: false
  shortname: yunyoujun
  count: false
  apikey:

# https://livere.com/
livere:
  enable: false
  uid:

# https://gitalk.github.io/
gitalk:
  enable: false
  clientID:
  clientSecret:
  repo:
  owner:
  admin:
  id:
  distractionFreeMode:

# https://github.com/utterance/utterances
utterances:
  enable: false
  repo:
  issue-term: pathname
  # label: comment
  theme: github-light

# Show Views / Visitors of the website / page with busuanzi.
# Get more information on http://ibruce.info/2015/04/04/busuanzi
busuanzi:
  enable: false
  site_uv: true
  site_uv_icon: icon-user-line
  site_pv: true
  site_pv_icon: icon-eye-line
  page_pv: true
  page_pv_icon: icon-eye-line

# Post wordcount
# https://github.com/willin/hexo-wordcount
wordcount:
  enable: false
  count: true
  time: true

# search
search:
  bg_image: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/bg/stars-timing-0-blur-30px.jpg
  dark_bg_image: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/bg/mountain-blur-30px.jpg
  # placeholder: 想要搜些什么？

engine_search:
  enable: false
  href: "https://www.google.com/search?q=site:"
  # href: "https://www.baidu.com/s?wd=site:"
  # href: "https://www.bing.com/search?q=site:"
  domain: yunyoujun.cn

# https://github.com/wzpan/hexo-generator-search
local_search:
  enable: false
  src: /js/search/local-search.js

# https://github.com/oncletom/hexo-algolia
algolia_search:
  enable: false
  src: /js/search/algolia-search.js
  hits:
    per_page: 8 # the number of search results per page

# Ads
# ---------------
# Google Adsense
google_adsense:
  enable: false
  client: ca-pub-2245427233262012

# Analysis
# ---------------
google_analytics:
  enable: false
  id: UA-XXXXXXXXX-X

# Google Tagmanager
google_tagmanager:
  enable: false
  id:

# That is it only render those page which has `katex: true` in Front-matter.
# math fomula
# https://katex.org/
katex:
  copy_tex: true
  global: false

# plugins
aplayer:
  global: false
  meting: true
  # https://github.com/metowolf/MetingJS/tree/v1.2#option
  widget:
    enable: false
    autoplay: false
    # theme: "#2980b9"
    loop: all
    order: list
    preload: auto
    volume: 0.7
    mutex: true
    lrcType: 0
    listFolded: false
    listMaxHeight: 340px
    audio:
      - name: 星宿计时
        artist: 杉田朗/洛天依
        url: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/audio/star-timer.mp3
        cover: https://cdn.jsdelivr.net/gh/YunYouJun/cdn/img/bg/stars-timing-0.jpg
    meting:
      enable: true
      id: 308168565
      server: netease
      type: playlist

# special
mourn:
  enable: false
  days:
    - "4-4"
    - "9-18"

# SEO
# https://ziyuan.baidu.com/linksubmit/index
baidu_push: false

# custom (You can use variables.)
custom:
  style: # source/_data/style/*

# slide
slide:
  separator: ---
  separator_vertical: "~~"
  data_separator_notes: "^Note:"
  theme: white
  config:
    history: true
    mouseWheel: false
