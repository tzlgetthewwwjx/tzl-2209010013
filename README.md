# 谭卓林| Quant Researcher
# 学号：2209010013
## 基本信息
- **教育背景**：北京大学数学科学学院 金融数学硕士（GPA: 3.8/4.0）
- **联系方式**：📱 (+86) 138-XXXX-XXXX | 📧 quantzhang@pku.edu.cn
- **在线资料**：[GitHub](https://github.com/quantzhang) | [个人博客](https://quantzhang.tech)

---

## 核心优势
### 数学能力
- 全国大学生数学竞赛**一等奖**（前0.5%）
- 精通随机分析、最优化理论、偏微分方程

### 编程能力
- ACM-ICPC区域赛**金牌**
- LeetCode 300+（Python/C++双语言解法）

### 金融建模
- CFA二级候选人
- 自主开发多因子模型IC>0.15

---

## 工作经历
### 九章量化 | 量化研究实习生
`2023.07-2023.12`
- 开发基于强化学习的期货高频策略
  - 实盘夏普比率**4.2**
  - 较传统策略提升138%
- 构建卫星图像分析因子
  ```python
  # 使用ResNet提取仓储特征
  def extract_warehouse_features(satellite_imgs):
      model = torch.hub.load('pytorch/vision', 'resnet50')
      return model(satellite_imgs)  # IC=0.12
