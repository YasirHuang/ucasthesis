1. 变量命名统一问题（图片用I，视觉目标改用V{v_1,v_2,...}，embedding用e）
2. 变量格式问题，例如矩阵、集合(加粗？)、向量。。。
3. mywork_2可以增加en-cs的翻译，但目前表现不好
4. “本章所提出的”把“所”去掉
5. mywork_2中需要提及显式融合方法和隐式融合方法的结合，但是目前没有在实验中有明显证明隐式融合方法有用
6. 第3章的词实体、实体词、短语实体、实体短语的用法混乱
7. 第4章和第5章的余弦相似度需要统一一下
8. 图4-7的清晰度不够，数字太小


模板替换说明：
1. Thesis.tex：将“\usepackage{Style/custom}”加在document前
2. Tex/Frontinfo.tex：将所有信息复制过去
3. Tex/Frontmatter.tex：将“\input{Tex/0_Abstract}”复制过去
4. Tex/Prematter.tex：暂无改动
5. Tex/Mainmatter.tex：将各章节的\input复制过去
6. Tex/Backmatter.tex：已发表论文、专利复制过去，注意注销不需要写的部分
7. Biblio/ref.bib：丢弃新的文件
8. Biblio/其它：均复制过来
9. Style/*：全复制过来
10. Tex/figuretable.tex：新增文件