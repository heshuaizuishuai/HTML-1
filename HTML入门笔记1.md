1. HTML 是谁发明的？ 
* Tim Berners-Lee 李爵士


2. HTML 起手应该写什么？
~~~
<!DOCTYPE html>  //文档类型
<html lang="Zh-CN"> //浏览器识别文档的语言
    <head> //包含的内容一般不在页面中显示
        <meta charset="UTF-8"> //文件的字符编码
        <meta http-equiv="X-UA-Compatible" content="IE-edge"> //兼容手机，告诉IE使用最新内核
        <meta name="viewport" content="width=device-width, initial-scale=1.0"> //禁用缩放
        <title>Document</title> //html标题
    </head>
~~~

3. 常用的表章节的标签有哪些，分别是什么意思（h1~h6、section、article、main、aside 等等）？
* h1~h6 标题  标题有六级，层级依次递减，字号也越来越小，
* section 章节 
* article 文章 
* main 主要内容 
* aside 旁支内容 
* p 段落 
* header 头部 如头部的广告
* footer 脚部 如页面中尾部的版权归属
* div 划分   最常用，是division缩写


4. 全局属性有哪些？
* id 唯一的属性
* style 样式
* class标签   给某个代码的对象命名
* contenteditable使元素可以被编辑   
* hidden使元素看不见   style属性  
* title展示完整的内容 
* tabindex 用TAB时候，后面可以接不连续的数字，数字最大的最后选中& 数字为-1为直接隐去找不到此选项&数字为0的时候表示为最后被TAB找到

5. 常用的内容标签有哪些，分别是什么意思（a、strong、em、code、pre 等等）？
 * a anchor 的缩写，一般他都是用来放超链接的 
 * strong 表示用它包裹的内容是 加粗的，内容上的强调
 * em 表示强调 但他和strong的区别就是他是语气上的强调
 * code 等宽字符的代码
 * pre使多数空格和回车生效
 * hr水平分割 
 * br打断这一行使后面内容换行  
 * quote行内引用  
 * block quote块应用
 * ol>li 表示有序标签也就是1.2.3.等
 * ul>li 表示无序列表