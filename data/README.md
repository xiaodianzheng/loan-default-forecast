# [赛题与数据](https://tianchi.aliyun.com/competition/entrance/531830/information)

## 数据

| **Field**          | **Description**                                              |
| ------------------ | ------------------------------------------------------------ |
| id                 | 为贷款清单分配的唯一信用证标识                               |
| loanAmnt           | 贷款金额                                                     |
| term               | 贷款期限（year）                                             |
| interestRate       | 贷款利率                                                     |
| installment        | 分期付款金额                                                 |
| grade              | 贷款等级                                                     |
| subGrade           | 贷款等级之子级                                               |
| employmentTitle    | 就业职称                                                     |
| employmentLength   | 就业年限（年）                                               |
| homeOwnership      | 借款人在登记时提供的房屋所有权状况                           |
| annuallncome       | 年收入                                                       |
| verificationStatus | 验证状态                                                     |
| issueDate          | 贷款发放的月份                                               |
| purpose            | 借款人在贷款申请时的贷款用途类别                             |
| postCode           | 借款人在贷款申请中提供的邮政编码的前3位数字                  |
| regionCode         | 地区编码                                                     |
| dti                | 债务收入比                                                   |
| delinquency_2years | 借款人过去2年信用档案中逾期30天以上的违约事件数              |
| ficoRangeLow       | 借款人在贷款发放时的fico所属的下限范围                       |
| ficoRangeHigh      | 借款人在贷款发放时的fico所属的上限范围                       |
| openAcc            | 借款人信用档案中未结信用额度的数量                           |
| pubRec             | 贬损公共记录的数量                                           |
| pubRecBankruptcies | 公开记录清除的数量                                           |
| revolBal           | 信贷周转余额合计                                             |
| revolUtil          | 循环额度利用率，或借款人使用的相对于所有可用循环信贷的信贷金额 |
| totalAcc           | 借款人信用档案中当前的信用额度总数                           |
| initialListStatus  | 贷款的初始列表状态                                           |
| applicationType    | 表明贷款是个人申请还是与两个共同借款人的联合申请             |
| earliesCreditLine  | 借款人最早报告的信用额度开立的月份                           |
| title              | 借款人提供的贷款名称                                         |
| policyCode         | 公开可用的策略_代码=1新产品不公开可用的策略_代码=2           |
| n系列匿名特征      | 匿名特征n0-n14，为一些贷款人行为计数特征的处理               |

## 评测标准

提交结果为每个测试样本是1的概率，也就是y为1的概率。评价方法为AUC评估模型效果（越大越好）。

## 结果提交

提交前请确保预测结果的格式与sample_submit.csv中的格式一致，以及提交文件后缀名为csv。