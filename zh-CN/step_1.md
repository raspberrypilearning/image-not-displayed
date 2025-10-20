仔细检查 `src` 属性中的图片名称是否与文件名匹配。 确保使用相同的大写字母。 例如，“myimage.png”与“myimage.PNG”**不**相同。

这个 HTML 不显示保存为“happy.PNG”的图片：

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<img src="happy.png" alt="An outline of an anime-style girl with a happy facial expression."/>

--- /code ---
