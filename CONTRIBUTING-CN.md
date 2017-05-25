# 贡献你的力量

感谢你对React-Select的兴趣，我们欢迎任何形式的贡献，如issue报告、PR和文档。

* 我们使用node.js v4版本来开发和测试。因为和JSDOM以及更老的node.js版本不兼容，你需要使用node 4来运行测试用例。

* 如果你要升级你的node.js 0.x，为了保证在新node.js版本下正确的依赖，有时候你需要删除工程下的node_modules目录，然后重新运行npm install（至少你需要删除jsdom模块并重新安装）。

如果你想新建一个PR：

* 如果你计划在一个PR里增加或修改一个主要的特性，尤其是准备花费大量时间之前，请先新开一个issue来保证和路线图的一致。
* 开发过程中，运行`npm start`来构建（+监视）项目源码，然后它会启动一个[开发服务器](http://localhost:8000)。
* 在你修改后请确保所有的例子都保持正确。如你添加了一个主要用例，请在examples下新增一个展示用的例子。
* 请**不要**提交构建后的文件，在你的PR中，确保**只包含**你对`／src`、`/less/` 或 `/examples/src`的修改部分。
* 请遵循项目的代码风格。修改代码后运行`npm run lint`来进行检查，确保没有产生新的错误或警告。
* 和项目的维护者对话，确保你付出的努力和项目的路线图一致，特别是你准备投入大量时间的时候。
* 在开始工作并提交PR之前，提交新的issue可以让核心人员理解你的意图和方向，并保持良好的沟通。
* 如果你提了新的issue并希望提供补丁，请通知我们，我们会帮你更好的开始工作。
* 通过运行`npm test`来确保你没有搞破坏。
* 建议在你的变更里面包含测试用例来说明一个bug或测试新功能。如果你不知怎么测试你的变更代码，随时@bruderstein
* 运行 `npm run cover`来检查测试是否有覆盖你修改的代码(报告在生成的`coverage`目录下) 。
* 请[遵循我们既定的编码惯例](https://github.com/keystonejs/keystone/wiki/Coding-Standards)
(关于格式化，等等)
* 尽管我们的lint配置尚未完善，但是你可以运行`npm run lint` 和 `npm run style` 来保证你变更的代码没有违例。
* 新的修改最好提供相关文档。我们提供了三种翻译版本，请阅读我么的[文档指南](https://github.com/keystonejs/keystone/wiki/Documentation-Translation-Guidelines).
* **在你提交PR之前最好还原你的build文件**以避免引起冲突。`gulp build-scripts` 命令用于PR合并后、版本发布前。
