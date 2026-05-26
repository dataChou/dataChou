# 周文敏 · 数据分析作品集

## 关于我
数据分析师，擅长金融风控、医学统计、因果推断。R/Python/Stata 三语精通。

## 精选项目

### 🐳 上市公司财务造假风险识别系统（机器学习 + SHAP可解释 + 双模型预警）
- **技术栈**：Python, XGBoost, SHAP, Streamlit, pandas, scikit-learn, imbalanced-learn, plotly
- **核心指标**：同步识别模型召回率 67.5%，精确率 23.1%，AUC 0.788；提前预警模型召回率 64.3%，AUC 0.753
- **亮点**：基于 CSMAR 2005‑2025 真实财务数据，11 个核心特征（行业相对化、滞后 ST 状态、关联交易占比等）；提供“同步识别”与“提前预警”双模式；SHAP 瀑布图个体解释，满足审计/券商可解释性要求；Streamlit 看板支持手动输入与股票代码查询，集成历史风险趋势、行业对比、异常指标提醒；召回率优先策略，符合“宁可多报、不可漏报”业务目标。
- **在线演示**：本地部署
- **仓库**：私有（可授权）
- **模型报告**：见技术报告（含数据清洗、特征工程、模型评估、SHAP 分析、局限性、滚动窗口验证）
  
### 🔥 信用评分卡开发（个人信贷违约预测等）
- **技术栈**：R, Streamlit, Excel
- **核心指标**：KS=0.55, AUC=0.86, 所有客户可打分
- **亮点**：缺失值自动分箱，交互式计算器，可解释评分卡
- **在线演示**：https://creditscorecard-c6ryowmkft7fmmcdayhsgm.streamlit.app
- **仓库**：[Credit_Scorecard](https://github.com/dataChou/Credit_Scorecard)
- **模型报告**：见仓库 `report/` 文件夹

### 🐾 连锁经营分析看板（RFM客户分层+盈利分析+流失预警）
- **技术栈**：Python, Streamlit, Pandas, Plotly, Excel
- **核心指标**：客户分层准确率100%，流失率40.2%→可挽回至25%，看病+绝育贡献74%营收
- **亮点**：RFM模型自动分层，全局筛选联动所有图表，缺失值自动分箱，云端部署一键刷新，支持Excel/网页双版本
- **在线演示**：https://businessdashboard-datachou.streamlit.app/
- **仓库**：[Pet_Hospital_Business_Dashboard](https://github.com/dataChou/BusinessDashboard)
- **模型报告**：见仓库（开发报告、经营建议报告）
- 
### ❤️ 患者MACE风险预测（机器学习模型+临床决策工具）

- **技术栈**：Python, R, Streamlit, scikit-learn, XGBoost, SHAP, pandas, joblib  
- **核心指标**：逻辑回归 AUC=0.931, KS=0.724, 准确率=0.846  
- **亮点**：集成逻辑回归、随机森林、XGBoost对比，最终模型AUC达0.931；SHAP全特征可视化，风险决策透明；中英文双语Web应用，输入即得风险概率+分级建议（低/中/高危）；R与Python混合编程，兼顾建模严谨性与前端部署效率  
- **在线演示**：https://mace-prediction-app-datchou.streamlit.app/  
- **仓库**：[mace-prediction-streamlit](https://github.com/dataChou/mace-prediction-streamlit)  
- **模型报告**：见仓库 `report/` 文件夹（技术报告、执行摘要、SHAP分析）
- 
### 📊 其他项目
- 临床护士AI态度潜在剖面分析（LPA）
- 

## 联系我
- 微信：Amydlmy
- 邮箱：scarlettzwm@gmail.com
