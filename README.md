# coursework_1

ICP开发入门课程第一课课程作业  

1.使用SDK搭建一个简易网站 dfx new --no-frontend

    1）执行 dfx new --no-frontend  创建项目,无前端脚手架

    2）在frontend/assets中新建一个简易的html页面（非前端开发，简单到不能简单的单页>_<）

    3) dfx deploy 本地部署

2.领取cycles钱包  

    1) 获得qp2sd-aiaaa-aaaal-qa7wq-cai兑换地址与67854-E8BA5-D94A7兑换码

    2）dfx canister --network=ic call qp2sd-aiaaa-aaaal-qa7wq-cai redeem '("67854-E8BA5-D94A7")'

    3) (principal "wfum2-kaaaa-aaaam-aanya-cai")

    4）dfx identity --network=ic set-wallet wfum2-kaaaa-aaaam-aanya-cai

    5) dfx wallet --network=ic balance

3.将网站部署到ic0.app  

    1) dfx deploy --network=ic --with-cycles 1000000000000

    2) frontend: https://oqnxe-iaaaa-aaaam-aaqfq-cai.ic0.app/  

    backend: https://a4gq6-oaaaa-aaaab-qaa4q-cai.raw.ic0.app/?id=oxmrq-fyaaa-aaaam-aaqfa-cai

4.思考题:假如开发团队不再维护代码了 ，用户该怎么办?  

    1) 在问卷中填写。
