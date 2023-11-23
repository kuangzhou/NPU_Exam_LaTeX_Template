## 西北工业大学试卷 LaTeX 模板

- 改编自清华大学试卷Latex模板[GitHub](https://github.com/VicaYang/THU-Exam-LaTeX-Template)

- 试题与答案同时输入，输出试卷与答案可通过选择文档类型实现
  - 试卷：\documentclass[answer]{NPUExam}

  - 答案：\documentclass[]{NPUExam}

- 填空、选择、判断题通过\makepart填加，每种题型的小题通过problem环境填加

- 大题用\makepartt填加
