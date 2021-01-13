# 第一天学习html的语法规范
- 所有标签都在尖括号中，且一般成对出现，前面的是开始标签，后面的是结束标签
    <html></html>
    也有特殊的单标签
    <br />
- 标签关系
    包含关系和并列关系
    包含关系(父子关系)
        <head>
            <title></title>
        </head>
    并列关系(兄弟关系)
        <head></head>
        <body></body>
- 基本结构标签
    <html>  根标签
        <head>  头标签
        <title>第一个标签</tittle>  标题(页面名称)
        </head>
        <body>  主体
            键盘敲烂，工资过万
        </body>
    </html>
# 使用网页开发工具
- 用 ! 加上tab快速生成主体
- 代码说明 
    <!DOCTYPE html>文档类型声明，说明使用版本，必须写在第一行，这不是HTML标签，是声明标签
    <html lang="en"> 显示语言为英文 zh-CN就是中文网页
    <meta charset="UTF-8"> charset是字符集 常用的有 GB2312、BIG5、GBK、UTF-8，其中UTF-8叫万国码
# 常用标签
- 标签的语义
    既这个标签用来干嘛的，根据标签的语义，在合适的地方给一个最为合适的语义，可以让结构更加清晰
- 标题标签
    <h1></h1>到<h6></h6>六级标签
    单词head的缩写，依据重要性递减
- 段落标签<p></p>
    <p class="blue"></p>  其中class定义其属性用双引号包住
    短语段之间
- article 独立内容 nav 导航相关 aside 边栏 outline 大纲/目录
    <header>
        页头部分
    </header>
    <section>
        介绍
    </section>
    <aside>
        广告
    </aside>
    <footer>
        版权信息
    </footer>
- <pre></pre> 用原本的格式显示出来
- <ul>
    没有顺序的列表
    <li>列表项目的内容</li>
  </ui>
- <ol>有顺序的列表</ol>
- <dl>有描述的标签
    <dt>定义的词汇</dt>
    <dd>解释</dd>
  </dl>
- <abbr 在这里加一个title=“对缩写的描述”>是一个缩写标签</abbr>
- <mark>高亮显示文字</mark>
- <del>被删除的内容</del>
- <ins>插入标签</ins>
- <s>删除线</s>
- <u>下划线</u>
- <strong>加粗显示文字，增加重量</strong>
- <b>只加粗</b>
- <small>减小字号，减轻重量</small> 
- <code>特别样式，显示代码</code>

- <img src="图片来源" width="宽度调整" alt="使用文字描述">
- <video  width="宽度调整" poster="视屏海报" autoplay自动播放或者用controls增加控制栏>
    <source src="视频来源">
    <track kind="captions/subtitles" srclang="en"显示的语言 label="给用户看的标签">webvtt是字幕标准格式
  </video>
- <table> 表格
    <thead> 表格头
    <tr> 一行内容
        <td></td> 表格数据
        <th>头部单元格 </th>
    </tr>
    </thead>
    <tbody> 表格内容
        
    </tbody>
    <tfoot>
        <tr>
            <td colspan="2"></td> colspan表示表格占用的列
        </tr>
    </tfoot>
  </table>
- <form>
    <label for="id">标签</label>  用来修饰项目
    <input type="text"文本框 placeholder="占位符（提示用户应该输入啥）" value="文本框的值" id="">
    <button type="reset(重置) submit(提交) button(无默认功能)"></button>
    <label>
        <input type="checkbox" name="course" value=""> checkbox就是复选框，单选的type值为radio
        其中内容作为选项显示给用户
    </label>
    <select name="">
        <option value="1">1</option> 下拉框的可选项
    </select>
  </form>
- 
