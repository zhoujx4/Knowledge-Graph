# 基于规则的单轮医疗问答项目
- question_classifer.py：用于提取问题里面的**实体**，再根据实体和触发词提取**关系**
- question_parser.py：根据提取的实体和关系，生成相应的 Cpyher 语句
- answer_search.py：查询图数据库得到输出，组织美化回答