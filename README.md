# learn-javaWeb


用于路径匹配
ant风格：

?	匹配任何单字符
*	匹配0或者任意数量的字符
**	匹配0或者更多的目录

restful风格的参数

可以映射URL中的占位符到目标方法的参数
@PathVariable(value=[参数])
 @RequestMapping("/testPathVariable/{id}")
    public String testPathVariable(@PathVariable("id")Integer id){
        System.out.println(id);
        return SUCCESS;
    }
    
  HiddenHttpmethodFilte：可以是浏览器支持PUT DELETE请求
    
    
