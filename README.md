# Credit-Risk-Management
Study notes on credit risk management

# 风险测算
年化资损率测算方式：
1. VINTAGE 测算
   方式1：
   年化资损率 = Vintage资损率 * 12/ 生息月数
   生息月数 = sum(本金+1期剩余本金+2期剩余本金+。。。）/本金
   方式2：
   年化资损率 = sumproduct((VINTAGE 资损率 * 周转次数）,资产结构占比）
   举例：
   1期 VINTAGE 资损率 3%， 3 期VINTAGE 资损率6%， 1期放款额占比50%，3期占比50%，则平均周转次数 = 0.83
   年化资损率 = 
3. 
