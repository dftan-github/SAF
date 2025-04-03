# SAF(Ruby Windows General Purpose Application Framework)
- 由Ruby言语为主进行程序逻辑控制的Windows平台下通用桌面应用程序框架
- 支持在无源码、仅依靠文档和Demo的情况下可持续、递进式依葫芦画瓢地进行深度定制开发
- 目标是一个基本五脏俱全的可直接运行的通用程序，使用者可根据自己的需求在许可证权利授权下进行二次定制开发
- 以Bytecode的方式分发（黑盒子，最少关注原则，不含源码，相当于在Bin级对App进行修改、扩充、定制功能）
- 性能相关的任务交由C++完成
- 使用者不满意的地方都尽量允许有机会进行修改以达到个性化定制改造，一切以用户喜好为准！
- 在运行时进行UI设计，真正所见即所得！
- 基本上统一使用树形结构进行数据组织，方便理解程序逻辑（就像打开资源管理器查看电脑中的各种数据一样）
- 跟ROR一样使用契约式组织源码
  
# 初衷
- 解决软件行业以下痛点
  - 每年都有大量新人从学校进入软件行业
    - 新人基本上没有能力制作完整的应用程序，都需要从助理开始沉淀几年才有能力独立开发
  - 个人工作室
    - 有些能力，但是不想花时间在重建程序上，希望有个现成的可深度定制的通用App,只想写任务相关的代码，尽早交付应用
  - 中小企业
    - 自己研发团队开发App
      - 开发人员流动以及编码没有规范到位，使得经过几代的程序员后，遗留代码因为后来者需要通读框架才好继续，导致难以维护，丢又舍不得，继续维护成本又高，造成这些遗留的代码很可能会变成负资产
    - 委外开发，开发完成后，功能基本定型
      - 后续需要加功能时
        - 自己的Idea，不想经由开发商散布出去
        - 价格谈不拢，原开发商不愿意接单
        - 原开发商有心接单，但是原开发者离职，新人无法接手
      - 使用中发现Bug
        - 只能等待源开发商修复，自己就算有能力也没有途径修复
    - 购买现成的商用软件
      - 使用中发现Bug
        - 只能等待源开发商修复，自己就算有能力也没有途径修复
      - 想加功能
        - 只能依赖原开发商
  - 最终用户
    - 花钱买回来的软件基本上就是定死了功能，自己想要改造都没有途径
    - 运行中发现Bug，只能等开发商修复，自己（或者找第三方）修复都没有机会

# 为什么选择Ruby
- 只有使用过几个以上的编程语言（包含编译型和解释型）的才懂得Ruby的强大！正因为Ruby的强大才让解决以上所讲的行业痛点变得轻松
- 不要担心Ruby的魔幻，困难部分已由框架完成，使用者只管用常规方法做事就好
- 也不要担心不少人道听途说的性能问题，Ruby发展到现在，对于很多的应用场景，性能已经不是问题
- 解释型语言没有编译型语言（比如C++)的Coffee time的困扰，基本上是修改->随时运行程序（立等可取）

# 使用方法
- 下载后
  - 安装ruby
  - 在根目录下执行bundle install
  - 找到对应Vendors/xxx(开发商)/xxx(项目名)/run.rb
    - 执行(例如) ruby D:\DFTanRepository\Master\Projects\Vendors\DFTan\Meansure\run.rb

# 计划（展示相关功能及定制、增删、Bug修复方法）
- 制作一个基本功能的影像式测量软件（软仿真）
- 制作一个自动化设备上位机控制软件（软仿真）
- 制作贪食蛇、象棋、纸版游戏
- 制作各种小例子，帮助用户了解定制流程（欢迎提出问题、要求。然后我们来制作Demo）
- 在windows下成熟后，考虑更多的平台

# 期望
- 达到桌面版的ROR,让更多的Ruby爱好者有可用的好工具进行多种应用场景的桌面应用开发
- 欢迎留言探讨、挑刺、指正，共同进步
- 期待你的关注与参与
  
## 许可证
- 个人/非商业使用：免费 (MIT许可证)
- 商业使用：需购买商业许可证 (联系dftan@sina.com)
- 公司内部使用也属于商业使用

