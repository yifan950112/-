# 武汉市第四中学本次考试（语文）老师教学水平评估

* 首先用pandas读取原始excel数据，并替换列索引且删去重复行。
* 因为原始数据中成绩那列数据类型是object不能直接计算，我们将它改成能计算的float格式。
* 增加一列用来将全校学生的语文成绩排名，方便后续得到年级前十的学生信息。

* 将所有学生按班级分好类。将年级前十的学生信息读取出来，并记录每个班的年级前10学生个数，按照我们的模型给老师评估。


#### 分别计算各班平均分，按照模型给予老师评估打分。
#### 分别计算各班二本，一本，211上线率，按照模型给老师评估打分。
* 本次模拟考试二本线拟定89，一本线98，211线107。
#### 算出每个老师所有指标的总分（本次默认每个班级由不同老师教导）
#### 由于只有一次考试成绩，忽略模型中进步率模块的计算，并粗略调整了上线率模块的总分。