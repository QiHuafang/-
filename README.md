# 文件说明
train.csv - 训练集
test.csv - 测试集（并没有房产销售价格（SalePrice））

# 使用的机器学习的算法：
集成森林、SVM、贝叶斯回归

# 模型评估
分类问题和回归问题模型评估方法并不相同
1、回归问题的指标：
Mean Absolute Error(MAE)	平均绝对误差、Mean Square Error(MSE)	平均方差、R-Squared	R平方值	
2、分类模型的评估：
准确率、精确率、召回率、f1_score，混淆矩阵，ks，ks曲线，ROC曲线，psi等
（有一段注释掉的代码便是犯了此错。。。）

# 模型改进（不足）
1、主成分分析处：PCA等，用算法进行。。。
2、训练数据采用的算法还可再试一下其他的（KNN、K—Means.....）

# 变量含义
SalePrice - 以美元为单位的房产销售价格。这是您要预测的目标变量。
MSSubClass : 建筑类
MSZoning : 一般分区分类
LotFrontage : 与房产相连的街道的线性英尺
LotArea：以平方英尺为单位的地块面积
街道: 道路类型
胡同：胡同类型
LotShape : 财产的一般形状
LandContour : 物业的平整度
实用程序：可用的实用程序类型
LotConfig : 批次配置
LandSlope : 财产的坡度
邻里: 艾姆斯市范围内的物理位置
条件 1：靠近主要道路或铁路
条件 2：靠近主要道路或铁路（如果有第二条）
BldgType : 住宅类型
HouseStyle : 住宅风格
OverallQual：总体材料和加工质量
TotalCond : 总体状况评级
建造年份：原始建造日期
YearRemodAdd :改造日期
RoofStyle : 屋顶类型
RoofMatl : 屋顶材料
Exterior1st : 房屋外墙
Exterior2nd : 房屋的外部覆盖物（如果不止一种材料）
MasVnrType : 砌体单板类型
MasVnrArea : 砌体单板面积（平方英尺）
ExterQual : 外部材料质量
ExterCond : 外部材料的现状
基础: 基础类型
BsmtQual : 地下室的高度
BsmtCond : 地下室的一般情况
BsmtExposure : 罢工或花园级地下室墙壁
BsmtFinType1 : 地下室完工区域的质量
BsmtFinSF1：类型 1 成品平方英尺
BsmtFinType2：第二个完成区域的质量（如果存在）
BsmtFinSF2：2型成品平方英尺
BsmtUnfSF : 未完成的地下室面积平方英尺
TotalBsmtSF : 地下室总平方英尺
加热：加热类型
HeatingQC : 加热质量和条件
CentralAir : 中央空调
电气: 电气系统
1stFlrSF : 一楼平方英尺
2ndFlrSF : 二楼平方英尺
LowQualFinSF：低质量成品平方英尺（所有楼层）
GrLivArea : 地上（地面）生活区平方英尺
BsmtFullBath : 地下室全浴室
BsmtHalfBath : 地下室半浴室
FullBath :楼上的完整浴室
HalfBath : 半浴以上等级
卧室: 地下层以上的卧室数量
厨房:厨房数量
KitchenQual : 厨房质量
TotRmsAbvGrd : 等级以上的房间总数（不包括浴室）
功能: 家庭功能评级
壁炉:壁炉数量
FireplaceQu : 壁炉质量
车库类型：车库位置
GarageYrBlt : 车库建成年份
GarageFinish : 车库的内部装饰
GarageCars：车库的汽车容量大小
GarageArea : 车库面积（平方英尺）
GarageQual : 车库质量
GarageCond : 车库条件
PavedDrive :铺好的车道
WoodDeckSF：以平方英尺为单位的木甲板面积
OpenPorchSF：以平方英尺为单位的开放门廊面积
EnclosedPorch : 封闭的门廊面积，以平方英尺为单位
3SsnPorch：以平方英尺为单位的三季门廊面积
ScreenPorch : 屏幕门廊面积（平方英尺）
PoolArea : 以平方英尺为单位的泳池面积
PoolQC : 游泳池质量
围栏：围栏质量
MiscFeature：其他类别未涵盖的杂项功能
MiscVal：杂项功能的 $Value
MoSold : 销售月
YrSold : 销售年份
SaleType : 销售类型
SaleCondition : 销售条件
