# xhyx
win10自带输入法挂小鹤双拼再挂音形

1. win10自带输入法挂小鹤双拼（本方法来自 散步de鹤）

右键开始→运行：Regedit（注册表编辑器）

定位计算机\HKEY_CURRENT_USER\Software\Microsoft\InputMethod\Settings\CHS

右键新建字符串值
数值名称：UserDefinedDoublePinyinScheme0
数值数据：小鹤双拼*2*^*iuvdjhcwfg^xmlnpbksqszxkrltvyovt
重启电脑

2. 在上一步的基础上挂小鹤音形
下载win10微软拼音小鹤音形词库.dat
右键微软输入法的“中”字，用户自定义短语
导入刚才下载的win10微软拼音小鹤音形词库
选择已导入的aa词条，修改为拼音为a，保存后关闭
