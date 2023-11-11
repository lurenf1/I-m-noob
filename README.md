# Markdown上手操作

## ‘#’的操作

- ‘#’ 个数越多表示层级越低，如 ‘#’ 表示最大标题，‘##’表示第二级标题，以此类推。
- ‘#’ 与 ‘##’ 使用时会有下划线，但大于等于三个‘#’时不会出现，如要添加则需加上三个及以上的 ‘-’（减号）。

## ‘*’的操作
- 单个星号在文本两边表示  *斜体* ，两个星号表示 **加粗** 。

## 添加代码的操作
-  如在文章段中使用反引号（一般在esc下方）

	例：这是一个c和c++中整形变量的定义`int a;`
- 如需一部分完整代码则使用三个反引号开始，三个反引号结束
	例：
``` c++(这部分写所用语言名称能给代码上色)
#include<iostream>
using namespace std;
int main(){
	cout<<"Hello World!"<<endl;
	return 0;
}
```

## 链接的操作
- 使用‘[]（)’，方括号内放链接的别名，圆括号内放地址。当想在文本内显示图片时，在前加叹号‘ ！’。若是需要使用将图片本身做成一个链接，则再在外套一层‘[]（)’。
例： 
[**说谎-Geebar**](https://www.bilibili.com/video/BV1fm4y1Y7LM/?spm_id_from=333.337.search-card.all.click&vd_source=61a7d0ff7ef2290dcbadefa0bee3d62f)

	[![说谎](https://p2.music.126.net/dXfWd-eY7ZSIjyiY1qYDrQ==/109951168700387757.jpg?param=130y130)](https://www.bilibili.com/video/BV1fm4y1Y7LM/?spm_id_from=333.337.search-card.all.click&vd_source=61a7d0ff7ef2290dcbadefa0bee3d62f)

## 表格的操作
- 使用‘ | ’，多个‘ | ’用于隔开数据，并在其下方使用减号替代所填内容，目的是隔开表头和所填数据。
例：
	|p5面具推荐|枪p    |万能p |物理p|
	|------------- |------ |-------|-------|
	|愚者			 |撒旦耶尔|无|无|
	|世界|无|伊邪那岐大神/贼神|无|
	|塔|无|无|义经|
	
