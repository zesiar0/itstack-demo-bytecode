# 字节码编程连载

- [`字节码编程，Javassist篇一《基于javassist的第一个案例helloworld》`](https://bugstack.cn/itstack-demo-agent/2020/04/19/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Javassist%E7%AF%87%E4%B8%80-%E5%9F%BA%E4%BA%8Ejavassist%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AA%E6%A1%88%E4%BE%8Bhelloworld.html)
- [`字节码编程，Javassist篇二《定义属性以及创建方法时多种入参和出参类型的使用》`](https://bugstack.cn/itstack-demo-agent/2020/04/20/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Javassist%E7%AF%87%E4%BA%8C-%E5%AE%9A%E4%B9%89%E5%B1%9E%E6%80%A7%E4%BB%A5%E5%8F%8A%E5%88%9B%E5%BB%BA%E6%96%B9%E6%B3%95%E6%97%B6%E5%A4%9A%E7%A7%8D%E5%85%A5%E5%8F%82%E5%92%8C%E5%87%BA%E5%8F%82%E7%B1%BB%E5%9E%8B%E7%9A%84%E4%BD%BF%E7%94%A8.html)
- [`字节码编程，Javassist篇三《使用Javassist在运行时重新加载类「替换原方法输出不一样的结果」》`](https://bugstack.cn/itstack-demo-agent/2020/04/21/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Javassist%E7%AF%87%E4%B8%89-%E4%BD%BF%E7%94%A8Javassist%E5%9C%A8%E8%BF%90%E8%A1%8C%E6%97%B6%E9%87%8D%E6%96%B0%E5%8A%A0%E8%BD%BD%E7%B1%BB-%E6%9B%BF%E6%8D%A2%E5%8E%9F%E6%96%B9%E6%B3%95%E8%BE%93%E5%87%BA%E4%B8%8D%E4%B8%80%E6%A0%B7%E7%9A%84%E7%BB%93%E6%9E%9C.html)
- [`字节码编程，Javassist篇四《通过字节码插桩监控方法采集运行时入参出参和异常信息》`](https://bugstack.cn/itstack-demo-agent/2020/04/27/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Javassist%E7%AF%87%E5%9B%9B-%E9%80%9A%E8%BF%87%E5%AD%97%E8%8A%82%E7%A0%81%E6%8F%92%E6%A1%A9%E7%9B%91%E6%8E%A7%E6%96%B9%E6%B3%95%E9%87%87%E9%9B%86%E8%BF%90%E8%A1%8C%E6%97%B6%E5%85%A5%E5%8F%82%E5%87%BA%E5%8F%82%E5%92%8C%E5%BC%82%E5%B8%B8%E4%BF%A1%E6%81%AF.html)
- [`字节码编程，Javassist篇五《使用Bytecode指令码生成含有自定义注解的类和方法》`](https://bugstack.cn/itstack-demo-agent/2020/04/29/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Javassist%E7%AF%87%E4%BA%94-%E4%BD%BF%E7%94%A8Bytecode%E6%8C%87%E4%BB%A4%E7%A0%81%E7%94%9F%E6%88%90%E5%90%AB%E6%9C%89%E8%87%AA%E5%AE%9A%E4%B9%89%E6%B3%A8%E8%A7%A3%E7%9A%84%E7%B1%BB%E5%92%8C%E6%96%B9%E6%B3%95.html)
- [`字节码编程，Byte-buddy篇一《基于Byte Buddy语法创建的第一个HelloWorld》`](https://bugstack.cn/itstack-demo-agent/2020/05/08/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Byte-buddy%E7%AF%87%E4%B8%80-%E5%9F%BA%E4%BA%8EByte-Buddy%E8%AF%AD%E6%B3%95%E5%88%9B%E5%BB%BA%E7%9A%84%E7%AC%AC%E4%B8%80%E4%B8%AAHelloWorld.html)
- [`字节码编程，Byte-buddy篇二《监控方法执行耗时动态获取出入参类型和值》`](https://bugstack.cn/itstack-demo-agent/2020/05/12/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Byte-buddy%E7%AF%87%E4%BA%8C-%E7%9B%91%E6%8E%A7%E6%96%B9%E6%B3%95%E6%89%A7%E8%A1%8C%E8%80%97%E6%97%B6%E5%8A%A8%E6%80%81%E8%8E%B7%E5%8F%96%E5%87%BA%E5%85%A5%E5%8F%82%E7%B1%BB%E5%9E%8B%E5%92%8C%E5%80%BC.html)
- [`字节码编程，Byte-buddy篇三《使用委托实现抽象类方法并注入自定义注解信息》`](https://bugstack.cn/itstack-demo-agent/2020/05/14/%E5%AD%97%E8%8A%82%E7%A0%81%E7%BC%96%E7%A8%8B-Byte-buddy%E7%AF%87%E4%B8%89-%E4%BD%BF%E7%94%A8%E5%A7%94%E6%89%98%E5%AE%9E%E7%8E%B0%E6%8A%BD%E8%B1%A1%E7%B1%BB%E6%96%B9%E6%B3%95%E5%B9%B6%E6%B3%A8%E5%85%A5%E8%87%AA%E5%AE%9A%E4%B9%89%E6%B3%A8%E8%A7%A3%E4%BF%A1%E6%81%AF.html)
