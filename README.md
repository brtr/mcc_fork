## 已知流程

1. 发布合约，需要带上参数_MCCTreasury和_multisigParties，签名地址暂时还不知道有什么用

2. 金库地址可以通过approve发币，spender填uniswap v2 router的地址 0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D # 暂时只测过eth rinkeby，ftm不可用

3. https://app.uniswap.org 连接钱包，点击流动池，查看v2流动池，导入流动池，粘贴合约地址选择相应的交易对，创建流动池，设置兑换比例和手续费级别

4. 正常兑换币种

5. https://app.uniswap.org 连接钱包，点击流动池，查看v2流动池，找到需要赎回的流动池点击管理，去除，选择比例，批准，去除


