## hosts  
为目标ip地址做域名伪装  
> srcHost tarDomain
## rewrite  
代理的相关配置：  
> 1. domain [伪装的域名]  
> 2. set_header: 添加的http头内容  
## chrome代理插件：SwitchyOmega
在 选项页中新建一个“PAC模式的情景模式”，   
然后填充“PAC”网址为控制台暴露的 "XXX/proxy.pac"，  
点击“立即更新情景模式”按钮；  
**后续对hosts和rewrite更新之后，都要更新情景模式配置**