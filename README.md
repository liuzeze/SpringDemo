# SpringDemo
接口demo,方便平时调试数据

IDE  引入插件  SpringAssistant

pom.xml 配置maven 引用

application.properties   配置端口号 

```
//拼接路劲   请求方式
    @RequestMapping(value = "demo",method = RequestMethod.GET.GET)
    @GetMapping
    @PostMapping
    //请求参数
    public static String demo(@RequestParam("param") String param,
                              HttpServletRequest request, HttpServletResponse response)
            throws Exception {
            
            //接口l返回值
        return "success";
    }
    
    ```
