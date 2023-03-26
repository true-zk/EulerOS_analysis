# EulerOS_analysis
SJTU_IS_OS2022lab:EulerOS's analysisreport


选择：lab2和lab3的必做部分


文件和说明：两份实验报告：lab2.doc   lab3.doc
	两份函数调用流程图pdf：lab2函数调用流程图.pdf   lab3函数调用流程图.pdf
	一份修改后的代码：page_alloc.c
	由于页面淘汰的情况实在太多，为了Log淘汰的页面，就一路查看函数调用，发现最后都会调用free_one_page()于是就只在这里输出pfn
