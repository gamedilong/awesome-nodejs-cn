# awesome-nodejs-cn

>该项目翻译至[Awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs),为大家提供一个快速查阅优秀nodejs资源的中文索引，希望能够提升大家找nodejs相关资源&项目的效率。（目前Github上已经有该项目的中文翻译了，不过只翻译了一小部分，看提交时间两年没维护了，故自己完整的翻译了一份。）

## 路线图
目前该目录索引主要来自前言提到的awesome-nodejs，后续增量的新内容有兴趣的小伙伴可以PR更新，可以提交一些自己开发的优质资源分享

## 内容

- [目录](#packages)
	- [逼格项目](#逼格项目)
	- [命令行应用](#命令行应用)
	- [函数式编程](#函数式编程)
	- [HTTP](#HTTP)
	- [调试/分析](#调试/分析)
	- [日志](#日志)
	- [命令行工具](#命令行工具)
	- [构建工具](#构建工具)
	- [硬件](#硬件)
	- [模板](#模板)
	- [Web框架](#Web框架)
	- [文档生成相关](#文档生成相关)
	- [文件系统](#文件系统)
	- [流程控制](#流程控制)
	- [流处理](#流处理)
	- [即时通信](#即时通信)
	- [图像处理](#图像处理)
	- [文本处理](#文本处理)
	- [数字](#数字)
	- [数学](#数学)
	- [日期处理](#日期处理)
	- [URL](#URL)
	- [数据校验](#数据校验)
	- [解析工具](#解析工具)
	- [人性化](#人性化)
	- [压缩](#压缩)
	- [网络](#网络)
	- [数据库](#数据库)
	- [测试相关](#测试相关)
	- [安全相关](#安全相关)
	- [基准化](#基准化)
	- [文件压缩](#文件压缩)
	- [认证方式](#认证方式)
	- [授权库](#授权库)
	- [邮箱](#邮箱)
	- [任务队列](#任务队列)
	- [Node.js管理工具](#Node.js管理工具)
	- [NLP自然语言处理](#NLP自然语言处理)
	- [进程管理](#进程管理)
	- [自动化](#自动化)
	- [AST](#AST)
	- [静态站点生成](#静态站点生成)
	- [CMS内容管理系统](#content-management-systems)
	- [论坛](#论坛)
	- [博客](#博客)
	- [序列化](#序列化)
	- [其他](#其他)
- [资源](#资源)
	- [教程](#教程)
	- [资源仓库](#资源仓库)
	- [文章](#文章)
	- [新闻](#新闻)
	- [视频](#视频)
	- [书籍](#书籍)
	- [博客](#博客)
	- [课程](#课程)
	- [备忘单](#备忘单)
	- [工具](#工具)
	- [社区](#社区)
	- [其他](#其他)
- [相关链接](#related-lists)

## 目录

### 逼格项目

- [webtorrent](https://github.com/feross/webtorrent) - 用于Nodejs 和 浏览器的磁力种子客户端.
- [peerflix](https://github.com/mafintosh/peerflix) - 磁力种子客户端.
- [dat](https://github.com/datproject/dat-node) - 数据集的实时复制和版本控制库.
- [ipfs](https://github.com/ipfs/js-ipfs) - 将所有计算设备与同一文件系统连接的分布式文件系统。
- [stackgl](https://github.com/stackgl) - WebGL的开放软件生态系统，建立在browserify和npm之上。
- [peerwiki](https://github.com/mafintosh/peerwiki) - 种子维基百科.
- [peercast](https://github.com/mafintosh/peercast) - 种子视频流式传输到Chromecast工具.
- [BitcoinJS](https://github.com/bitcoinjs/bitcoinjs-lib) - 干净，可读，经过验证的比特币库.
- [Bitcore](https://github.com/bitpay/bitcore) - 强大的纯比特币库.
- [PDFKit](https://github.com/devongovett/pdfkit) - PDF生成库.
- [turf](https://github.com/Turfjs/turf) - 模块化地理空间处理和分析引擎.
- [webcat](https://github.com/mafintosh/webcat) - 使用WebRTC在Web上通过p2p管道，该WebRTC使用GitHub私钥/公钥进行身份验证.
- [NodeOS](https://github.com/NodeOS/NodeOS) - 基于Node的操作系统.
- [YodaOS](https://github.com/yodaos-project/yodaos) - AI操作系统.
- [Brain.js](https://github.com/BrainJS/brain.js) - 机器学习框架.
- [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - 图论（又称网络）建模和分析.
- [Kadence](https://gitlab.com/deadcanaries/kadence) - Kademlia分布式哈希表.
- [seedshot](https://github.com/twobucks/seedshot) - 通过浏览器共享临时P2P屏幕截图.
- [js-git](https://github.com/creationix/js-git) - JS版Git实现.
- [skale](https://github.com/skale-me/skale-engine) - 高性能分布式数据处理引擎.
- [xlsx](https://github.com/sheetjs/js-xlsx) - 纯JS Excel电子表格阅读器和编写器.
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) - Git的纯JavaScript实现.

### 命令行应用

- [np](https://github.com/sindresorhus/np) - 更好的 `npm publish`.
- [npm-name](https://github.com/sindresorhus/npm-name) - 在npm上检查软件包名称的可用性.
- [gh-home](https://github.com/sindresorhus/gh-home) - 在当前目录中打开仓库的GitHub页面.
- [npm-home](https://github.com/sindresorhus/npm-home) - 打开软件包的npm页面.
- [trash](https://github.com/sindresorhus/trash) -  比`rm`更安全的替代命令.
- [speed-test](https://github.com/sindresorhus/speed-test) - 测试您的互联网连接速度和ping.
- [emoj](https://github.com/sindresorhus/emoj) - 在命令行上的文本中找到相关的表情符号.
- [pageres](https://github.com/sindresorhus/pageres) - 捕获网站截图.
- [cpy](https://github.com/sindresorhus/cpy) - 文件拷贝.
- [vtop](https://github.com/MrRio/vtop) - 顶部更好，图表更漂亮的命令行的图形活动监视器。.
- [empty-trash](https://github.com/sindresorhus/empty-trash) - 清空垃圾.
- [is-up](https://github.com/sindresorhus/is-up) - 检查网站是否正常.
- [is-online](https://github.com/sindresorhus/is-online) - 检查互联网连接是否正常.
- [public-ip](https://github.com/sindresorhus/public-ip) - 获取你的公共IP地址.
- [clipboard-cli](https://github.com/sindresorhus/clipboard-cli) - 复制并粘贴到终端上.
- [XO](https://github.com/xojs/xo) - 使用JavaScript幸福样式强制执行严格的代码样式.
- [Standard](https://github.com/feross/standard) -JavaScript标准样式-一种统治所有样式的样式.
- [ESLint](https://github.com/eslint/eslint) - JavaScript的可插入linting实用程序.
- [dev-time](https://github.com/samverschueren/dev-time-cli) - 获取GitHub用户的当前本地时间.
- [David](https://github.com/alanshaw/david) - 告诉您您的软件包npm依赖项何时过时.
- [http-server](https://github.com/indexzero/http-server) - 简单的零配置命令行HTTP服务器.
- [Live Server](https://github.com/tapio/live-server) - 具有livereload功能的开发HTTP服务器.
- [bcat](https://github.com/kessler/node-bcat) -将命令输出管道传输到Web浏览器.
- [normit](https://github.com/pawurb/normit) - 在您的终端中使用语音合成功能进行Google翻译.
- [fkill](https://github.com/sindresorhus/fkill-cli) - 跨平台的进程强杀命令.
- [pjs](https://github.com/danielstjules/pjs) - 可移植的JavaScript。 从终端快速过滤，映射和缩小.
- [license-checker](https://github.com/davglass/license-checker) - 检查应用程序依赖项的许可证.
- [browser-run](https://github.com/juliangruber/browser-run) - 在浏览器环境中轻松运行代码.
- [tmpin](https://github.com/sindresorhus/tmpin) - 将stdin支持添加到任何接受文件输入的CLI应用程序.
- [wifi-password](https://github.com/kevva/wifi-password-cli) - 获取当前的wifi密码.
- [wallpaper](https://github.com/sindresorhus/wallpaper) - 更改桌面墙纸.
- [brightness](https://github.com/kevva/brightness-cli) - 更改屏幕亮度.
- [torrent](https://github.com/maxogden/torrent) - 种子下载命令.
- [kill-tabs](https://github.com/sindresorhus/kill-tabs) - 取消所有Chrome标签页，以提高性能，减少电池使用量并节省内存.
- [alex](https://github.com/wooorm/alex) - 捕捉不敏感，不体贴的文字.
- [pen](https://github.com/noraesae/pen) - 通过您喜欢的编辑器在浏览器中进行实时Markdown预览.
- [subdownloader](https://github.com/beatfreaker/subdownloader) - 电影和电视剧字幕下载器.
- [dark-mode](https://github.com/sindresorhus/dark-mode) - 切换macOS暗模式.
- [iponmap](https://github.com/nogizhopaboroda/iponmap) - IP位置查找器.
- [Jsome](https://github.com/Javascipt/Jsome) - 漂亮地打印带有可配置颜色和缩进的JSON命令.
- [itunes-remote](https://github.com/mischah/itunes-remote) - 交互式控制iTunes.
- [mobicon](https://github.com/samverschueren/mobicon-cli) - 移动应用程序图标生成器.
- [mobisplash](https://github.com/samverschueren/mobisplash-cli) - 移动应用启动画面生成器.
- [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) - 漂亮的git diff与HTML生成器.
- [Cash](https://github.com/dthree/cash) - 纯JavaScript中的跨平台Unix Shell命令.
- [trymodule](https://github.com/VictorBjelkholm/trymodule) - 在终端中试用npm软件包.
- [jscpd](https://github.com/kucherenko/jscpd) - 复制/粘贴检测器以获取源代码.
- [atmo](https://github.com/Raathigesh/Atmo) - 服务器端API模拟.
- [auto-install](https://github.com/siddharthkp/auto-install) - 在编码时自动安装依赖项.
- [lessmd](https://github.com/linuxenko/lessmd) - 终端中的降价.
- [cost-of-modules](https://github.com/siddharthkp/cost-of-modules) - 找出哪些依赖性使项目性能降低的库.
- [localtunnel](https://github.com/localtunnel/localtunnel) - 将你的本地主机公开命令.
- [svg-term-cli](https://github.com/marionebl/svg-term-cli) - 通过SVG分享终端会话.
- [gtop](https://github.com/aksakalli/gtop) - 终端的系统监控仪表板.
- [themer](https://github.com/mjswensen/themer) - 为您的编辑器，终端，墙纸，Slack等生成主题.
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - 代码的精美图片-从终端内部开始.
- [cash-cli](https://github.com/xxczaki/cash-cli) - 170种货币之间转换命令.
- [taskbook](https://github.com/klauscfhq/taskbook) - 命令行栖息地的任务，公告板和注释.
- [discharge](https://github.com/brandonweiss/discharge) - 轻松将静态网站部署到Amazon S3.
- [npkill](https://github.com/voidcosmos/npkill) - 轻松查找和删除旧的沉重的node_modules文件夹.

### 函数式编程

- [lodash](https://github.com/lodash/lodash) -  可提供一致性，自定义，性能和其他功能的实用程序库。 更好更快的Underscore.js.
- [immutable](https://github.com/facebook/immutable-js) - 不变的数据收集.
- [Ramda](https://github.com/ramda/ramda) - 实用程序库着重于通过自动计算和相反的参数顺序实现的灵活功能组合。 避免变异数据.
- [Folktale](https://github.com/origamitower/folktale) - 一套用于JavaScript中的通用函数编程的库，它允许您编写优雅的、模块化的应用程序，并且bug更少，重用性更强。.
- [Mout](https://github.com/mout/mout) - 该库与其他现有解决方案之间最大的区别是，您可以选择只加载需要的模块/函数，而不需要额外开销。.
- [Bacon.js](https://github.com/baconjs/bacon.js) - 函数式响应式编程.
- [RxJS](https://github.com/reactivex/rxjs) - 用于转换、组合和查询各种数据的函数式响应式库.
- [Lazy.js](https://github.com/dtao/lazy.js) - 类似于lodash/underline的工具库，但具有惰性计算，在许多情况下可以转换为卓越的性能.
- [Kefir.js](https://github.com/kefirjs/kefir) - 响应式库，专注于高性能和低内存使用.
- [immer](https://github.com/immerjs/immer) 不可变数据的特性 

### HTTP

- [got](https://github.com/sindresorhus/got) - 更好的内置“http”模块接口.
- [gh-got](https://github.com/sindresorhus/gh-got) - “got”与GitHub API交互的方便包装.
- [axios](https://github.com/mzabriskie/axios) - 基于Promise 的HTTP客户端（也可以在浏览器中工作）.
- [request](https://github.com/request/request) - 简单的 HTTP 请求客户端.
- [wreck](https://github.com/hapijs/wreck) - HTTP 客户端工具.
- [download](https://github.com/kevva/download) - 轻松下载和提取文件.
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - HTTP代理.
- [superagent](https://github.com/visionmedia/superagent) - HTTP请求库.
- [node-fetch](https://github.com/bitinn/node-fetch) - Node.js的`window.fetch` .
- [flashheart](https://github.com/bbc/flashheart) - REST 客户端.
- [http-fake-backend](https://github.com/micromata/http-fake-backend) - 通过可配置的路线提供JSON文件或JavaScript对象的内容来构建伪造的后端.
- [cacheable-request](https://github.com/lukechilds/cacheable-request) - 使用符合RFC的缓存支持包装本机HTTP请求.
- [gotql](https://github.com/khaosdoctor/gotql) - 基于[got]构建的GraphQL请求库(https://github.com/sindresorhus/got).
- [global-agent](https://github.com/gajus/global-agent) - 可以使用环境变量配置的全局HTTP / HTTPS代理.

### 调试/分析

- [ndb](https://github.com/GoogleChromeLabs/ndb) - Chrome DevTools调试体验改进工具.
- [ironNode](https://github.com/s-a/iron-node) - 支持ES2015的Node.js开箱即用的调试器.
- [node-inspector](https://github.com/node-inspector/node-inspector) - 基于Blink 开发者工具的调试器.
- [debug](https://github.com/visionmedia/debug) - 轻量调试工具.
- [why-is-node-running](https://github.com/mafintosh/why-is-node-running) - 当不明Node原因继续运行时，使用的分析工具
- [njsTrace](https://github.com/valyouw/njstrace) - 检测并跟踪代码，查看所有函数调用、参数、返回值以及在每个函数中花费的时间.
- [vstream](https://github.com/joyent/node-vstream) -可检测的流混入以检查流的管道.
- [stackman](https://github.com/watson/stackman) - E使用代码摘录和其他优点增强错误堆栈跟踪.
- [locus](https://github.com/alidavut/locus) - 在运行时启动可访问所有变量的REPL.
- [0x](https://github.com/davidmarkclements/0x) - 火焰图分析.
- [ctrace](https://github.com/automation-stack/ctrace) - 格式正确且经过改进的跟踪系统调用和信号.
- [leakage](https://github.com/andywer/leakage) - 写入内存泄漏测试.
- [llnode](https://github.com/nodejs/llnode) - 事后分析工具，使您可以检查对象并从崩溃的Node.js进程中获取见解.
- [thetool](https://github.com/sfninja/thetool) - 以Chrome DevTools友好格式为您的应用捕获不同的CPU，内存和其他配置文件.
- [swagger-stats](https://github.com/slanatech/swagger-stats) - 跟踪API调用并监视API性能，运行状况和使用情况指标.

### 日志

- [pino](https://github.com/pinojs/pino) - 受Bunyan启发的超快速记录器.
- [winston](https://github.com/winstonjs/winston) - 多传输异步日志记录库.
- [console-log-level](https://github.com/watson/console-log-level) - 可以想象的最简单的记录器，支持日志级别和自定义前缀.
- [storyboard](https://github.com/guigrpa/storyboard) -端到端，分层，实时，丰富多彩的日志和故事.
- [signale](https://github.com/klauscfhq/signale) - 具有漂亮输出的控制台记录器.

### 命令行工具

- [chalk](https://github.com/chalk/chalk) - 终端字符串样式工具.
- [meow](https://github.com/sindresorhus/meow) - CLI App帮助工具.
- [yargs](https://github.com/yargs/yargs) - 自动生成优雅用户界面的命令行解析器.
- [ora](https://github.com/sindresorhus/ora) - 优雅的终端旋转进度条.
- [get-stdin](https://github.com/sindresorhus/get-stdin) - 简单的 stdin输出.
- [log-update](https://github.com/sindresorhus/log-update) - 通过覆盖终端中的上一个输出来记录。用于渲染进度条、动画等.
- [Ink](https://github.com/vadimdemedes/ink) - 用于交互式命令行的react apps.
- [listr](https://github.com/samverschueren/listr) - 终端任务列表.
- [conf](https://github.com/sindresorhus/conf) - 应用程序或模块的简单配置处理.
- [ansi-escapes](https://github.com/sindresorhus/ansi-escapes) - 操作终端的ANSI转义代码.
- [log-symbols](https://github.com/sindresorhus/log-symbols) - 不同日志级别的彩色符号.
- [figures](https://github.com/sindresorhus/figures) - Windows CMD后备的Unicode符号.
- [boxen](https://github.com/sindresorhus/boxen) - 在终端中创建框.
- [terminal-link](https://github.com/sindresorhus/terminal-link) - 终端创建可点击链接.
- [terminal-image](https://github.com/sindresorhus/terminal-image) - 终端展示图片.
- [string-width](https://github.com/sindresorhus/string-width) - 获取字符串的可视宽度-显示字符串所需的列数.
- [cli-truncate](https://github.com/sindresorhus/cli-truncate) - 在终端中将字符串截断为特定宽度.
- [first-run](https://github.com/sindresorhus/first-run) - 检查是否是第一次运行该进程.
- [blessed](https://github.com/chjj/blessed) - 具有node.js高级终端接口API的类似于curses的库。.
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) - 交互式的命令行弹框.
- [yn](https://github.com/sindresorhus/yn) - 解析 yes/no 像值.
- [cli-table3](https://github.com/cli-table/cli-table3) - 漂亮的unicode表.
- [drawille](https://github.com/madbence/node-drawille) - 使用Unicode盲文字符在终端上绘图.
- [update-notifier](https://github.com/yeoman/update-notifier) - 更新CLI应用程序的通知.
- [ascii-charts](https://github.com/jstrace/chart) - 终端中的ASCII条形图.
- [progress](https://github.com/tj/node-progress) - 灵活的ascii进度栏.
- [insight](https://github.com/yeoman/insight) - 通过向Google Analytics（分析）匿名报告使用情况指标来帮助您了解工具的使用情况.
- [cli-cursor](https://github.com/sindresorhus/cli-cursor) - 切换CLI光标.
- [columnify](https://github.com/timoxley/columnify) - 创建适合控制台输出的基于文本的列。 支持单元包裹.
- [cli-columns](https://github.com/shannonmoeller/cli-columns) - 列式Unicode和Ansi安全文本列表.
- [cfonts](https://github.com/dominikwilkowski/cfonts) - 性感的控制台ASCII字体.
- [multispinner](https://github.com/codekirei/node-multispinner) - 多个可同时单独控制的CLI进度加载器.
- [omelette](https://github.com/f/omelette) - Shell自动完成帮助程序.
- [cross-env](https://github.com/kentcdodds/cross-env) - 跨平台的环境变量设置.
- [shelljs](https://github.com/shelljs/shelljs) - 可移植的Unix shell命令.
- [sudo-block](https://github.com/sindresorhus/sudo-block) - 阻止用户用root权限使用你的程序.
- [loud-rejection](https://github.com/sindresorhus/loud-rejection) - 显示处理没有控制的promise rejections 失败，替代默认的静默失败方式.
- [sparkly](https://github.com/sindresorhus/sparkly) - 生成迷你图 `▁▂▃▅▂▇`.
- [Bit](https://github.com/teambit/bit) - 在存储库中创建，维护，查找和使用小型模块和组件.
- [gradient-string](https://github.com/bokub/gradient-string) - 终端中输出漂亮的色彩渐变.
- [oclif](https://github.com/oclif/oclif) - CLI框架，包括解析器，自动文档，测试和插件.
- [term-size](https://github.com/sindresorhus/term-size) - 可靠地获得终端窗口大小.
- [Cliffy](https://github.com/drew-y/cliffy) - 交互式CLI的框架.

### 构建工具

- [parcel](https://github.com/parcel-bundler/parcel) - 快速，零配置的Web应用构建工具.
- [webpack](https://github.com/webpack/webpack) - 打包浏览器的模块和资产.
- [rollup](https://github.com/rollup/rollup) - 新一代的 ES2015 打包构建工具.
- [gulp](https://github.com/gulpjs/gulp) - 流式快速构建系统，支持代码而不是配置.
- [Broccoli](https://github.com/broccolijs/broccoli) - 快速、可靠的资产管道，支持固定时间重建和紧凑的构建定义.
- [Brunch](https://github.com/brunch/brunch) - 前端web应用程序构建工具，具有简单的声明性配置、快速的增量编译和自定的工作流.
- [Start](https://github.com/deepsweet/start) - 具有可共享预设的功能性任务管理器.
- [ygor](https://github.com/shannonmoeller/ygor) - `npm run`不够用时的补充工具.
- [FuseBox](https://github.com/fuse-box/fuse-box) - 快速构建系统，结合了webpack，JSPM和SystemJS的强大功能，并具有一流的TypeScript支持.
- [pkg](https://github.com/zeit/pkg) - 将你的Node.js项目打包成可执行文件.

### 硬件

- [johnny-five](https://github.com/rwaldron/johnny-five) - 基于Firmata的Arduino框架.
- [serialport](https://github.com/voodootikigod/node-serialport) - 访问串行端口以进行读写.
- [usb](https://github.com/nonolith/node-usb) - USB 库.
- [i2c-bus](https://github.com/fivdi/i2c-bus) - I2C串行总线访问.
- [onoff](https://github.com/fivdi/onoff) - GPIO访问和中断检测.
- [spi-device](https://github.com/fivdi/spi-device) - SPI串行总线访问.
- [pigpio](https://github.com/fivdi/pigpio) - Raspberry Pi上的快速GPIO，PWM，伺服控制，状态更改通知和中断处理.
- [gps](https://github.com/infusion/GPS.js) - NMEA解析器，用于处理GPS接收器.

### 模板

- [marko](https://github.com/marko-js/marko) - 基于HTML的模板引擎，可将模板编译为CommonJS模块，并支持流，异步渲染和自定义标签.
- [nunjucks](https://github.com/mozilla/nunjucks) - 具有继承，异步控制等功能的模板引擎（受Jinja2启发）.
- [handlebars.js](https://github.com/wycats/handlebars.js) - Mustache模板的超集，其中添加了强大的功能，如助手和更高级的块.
- [EJS](https://github.com/mde/ejs) - 超级简单的模板语言.
- [Pug](https://github.com/pugjs/pug) - 受Haml影响的高性能模板引擎.

### Web框架

- [Hapi](https://github.com/hapijs/hapi) - 用于创建应用服务的框架.
- [Koa](https://github.com/koajs/koa) - 由Express背后的团队设计的框架，旨在为Web应用程序和API提供更小，更富表现力和更强大的基础.
- [Express](https://github.com/expressjs/express) - Web应用程序框架，为构建单页和多页以及混合Web应用程序提供了一组强大的功能.
- [Feathers](https://github.com/feathersjs/feathers) - 本着Express精神构建的微服务框架.
- [LoopBack](https://github.com/strongloop/loopback) - 用于创建REST API并轻松连接到后端数据源的强大框架.
- [Meteor](https://github.com/meteor/meteor) - 
-超简单，无处不在的数据库，在线数据，纯Javascript Web框架。 *（你可能会喜欢 [awesome-meteor](https://github.com/Urigo/awesome-meteor))*
- [Restify](https://github.com/restify/node-restify) - 使你能够构建正确的REST Web服务。
- [ThinkJS](https://github.com/thinkjs/thinkjs) - 支持ES2015 +的框架，WebSockets，REST API.
- [ActionHero](https://github.com/actionhero/actionhero) - 用于为TCP套接字，WebSocket和HTTP客户端制作可重用和可扩展的API的框架.
- [Next.js](https://github.com/zeit/next.js) - React服务端渲染框架.
- [Nuxt.js](https://github.com/nuxt/nuxt.js) - Vue服务端渲染框架.
- [seneca](https://github.com/senecajs/seneca) - 编写微服务的工具包.
- [AdonisJs](http://adonisjs.com) - 基于依赖注入和IoC容器的坚实基础构建的Node.js的真正MVC框架.
- [Hemera](https://github.com/hemerajs/hemera) -使用以下工具编写可靠且容错的微服务 [NATS](https://nats.io).
- [Micro](https://github.com/zeit/micro) - 具有异步方法的简约微服务框架.
- [Moleculer](https://moleculer.services) - 快速而强大的微服务框架.
- [Fastify](https://github.com/fastify/fastify) - 快速和低开销的Web框架.
- [Nest](https://github.com/nestjs/nest) -受Angular启发的框架，用于构建高效且可扩展的服务器端应用程序.
- [Zeronode](https://github.com/sfast/zeronode) - 最小的构建块，可实现可靠且容错的微服务.
- [TypeGraphQL](https://github.com/19majkel94/type-graphql) - 使用类和装饰器使用TypeScript创建GraphQL API的现代框架.

### 文档生成相关

- [documentation.js](https://github.com/documentationjs/documentation) - API文档生成器，支持ES2015 +和流程注释.
- [ESDoc](https://github.com/esdoc/esdoc) - 针对ES2015的文档生成器，附加测试代码并衡量文档覆盖范围.
- [Docco](https://github.com/jashkenas/docco) - 文档生成器，该生成器生成一个HTML文档，该文档显示与代码混合的注释.
- [JSDoc](https://github.com/jsdoc3/jsdoc) - API文档生成器，类似于JavaDoc或PHPDoc.

### 文件系统

- [del](https://github.com/sindresorhus/del) - 使用Glob删除文件/文件夹.
- [globby](https://github.com/sindresorhus/globby) - 支持多种模式的Glob文件s.
- [cpy](https://github.com/sindresorhus/cpy) - 文件拷贝.
- [rimraf](https://github.com/isaacs/rimraf) - 递归删除rm -rf之类的文件.
- [make-dir](https://github.com/sindresorhus/make-dir) - 像`mkdir -p`一样递归创建目录.
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - 具有各种改进功能的fs模块的直接替代品.
- [chokidar](https://github.com/paulmillr/chokidar) - 
稳定来自fs.watch和fs.watchFile的事件以及在macOS上使用本机fsevents的文件系统监视程序.
- [find-up](https://github.com/sindresorhus/find-up) - 通过上级父目录查找文件.
- [proper-lockfile](https://github.com/IndigoUnited/node-proper-lockfile) - 进程间和机器间锁文件工具.
- [load-json-file](https://github.com/sindresorhus/load-json-file) - 读取解析JSON文件.
- [write-json-file](https://github.com/sindresorhus/write-json-file) - 自动序列化写入JSON到文件.
- [fs-write-stream-atomic](https://github.com/npm/fs-write-stream-atomic) - 类似 `fs.createWriteStream()`, 但是原子的操作.
- [filenamify](https://github.com/sindresorhus/filenamify) - 将字符串转换为有效的文件名.
- [lnfs](https://github.com/kevva/lnfs) - 像`ln -fs`一样，强制创建符号链接.
- [istextorbinary](https://github.com/bevry/istextorbinary) - 检查文件是文本还是二进制.
- [fs-jetpack](https://github.com/szwacz/fs-jetpack) - 完全重新设计的文件系统API，方便日常使用.
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - fs模块的额外方法.
- [pkg-dir](https://github.com/sindresorhus/pkg-dir) - 查找npm包的根目录.
- [filehound](https://github.com/nspragg/filehound) - 用于文件系统搜索的灵活流畅的接口.
- [move-file](https://github.com/sindresorhus/move-file) - 移动文件，甚至可以跨设备使用.
- [tempy](https://github.com/sindresorhus/tempy) - 获取随机的临时文件或目录路径.

### 流程控制

- Promises
	- [Bluebird](https://github.com/petkaantonov/bluebird) - 致力于创新功能和性能的Promise库.
	- [pify](https://github.com/sindresorhus/pify) - Promisify化回调形式的函数.
	- [delay](https://github.com/sindresorhus/delay) - 将Promise延迟指定的时间.
	- [更多](https://github.com/sindresorhus/promise-fun)
- Observables
	- [zen-observable](https://github.com/zenparsing/zen-observable) - 观察者模式实现.
	- [RxJS](https://github.com/ReactiveX/RxJS) - 响应式编程.
	- [observable-to-promise](https://github.com/sindresorhus/awesome-observables) - 将可观察者转换为Promise.
	- [更多…](https://github.com/sindresorhus/awesome-observables)
- Streams
	- [Highland.js](https://github.com/caolan/highland) - 仅使用标准JavaScript和类似Node的流，即可轻松管理同步和异步代码.
- Callbacks
	- [each-async](https://github.com/sindresorhus/each-async) - 异步并发迭代器，如forEach.
	- [async](https://github.com/caolan/async) - 提供简单，强大的功能来处理异步问题.
- Channels
	- [js-csp](https://github.com/ubolonton/js-csp) - 为JavaScript通信顺序过程（例如Clojurescript core.async或Go）。

### 流处理

- [through2](https://github.com/rvagg/through2) - 轻量的流包装器.
- [from2](https://github.com/hughsk/from2) - ReadableStream方便的流包装 , 灵感来自于 `through2`.
- [get-stream](https://github.com/sindresorhus/get-stream) - 获取流作为字符串或缓冲区.
- [into-stream](https://github.com/sindresorhus/into-stream) - 将 buffer/string/array/object 转化为流.
- [duplexify](https://github.com/mafintosh/duplexify) - 将可写和可读流转换为单个stream2双工流。.
- [pumpify](https://github.com/mafintosh/pumpify) - 将一系列流合并为单个双工流.
- [peek-stream](https://github.com/mafintosh/peek-stream) - 转换流，使您可以先决定第一行，然后再决定如何解析它.
- [binary-split](https://github.com/maxogden/binary-split) - 换行符（或任何定界符）分隔符流
- [byline](https://github.com/jahewson/node-byline) - 超简单的逐行流读取器.
- [first-chunk-stream](https://github.com/sindresorhus/first-chunk-stream) - 转换流中的第一个块.
- [pad-stream](https://github.com/sindresorhus/pad-stream) - 填充流中的每一行.
- [multistream](https://github.com/feross/multistream) - 
将多个流合并为一个流.
- [stream-combiner2](https://github.com/substack/stream-combiner2) - 流水线成一个流.
- [readable-stream](https://github.com/nodejs/readable-stream) - Streams2 and Streams3 核心实现镜像.
- [through2-concurrent](https://github.com/almost/through2-concurrent) - 同时转换对象流.

### 即时通信

- [µWebSockets](https://github.com/uWebSockets/uWebSockets) - 高度可扩展的WebSocket服务器和客户端库.
- [Socket.io](https://github.com/socketio/socket.io) - 实现基于事件的实时双向通信.
- [Faye](https://github.com/faye/faye) - 基于Bayeux协议的实时客户端-服务器消息总线.
- [SocketCluster](https://github.com/SocketCluster/socketcluster) - 可扩展的HTTP + WebSocket引擎，可以在多个CPU内核上运行.
- [Primus](https://github.com/primus/primus) - 实时框架的抽象层，以防止模块锁定.
- [deepstream.io](https://github.com/deepstreamIO/deepstream.io-client-js) - 可扩展的实时微服务框架.
- [Kalm](https://github.com/kalm/kalm.js) - 低级套接字路由器和中间件框架.
- [MQTT.js](https://github.com/mqttjs/MQTT.js) - MQTT客户端-基于Pub-sub的消息协议，用于TCP / IP.
- [rpc-websockets](https://github.com/elpheria/rpc-websockets) - 通过WebSocket实现JSON-RPC 2.0.
- [Aedes](https://github.com/mcollina/aedes) - 可以在任何流服务器上运行的准系统MQTT服务器.

### 图像处理

- [sharp](https://github.com/lovell/sharp) - 调整JPEG，PNG，WebP和TIFF图像大小的最快模块.
- [image-type](https://github.com/sindresorhus/image-type) - 检测Buffer / Uint8Array的图像类型.
- [gm](https://github.com/aheckmann/gm) - GraphicsMagick和ImageMagick包装器.
- [lwip](https://github.com/EyalAr/lwip) - 不需要ImageMagick的轻量级图像处理器.
- [pica](https://github.com/nodeca/pica) -
纯JS中的高质量和快速调整大小（lanczos3）。 当不允许像素化时替代canvas drawImage（）.
- [jimp](https://github.com/oliver-moran/jimp) - 纯JavaScript中的图像处理.
- [probe-image-size](https://github.com/nodeca/probe-image-size) - 无需完全下载即可获取大多数图像格式的大小.
- [qrcode](https://github.com/soldair/node-qrcode) - QR码和条形码生成器.

### 文本处理

- [iconv-lite](https://github.com/ashtuchkin/iconv-lite) - 转换字符编码.
- [string-length](https://github.com/sindresorhus/string-length) - 获取字符串的真实长度-通过正确计算星号并忽略ansi转义码.
- [camelcase](https://github.com/sindresorhus/camelcase) - 将破折号/点号/下划线/空格分隔的字符串转换为驼峰式,案例：foo-bar→fooBar.
- [escape-string-regexp](https://github.com/sindresorhus/escape-string-regexp) - 转义RegExp特殊字符.
- [execall](https://github.com/sindresorhus/execall) - 在字符串中查找多个RegExp匹配项.
- [splice-string](https://github.com/sindresorhus/splice-string) - 移除或替换字符串的一部分`Array#splice`.
- [indent-string](https://github.com/sindresorhus/indent-string) - 缩进字符串中的每一行.
- [strip-indent](https://github.com/sindresorhus/strip-indent) - 从字符串的每一行中除去前导空格.
- [detect-indent](https://github.com/sindresorhus/detect-indent) - 检测代码缩进.
- [he](https://github.com/mathiasbynens/he) - HTML实体编码器/解码器.
- [i18n-node](https://github.com/mashpie/i18n-node) - 具有动态JSON存储的简单翻译模块.
- [babelfish](https://github.com/nodeca/babelfish) - i18n，复数的语法非常简单.
- [matcher](https://github.com/sindresorhus/matcher) - 简单通配符匹配.
- [unhomoglyph](https://github.com/nodeca/unhomoglyph) - 规范化视觉上相似的unicode字符.
- [i18next](https://github.com/i18next/i18next) - 国际化框架.
- [nanoid](https://github.com/ai/nanoid) - 小巧、安全、URL友好、唯一的字符串ID生成器.

### 数字

- [random-int](https://github.com/sindresorhus/random-int) - 生成随机整数.
- [random-float](https://github.com/sindresorhus/random-float) - 生成随机浮点数.
- [unique-random](https://github.com/sindresorhus/unique-random) - 生成连续唯一的随机数.
- [round-to](https://github.com/sindresorhus/round-to) - 将数字四舍五入到指定的小数位数：`1.234`→1.2`.

### 数学

- [ndarray](https://github.com/scijs/ndarray) - 多维数组.
- [mathjs](https://github.com/josdejong/mathjs) - 广泛的数学图书馆.
- [math-clamp](https://github.com/sindresorhus/math-clamp) - 钳制一个数字.
- [algebra](https://github.com/fibo/algebra) - 代数结构.
- [multimath](https://github.com/nodeca/multimath) - 在WebAssembly和JS中创建快速图像数学的核心.
- [decimal.js](https://github.com/MikeMcl/decimal.js) - 浮点计算.

### 日期处理

- [Luxon](https://github.com/moment/luxon) - 用于处理日期和时间的库.
- [date-fns](https://github.com/date-fns/date-fns) - 现代日期工具.
- [Moment.js](http://momentjs.com) - 分析、验证、操作和显示日期.
- [Day.js](https://github.com/iamkun/dayjs) - Moment.js之外的不可变日期库.
- [dateformat](https://github.com/felixge/node-dateformat) - 日期格式化.
- [tz-format](https://github.com/samverschueren/tz-format) - 通过时区格式化时间: `2015-11-30T10:40:35+01:00`.
- [cctz](https://github.com/floatdrop/node-cctz) - 快速解析, 格式化, 和时区转化工具.

### URL

- [normalize-url](https://github.com/sindresorhus/normalize-url) - 规范化 URL.
- [humanize-url](https://github.com/sindresorhus/humanize-url) - 可读化 URL: http://sindresorhus.com → sindresorhus.com.
- [url-unshort](https://github.com/nodeca/url-unshort) - 扩展锻炼URL.
- [speakingurl](https://github.com/pid/speakingurl) - 通过音译从字符串生成子段.
- [linkify-it](https://github.com/markdown-it/linkify-it) - 具有完整Unicode支持的链接模式检测器.
- [url-pattern](https://github.com/snd/url-pattern) - 比regex字符串更容易匹配url和其他字符串的模式.
- [embedza](https://github.com/nodeca/embedza) - 使用oEmbed、Open Graph、meta标记中的信息从url创建HTML片段/嵌入

### 数据校验

- [joi](https://github.com/hapijs/joi) - JavaScript对象的对象模式描述语言和验证器.
- [is-my-json-valid](https://github.com/mafintosh/is-my-json-valid) - 急速JSON格式校验工具.
- [property-validator](https://github.com/nettofarah/property-validator) - Express的属性校验工具.
- [schema-inspector](https://github.com/Atinux/schema-inspector) - JSON API清理和验证.
- [ajv](https://github.com/epoberezkin/ajv) - 最快的JSON模式验证程序。支持v5、v6和v7方案.

### 解析工具

- [remark](https://github.com/wooorm/remark) - Markdown插件.
- [markdown-it](https://github.com/markdown-it/markdown-it) - Markd支持100%通用Markdown标签解析的扩展&语法插件.
- [parse5](https://github.com/inikulin/parse5) - 快速全功能规范兼容的HTML解析器.
- [strip-json-comments](https://github.com/sindresorhus/strip-json-comments) - JSON注释剔除工具.
- [strip-css-comments](https://github.com/sindresorhus/strip-css-comments) - CSS注释剔除工具.
- [parse-json](https://github.com/sindresorhus/parse-json) -  JSON更多错误信息提示工具.
- [URI.js](https://github.com/medialize/URI.js) - URL 处理工具.
- [PostCSS](https://github.com/postcss/postcss) - CSS 解析工具.
- [JSONStream](https://github.com/dominictarr/JSONStream) -  JSON.parse&stringify流处理工具.
- [csv-parser](https://github.com/mafintosh/csv-parser) - 旨在比其他任何人都快的流式CSV解析器.
- [PEG.js](https://github.com/pegjs/pegjs) - 简单的语法分析器生成器，可以生成快速的语法分析器，并具有出色的错误报告功能.
- [x-ray](https://github.com/lapwinglabs/x-ray) - Web 爬虫工具.
- [nearley](https://github.com/Hardmath123/nearley) - 简单，快速，强大的JavaScript解析器.
- [binary-extract](https://github.com/juliangruber/binary-extract) - 从JSON缓冲区中提取一个值而无需解析整个对象的工具.
- [Stylecow](https://github.com/stylecow/stylecow) - 解析，操纵和转换现代CSS，使其与所有浏览器兼容。 可扩展的插件.
- [js-yaml](https://github.com/nodeca/js-yaml) - 快速的YAML解析器.
- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML到JavaScript对象的转换器.
- [Jison](https://github.com/zaach/jison) - 友好的 JavaScript parser生成器. 与 Bison, Yacc 家族一样的思路.
- [google-libphonenumber](https://github.com/seegno/google-libphonenumber) - 解析、格式化、存储和验证电话号码.
- [ref](https://github.com/TooTallNate/ref) - 读/写缓冲区中的结构化二进制数据.
- [xlsx-populate](https://github.com/dtjohnson/xlsx-populate) - 读/写 Excel XLSX.
- [Chevrotain](https://github.com/SAP/chevrotain) - 非常快速且功能丰富的JavaScript解析器构建工具包.
- [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser) - 验证&解析 XML.

### 人性化

- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - 字节转换成人可读的字符工具: `1337` → `1.34 kB`.
- [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: `1337000000` → `15d 11h 23m 20s`.
- [ms](https://github.com/rauchg/ms.js) - 微毫秒转换实用程序.
- [pretty-error](https://github.com/AriaMinaei/pretty-error) - 更少无关信息的错误提示器.
- [read-art](https://github.com/Tjatse/node-readability) - 从任何页面提取可读内容.

### 压缩

- [yazl](https://github.com/thejoshwolfe/yazl) - Zip打包.
- [yauzl](https://github.com/thejoshwolfe/yauzl) - Unzip解压.
- [Archiver](https://github.com/archiverjs/node-archiver) - 用于生成存档文件的流接口，支持ZIP和TAR.
- [pako](https://github.com/nodeca/pako) - javascript的高速zlib端口，可在浏览器和node.js中使用.
- [tar-stream](https://github.com/mafintosh/tar-stream) - 流式tar解析器和生成器。另见[tar-fs](https://github.com/mafintosh/tar-fs).
- [decompress](https://github.com/kevva/decompress) - 解压模块，支持tar、tar.gz和zip文件开箱即用.

### 网络

- [get-port](https://github.com/sindresorhus/get-port) - 获取一个可以的端口.
- [ipify](https://github.com/sindresorhus/ipify) - 获取你的公网IP地址.
- [getmac](https://github.com/bevry/getmac) - 获取电脑的MAC地址.
- [DHCP](https://github.com/infusion/node-dhcp) - DHCP 客户端 &服务器.
- [netcat](https://github.com/roccomuso/netcat) - 纯JS中的Netcat端口.

### 数据库

- 驱动
	- [PostgreSQL](https://github.com/brianc/node-postgres) - PostgreSQL客户端。 纯JavaScript和本机libpq绑定.
	- [Redis](https://github.com/luin/ioredis) - Redis 客户端.
	- [LevelUP](https://github.com/Level/levelup) - LevelDB.
	- [MySQL](https://github.com/mysqljs/mysql) - MySQL 客户端.
	- [couchdb-nano](https://github.com/apache/couchdb-nano) - CouchDB 客户端.
	- [Aerospike](https://github.com/aerospike/aerospike-client-nodejs) - Aerospike 客户端.
	- [Couchbase](https://github.com/couchbase/couchnode) - Couchbase 客户端.
	- [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB 驱动.
- ODM / ORM
	- [Sequelize](https://github.com/sequelize/sequelize) - 多方ORM。 支持PostgreSQL，SQLite，MySQL.
	- [Bookshelf](https://github.com/bookshelf/bookshelf) - Backbone.js风格的PostgreSQL，MySQL和SQLite3的ORM.
	- [Massive](https://github.com/robconery/massive-js) - PostgreSQL数据访问工具.
	- [Mongoose](https://github.com/Automattic/mongoose) - 优雅的MongoDB对象建模.
	- [Waterline](https://github.com/balderdashy/waterline) - 与数据存储区无关的工具，可大大简化与一个或多个数据库的交互.
	- [OpenRecord](https://github.com/PhilWaldmann/openrecord) - PostgreSQL，MySQL，SQLite3和RESTful数据存储的ORM。 类似于ActiveRecord.
	- [pg-promise](https://github.com/vitaly-t/pg-promise) - 用于使用Promise的本机SQL的PostgreSQL框架.
	- [slonik](https://github.com/gajus/slonik) - 具有严格类型，详细日志记录和断言的PostgreSQL客户端.
	- [Objection.js](https://github.com/Vincit/objection.js) - 基于SQL查询生成器Knex的轻量级ORM.
	- [TypeORM](https://github.com/typeorm/typeorm) - PostgreSQL，MariaDB，MySQL，SQLite等的ORM.
	- [MikroORM](https://github.com/mikro-orm/mikro-orm) - 基于数据映射器，工作单元和身份映射模式的TypeScript ORM。 支持MongoDB，PostgreSQL，MySQL和SQLite.
- Query builder
	- [Knex](https://github.com/tgriesser/knex) - PostgreSQL，MySQL和SQLite3的查询构建器，旨在灵活，可移植且易于使用.
- 其他
	- [NeDB](https://github.com/louischatriot/nedb) - 用JavaScript编写的嵌入式持久数据库.
	- [Lowdb](https://github.com/typicode/lowdb) - 由Lodash支持的小型JavaScript数据库.
	- [Keyv](https://github.com/lukechilds/keyv) - 简单的键值存储，支持多个后端.
	- [Finale](https://github.com/tommybananas/finale) - 用于Sequelize模型的RESTful端点生成器.
	- [database-js](https://github.com/mlaanderson/database-js) - 具有类似JDBC的连接的多个数据库的包装器.
	- [Mongo Seeding](https://github.com/pkosiec/mongo-seeding) - 使用JavaScript和JSON文件填充MongoDB数据库.

### 测试相关

- [AVA](https://github.com/avajs/ava) - 面向未来的测试运行程序.
- [Mocha](https://github.com/mochajs/mocha) - 使异步测试变得简单有趣的功能丰富的测试框架.
- [nyc](https://github.com/bcoe/nyc) - 基于istanbul 构建的代码覆盖工具，可用于子流程.
- [tap](https://github.com/isaacs/node-tap) - TAP测试框架.
- [tape](https://github.com/substack/tape) - TAP生产测试.
- [power-assert](https://github.com/power-assert-js/power-assert) - 通过标准的assert接口提供描述性断言消息.
- [Mochify](https://github.com/mantoni/mochify.js) - TDD与Browserify，Mocha，PhantomJS和WebDriver.
- [trevor](https://github.com/vdemedes/trevor) - 针对多个版本的Node.js运行测试，而无需手动切换版本或推送至Travis CI.
- [loadtest](https://github.com/alexfernandez/loadtest) - 使用自动化API为Web应用程序运行负载测试.
- [Sinon.JS](https://github.com/sinonjs/sinon) - 单元测试数据模拟，函数模拟工具.
- [navit](https://github.com/nodeca/navit) - PhantomJS/SlimerJS包装器简化浏览器测试脚本.
- [Nock](https://github.com/pgte/nock) - HTTP模拟.
- [intern](https://github.com/theintern/intern) - 代码测试栈.
- [toxy](https://github.com/h2non/toxy) - 可入侵的HTTP代理可模拟故障场景和网络状况.
- [hook-std](https://github.com/sindresorhus/hook-std) -钩子&修改stdout / stderr.
- [testen](https://github.com/egoist/testen) - 使用NVM在本地运行针对多个版本的Node.js的测试.
- [Nightwatch](https://github.com/nightwatchjs/nightwatch) - 基于Selenium WebDriver的自动化UI测试框架.
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - 基于WebDriver协议的自动化测试.
- [Jest](https://github.com/facebook/jest) - 简单的JavaScript测试.
- [TestCafe](https://github.com/DevExpress/testcafe) - 自动化的浏览器测试.
- [abstruse](https://github.com/bleenco/abstruse) - 持续集成服务器.
- [CodeceptJS](https://github.com/Codeception/CodeceptJS) - 端到端测试.
- [Puppeteer](https://github.com/GoogleChrome/puppeteer) - 无界面Chrome.
- [nve](https://github.com/ehmicky/nve) - 在本地多个版本的Node.js上运行任何命令.

### 安全相关

- [upash](https://github.com/simonepri/upash) - 所有密码散列算法的统一API.
- [themis](https://github.com/cossacklabs/themis) - 使典型加密方案易于使用的多语言框架：静态数据、经过身份验证的数据交换、传输保护、身份验证等.
- [GuardRails](https://github.com/apps/guardrails) - 在请求中提供安全反馈的GitHub应用程序.
- [rate-limiter-flexible](https://github.com/animir/node-rate-limiter-flexible) - 暴力DDoS攻击保护.
- [crypto-hash](https://github.com/sindresorhus/crypto-hash) - 异步非阻塞哈希.
- [jose-simple](https://github.com/davesag/jose-simple) - 使用JOSE（JSON对象签名和加密）标准对数据进行加密和解密.
- [helmet](https://github.com/helmetjs/helmet) helmet 常见攻击防御库，比如xss等等

### 基准化

- [Benchmark.js](https://github.com/bestiejs/benchmark.js) - 代码性能测试工具.
- [matcha](https://github.com/logicalparadox/matcha) - 更简单的测试方法.

### 文件压缩

- [babili](https://github.com/babel/babili) -基于Babel工具链的 ES2015+ 压缩库.
- [UglifyJS2](https://github.com/mishoo/UglifyJS2) - JavaScript 压缩工具.
- [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS 压缩工具.
- [minimize](https://github.com/Swaagie/minimize) - HTML压缩工具.
- [imagemin](https://github.com/imagemin/imagemin) - Image压缩工具.

### 认证方式

- [Passport](https://github.com/jaredhanson/passport) - 简单, 无感的身份验证.
- [Grant](https://github.com/simov/grant) - Express, Koa, and Hapi权限校验中间件.

### 授权库

- [CASL](https://github.com/stalniy/casl) - UI和API的同构授权.
- [node-casbin](https://github.com/casbin/node-casbin) - 支持访问控制模型（如ACL、RBAC和ABAC）的授权库.

### 邮箱

- [Nodemailer](https://github.com/andris9/Nodemailer) - 处理电子邮件的最快方式.
- [emailjs](https://github.com/eleith/emailjs) - 向任何SMTP服务器发送带有附件的文本/HTML电子邮件.
- [email-templates](https://github.com/niftylettuce/email-templates) - 创建、预览和发送自定义电子邮件模板.
- [MJML](https://github.com/mjmlio/mjml) - 旨在减少创建响应电子邮件的痛苦的标记语言.

### 任务队列

- [bull](https://github.com/OptimalBits/bull) - 持久作业和消息队列.
- [agenda](https://github.com/rschmukler/agenda) - MongoDB支持的作业调度.
- [idoit](https://github.com/nodeca/idoit) - 具有高级作业控制的Redis支持的作业队列引擎.
- [node-resque](https://github.com/taskrabbit/node-resque) - Redis支持的作业队列.
- [rsmq](https://github.com/smrchy/rsmq) - 基于Redis的消息队列.
- [bee-queue](https://github.com/bee-queue/bee-queue) - 高性能的 基于Redis的任务队列.
- [RedisSMQ](https://github.com/weyoss/redis-smq) - 具有实时监控功能的简单高性能Redis消息队列.
- [sqs-consumer](https://github.com/bbc/sqs-consumer) - 在没有样板文件的情况下构建基于Amazon简单队列服务（SQS）的应用程序.
- [better-queue](https://github.com/diamondio/better-queue) - 无法使用Redis时简单高效的作业队列.
- [amqp](https://github.com/squaremo/amqp.node)- amqplib rabbit等等消息队列连接库.
- [kafka-node]( https://github.com/SOHU-Co/kafka-node)- kafka-node kafka客户端.


### Node.js管理工具

- [n](https://github.com/tj/n) - Node.js 版本控制.
- [nave](https://github.com/isaacs/nave) - Node.js虚拟环境.
- [nodeenv](https://github.com/ekalinin/nodeenv) - 与Python的virtualenv兼容的Node.js虚拟环境.
- [nvm for Windows](https://github.com/coreybutler/nvm-windows) - Windows node版本控制工具.
- [nodenv](https://github.com/nodenv/nodenv) - 类似于Ruby的rbenv的版本管理器,支持自动换版.

### NLP自然语言处理

- [retext](https://github.com/wooorm/retext) - 一个可扩展的自然语言系统.
- [franc](https://github.com/wooorm/franc) - 检测文本语言.
- [leven](https://github.com/sindresorhus/leven) - 使用Levenshtein距离算法测量两个字符串之间的差异.
- [natural](https://github.com/NaturalNode/natural) - 自然语言设施.
- [nlp.js](https://github.com/axa-group/nlp.js) - 构建机器人，具有实体提取、情感分析、自动语言识别等功能.

### 进程管理

- [PM2](https://github.com/Unitech/pm2) - 高级进程管理工具.
- [nodemon](https://github.com/remy/nodemon) - 监视应用程序中的更改并自动重新启动服务器.
- [node-mac](https://github.com/coreybutler/node-mac) - 将脚本作为本机Mac守护进程运行并登录到控制台应用程序.
- [node-linux](https://github.com/coreybutler/node-linux) - 将脚本作为本机系统服务运行并登录到syslog.
- [node-windows](https://github.com/coreybutler/node-windows) - 将脚本作为本机Windows服务运行并登录到事件查看器.
- [supervisor](https://github.com/petruisfan/node-supervisor) - 当脚本崩溃时重新启动脚本，或者当`*.js'文件更改时重新启动脚本s.
- [Phusion Passenger](https://github.com/phusion/passenger) - 直接嵌入Nginx的易用的进程管理工具.

### 自动化

- [robotjs](https://github.com/octalmage/robotjs) - 桌面自动化：控制鼠标、键盘和阅读屏幕。.

### AST

- [Acorn](https://github.com/ternjs/acorn) - 轻量、快速的JavaScript解析器.
- [babel-parser](https://github.com/babel/babel/tree/master/packages/babel-parser) - 用于babel的JavaScript解析工具.
- [cherow](https://github.com/cherow/cherow) - 专注于性能&稳定性的Javascript解析器.

### 静态站点生成

- [Wintersmith](https://github.com/jnordberg/wintersmith) - 灵活、简约、多平台静态站点生成器.
- [Assemble](https://github.com/assemble/assemble/) - Node.js、Grunt.js和Yeoman的静态站点生成器.
- [DocPad](https://github.com/docpad/docpad) - 具有动态能力和巨大插件生态系统的静态站点生成器.
- [Phenomic](https://github.com/phenomic/phenomic) - 基于React和Webpack生态系统的现代静态网站生成器.
- [docsify](https://github.com/QingWei-Li/docsify) - Markdow文档站点生成器.
- [Charge](https://github.com/brandonweiss/charge) - 使用JSX和MDX的自以为是的零配置静态站点生成器.

### Content management systems

- [KeystoneJS](https://github.com/keystonejs/keystone) -基于Express和MongoDB的CMS和web应用平台.
- [ApostropheCMS](https://github.com/apostrophecms/apostrophe) - 基于Express和MongoDB的内容管理系统，强调直观的前端内容编辑和管理.
- [Strapi](https://github.com/strapi/strapi) - 内容管理框架（headless CMS）构建强大的api.
- [Tipe](https://github.com/tipeio/tipe) - 从模式文件中使用GraphQL和REST API的开发人员第一内容管理系统.

### 论坛

- [nodeBB](https://github.com/NodeBB/NodeBB) - Node社区论坛.

### 博客

- [Ghost](https://github.com/TryGhost/Ghost) - Simple, powerful publishing platform.
- [Hexo](https://github.com/hexojs/hexo) - Fast, simple and powerful blogging framework.


### 序列化

- [snappy](https://github.com/kesla/node-snappy) - Google的snapy压缩库的本机绑定.
- [protobuf](https://github.com/dcodeIO/protobuf.js) - 协议缓冲区的实现.
- [compactr](https://github.com/compactr/compactr.js) - Compactr协议的实现.

### 其他

- [execa](https://github.com/sindresorhus/execa) - 比 `child_process`更好的子进程方法.
- [cheerio](https://github.com/cheeriojs/cheerio) - 快速, 灵活, 学习了jquery设计模式的服务端dom操作工具（爬取网页时使用）.
- [Electron](https://github.com/atom/electron) - 构建跨平台应用的GUI技术 *(You might like [awesome-electron](https://github.com/sindresorhus/awesome-electron))*
- [open](https://github.com/sindresorhus/open) - 打开网站、文件、可执行文件等.
- [hasha](https://github.com/sindresorhus/hasha) - 使散列变得简单。获取缓冲区/字符串/流/文件的哈希.
- [import-fresh](https://github.com/sindresorhus/import-fresh) - Import a module while bypassing the cache.
- [ssh2](https://github.com/mscdex/ssh2) - SSH2客户端和服务器模块.
- [adit](https://github.com/markelog/adit) - SSH 相关工具.
- [Bottleneck](https://github.com/SGrondin/bottleneck) - 速率限制器，使节流变得容易.
- [webworker-threads](https://github.com/audreyt/node-webworker-threads) - 具有本机线程的轻量级Web Worker API实现.
- [node-pre-gyp](https://github.com/mapbox/node-pre-gyp) - 使从二进制发布安装Nodjes C++ 插件更简单的工具.
- [opencv](https://github.com/peterbraden/node-opencv) - OpenCV的javascript绑定。计算机图形处理工具.
- [dotenv](https://github.com/motdotla/dotenv) - 从.env文件加载环境变量.
- [remote-git-tags](https://github.com/sindresorhus/remote-git-tags) - 从远程git repo获取标记.
- [semver](https://github.com/npm/node-semver) - 语义版本分析器.
- [Faker.js](https://github.com/Marak/Faker.js) - 测试数据批量生成工具.
- [nodegit](https://github.com/nodegit/nodegit) - node本地绑定Git.
- [json-strictify](https://github.com/pigulla/json-strictify) - 安全地将值序列化为JSON而不丢失数据或进入无限循环.
- [simplecrawler](https://github.com/cgiffard/node-simplecrawler) - 事件驱动的web爬网程序.
- [jsdom](https://github.com/tmpvar/jsdom) - HTML和DOM的JavaScript实现.
- [hypernova](https://github.com/airbnb/hypernova) - 服务端渲染javascsript视图.
- [env-dot-prop](https://github.com/simonepri/env-dot-prop) - 使用点路径获取、设置或删除process.env的嵌套属性.
- [node-video-lib](https://github.com/gkozlenko/node-video-lib) - 纯JavaScript库，用于处理MP4和FLV视频文件并为HLS流创建MPEG-TS块.
- [basic-ftp](https://github.com/patrickjuchli/basic-ftp) - FTP/FTPS 客户端.

## 资源

### 教程

- [Node.js 最佳实践](https://github.com/i0natan/nodebestpractices) - 以多种语言提供的Node.js最佳实践中排名靠前的内容的摘要和管理.
- [Nodeschool](https://github.com/nodeschool) - 通过交互式课程学习Node.js.
- [Node的艺术](https://github.com/maxogden/art-of-node/#the-art-of-node) - Node.js 全景介绍.
- [流操作手册](https://github.com/substack/stream-handbook) - 如何使用流编写Node.js程序s.
- [模块开发最佳实践](https://github.com/mattdesl/module-best-practices) -  一些写新的npm模块时的最近实践.
- [Node之路](http://thenodeway.io) - 一个完整的Node.js最佳实践和指导原则存在于编写可维护的模块、可扩展的应用程序和代码，这些代码实际上是可读的。.
- [你不知道的Node.js]Node.js核心特性和异步JavaScript简介t.
- [极简Node.js指南](https://github.com/ehmicky/portable-node-guide) - 如何编写可移植/跨平台Node.js代码的实用指南.
- [无框架构建可用web app](https://frameworkless.js.org/course) - 一组视频教程/直播，可帮助您使用一些简单的库和核心的Node.js模块来构建和部署真正的实时Web应用程序.

### 资源仓库

- [npms](https://npms.io) - 出色的包裹搜索功能，可使用[myriad of metrics](https://npms.io/about).
- [npm addict](https://npmaddict.com) - 你日常加入的npm软件包.
- [npmcompare.com](https://npmcompare.com) - 比较并发现npm软件包.

### 文章

- [Node.js异常处理](https://www.joyent.com/node-js/production/design/errors)
- [十步自学 Node.js](https://ponyfoo.com/articles/teach-yourself-nodejs-in-10-steps)
- [Node.js掌控文件系统](https://medium.com/@yoshuawuyts/mastering-the-filesystem-in-node-js-4706b7cb0801)
- [Semver：入门](https://nodesource.com/blog/semver-a-primer/)
- [Semver: Tilde and Caret](https://nodesource.com/blog/semver-tilde-and-caret/)
- [为什么使用异步?](https://nodesource.com/blog/why-asynchronous/)
- [深入浅出Node.js事件循环](https://nodesource.com/blog/understanding-the-nodejs-event-loop/)
- [深入浅出对象流](https://nodesource.com/blog/understanding-object-streams/)
- [README的艺术](https://github.com/noffle/art-of-readme) - 学习编写高质量readme的艺术.
- [ 使用Express快速构建Graphql服务器](https://snipcart.com/blog/graphql-nodejs-express-tutorial)

### 新闻

- [Node Weekly](http://nodeweekly.com) - Node.js新闻和文章的每周电子邮件摘要.
- [Node Module Of The Week!](https://nmotw.in) - 每周精选node模块 .

### 视频

- [Node.js介绍-Ryan Dahl](https://www.youtube.com/watch?v=jo_B4LTHi3I)
- [手把手使用Node.js](https://learn.bevry.me/hands-on-with-node.js/preface)
- [Nodetuts](http://nodetuts.com) - 一系列讲座，包括TCP和HTTP API服务器、异步编程等.
- [V8 垃圾收集器](https://v8.dev/blog/trash-talk) - V8垃圾收集器座谈.
- [Nodejs 10件憾事 - Ryan Dahl](https://www.youtube.com/watch?v=M3BM9TB-8yA) - Node.js的创建者关于其某些局限性的深刻见解.

### 书籍

- [Node.js in Action](https://www.manning.com/books/node-js-in-action-second-edition)
- [Node.js in Practice](http://www.amazon.com/Node-js-Practice-Alex-R-Young/dp/1617290939)
- [Mastering Node](http://visionmedia.github.io/masteringnode/)
- [Node.js 8 the Right Way](https://pragprog.com/book/jwnode2/node-js-8-the-right-way)
- [Professional Node.js: Building JavaScript Based Scalable Software](http://www.amazon.com/Professional-Node-js-Building-Javascript-Scalable-ebook/dp/B009L7QETY/)
- [Practical Node.js: Building Real-World Scalable Web Apps](http://practicalnodebook.com)
- [Mixu's Node book](http://book.mixu.net/node/)
- [Pro Express.js](http://proexpressjs.com)
- [Secure Your Node.js Web Application](http://www.amazon.com/Secure-Your-Node-js-Web-Application/dp/1680500856)
- [Express in Action](https://www.manning.com/books/express-in-action)
- [Practical Modern JavaScript](https://www.amazon.com/Practical-Modern-JavaScript-Dive-Future/dp/149194353X)
- [Mastering Modular JavaScript](https://www.amazon.com/Mastering-Modular-JavaScript-Nicolas-Bevacqua/dp/1491955686/)
- [Get Programming with Node.js](https://www.manning.com/books/get-programming-with-node-js)

### 博客

- [Node.js blog](https://nodejs.org/en/blog/)
- [webapplog.com](http://webapplog.com/tag/node-js/) - Blog posts on Node.js and JavaScript from the author of Practical Node.js and Pro Express.js Azat Mardan.

### 课程

- [学习用 Node.js构建web&App](https://learnnode.com/friend/AWESOME) -  Wes Bos视频教程.
- [基于Node.js的实时web应用](https://www.codeschool.com/courses/real-time-web-with-node-js)
- [学习&理解 Node.js](https://www.udemy.com/understand-nodejs)

### 备忘单

- [Express.js](https://github.com/azat-co/cheatsheets/blob/master/express4)
- [Stream FAQs](https://github.com/stephenplusplus/stream-faqs) - 回答有关流的常见问题，包括分页，事件等.
- [Strong Node.js](https://github.com/jesusprubio/strong-node) - Node.js Web服务的源代码安全性分析清单.

### 工具

- [OctoLinker](https://chrome.google.com/webstore/detail/octolinker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome扩展程序，可链接GitHub上package.json，.js，.jsx，.coffee和.md文件中的依赖项.
- [npm-hub](https://chrome.google.com/webstore/detail/npm-hub/kbbbjimdjbjclaebffknlabpogocablj) - Chrome扩展程序可在存储库自述文件的底部显示npm依赖项.
- [RunKit](http://blog.tonicdev.com/2015/09/30/embedded-tonic.html) - 在任何网站上嵌入Node.js环境.
- [RequireBin](http://requirebin.com) - 由npm和browserify提供支持的可共享JavaScript程序.
- [github-npm-stats](https://chrome.google.com/webstore/detail/github-npm-stats/oomfflokggoffaiagenekchfnpighcef) - Chrome扩展程序在GitHub上显示npm下载统计信息.
- [npm semver calculator](https://semver.npmjs.com) - 直观地探索一个semver范围匹配的软件包版本.

### 社区

- [Gitter](https://gitter.im/nodejs/node)
- [`#node.js` on Freenode](http://webchat.freenode.net/?channels=node.js)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/node.js)
- [Reddit](https://www.reddit.com/r/node)
- [Twitter](https://twitter.com/nodejs)
- [Hashnode](https://hashnode.com/n/nodejs)
- [Discord](https://discordapp.com/invite/96WGtJt)

### 其他

- [nodebots](http://nodebots.io) - 由JavaScript驱动的机器人.
- [modern-node](https://github.com/sheerun/modern-node) - 使用Jest，Prettier，ESLint和Standard创建节点模块的工具包.
- [Microsoft Node.js Guidelines](https://github.com/Microsoft/nodejs-guidelines) - 在Microsoft平台上使用Node.js的提示，技巧和资源.

## 相关链接

- [awesome-npm](https://github.com/sindresorhus/awesome-npm) - 使用npm的资源和技巧.
- [awesome-cross-platform-nodejs](https://github.com/bcoe/awesome-cross-platform-nodejs) - 编写和测试跨平台代码的资源.
