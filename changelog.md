1.3.6
1. 新增sprouter模块, 扩展路由能力
2. 新增sprpc模块, 增加rpc能力
3. 修复已知问题

1.2.1
1. service方法调用过程增加同步拦截
2. 新增getFixedService方法，通过class获取该class的实例，而不会是class的子类实例
3. @Service支持inherited属性, inherited属性为true时,
   他的所有子类都会被当做一个Service
4. 修复@Service注解处理Field字段生成注入对象时机不准确问题
5. 修复@Service会对Field进行重复多次注入问题
6. 其他一些优化