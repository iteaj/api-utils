#### 此jar模块主要提供现阶段一些常用或者热门的第三方接口的开发 提供一套简单、易用、统一、方便理解、快速定位问题的api,方便我们快速进入业务的开发,而无需耗费大量的时间对接第三方接口
##### 快速导航
1. [此模块主要用于解决哪些问题](#what)
##### <a id="what">一、什么时候用,或者说能解决哪些问题</a>
>* 你对本模块里面提供的第三方接口没有任何的对接经验, 又想进入快速的开发
>* 如果你不想每次在对接一个第三方接口的时候,使用不同风格的api接口(不同的人代码风格不一样)导致增加学习成本,降低开发效率
>* 如果你想开源一个jar模块,但是又不想让使用者导入太多的jar包 比如：你开发的功能需要使用json功能,这时候你又不知道使用者项目里面导入的是哪个jar模块(Fastjson、jsckson、gson),这时候你可能需要一种json适配器
    
#### <a id="deal">二、编写api需要关注哪些点</a>
* 可读性强, 易于理解, 风格统一
  1. 使用一个接口描述清楚一个Api的主要功能,作为所有Api的父接口, 此父接口尽量简单, 注释清晰,
* 在不同版本之前能提供兼容性
* 易于使用,异常时

   
##### <a id="supportApi">提供那些接口Api</a>
>1. [微信公众号Api使用文档](/doc/微信公众号Api文档.md)
>2. [http适配器使用文档](/doc/http适配器文档.md)
>3. [json适配器使用文档](/doc/json适配器文档.md)
