#Meeting 1
##概述
初步用于简单的交互，扩展功能会作为补充加入到设计中来    

###基础功能
注册， 登录， 看榜， 发单， 接单    
发奖励

##流程
1. 用户注册后，就可以得到“看榜单”的权限，只有实名之后才可以发单或者接单
    - 注册后我们会提供相应的奖励（实际券/系统币）
2. 发单或者接单后，都可以得到相应的系统币
    - 发单且完成后，需要扣除相应的系统币
    - 接单，接到一定的次数，也可能得到随机的实际券
3. 【活跃社区】实际券发送后，需要领取
    - 领取后，会有时间限制
    - 尽量发在一定地理范围内的券
    - 可以捆绑发送

##TODO 
1. 如何算是一次完整的单流程？ 谁来判断单子是否完成？ 发布者？还是接收者？是否需要report系统?
2. 是否提供fast create功能？用户可以快速创建旧单。
3. 个人信息中“感兴趣”的实现。是侧重可以完成的任务类型？还是侧重想得到的实际券类型？
4. 技能认证的实现。
5. 作弊操作怎么办？发收者刷币（用hash来确定发收者）
6. 如何算是实名？ （实名+人脸）
7. 发收者之间是否需要实时交流？ 或提供跟踪信息？
8. 是否需要做分享功能？
   