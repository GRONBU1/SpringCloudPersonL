#### 注意
`@FeignClient(value = "eurka-client")`
中的value 为 其他客服端的名称,  
`@RequestMapping(value = "/hi",method = RequestMethod.GET)`中的value为 其他客户端中的方法的url路由