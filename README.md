# OpenCMKG

这是一个开源的中文医疗知识图谱，由以下数据聚合得到：

- QAKG：https://github.com/liuhuanyong/QASystemOnMedicalKG
- OwnThink：https://www.ownthink.com/docs/kg
- CHIP2021：http://cips-chip.org.cn/2021/eval1


## 文件说明

`triples.txt`: 3列（实体1，关系，实体2），逗号隔开

`entities_dict.txt`: 字典形式，key为类别，value为对应的实体列表


## 各类别实体的数量

| 本体/类别 | 本体/类别英文 | 数量       |
| --------- | ------------- | ---------- |
| 疾病      | disease       | 14726      |
| 药物      | drug          | 4289       |
| 食物      | food          | 4846       |
| 科室      | department    | 54         |
| 生产商    | producer      | 16772      |
| 症状      | symptom       | 19411     |
| 治疗方式  | treatment     | 598       |
| **总计**  |               | **60696**  |



## 三元组数量

| **三元组关系** | **三元组关系英文**           | **数量**   |
| -------------- | ---------------------------- | ---------- |
| 科室所属关系   | department_belong_department | 37         |
| 并发症         | disease_acompany_disease     | 25161      |
| 疾病所属科室   | disease_belong_department    | 8820       |
| 疾病一般用药   | disease_common_drug          | 14693      |
| 疾病可吃食物   | disease_eat_food             | 22262      |
| 疾病对应症状   | disease_has_symptom          | 59762      |
| 疾病需要检查   | disease_need_check           | 39416      |
| 疾病需要治疗   | disease_need_treatment       | 20607      |
| 疾病忌吃食物   | disease_noteat_food          | 27646      |
| 疾病推荐药物   | disease_recommand_drug       | 60621      |
| 疾病推荐食物   | disease_recommand_food       | 40221      |
| 药物生厂商     | drug_relate_producer         | 17532      |
| 同义实体       | SameAs                       | 17977      |
| **总计**       |                              | **354755** |







