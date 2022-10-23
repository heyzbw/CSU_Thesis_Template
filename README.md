# CSU_Thesis_Template
中南大学本科生毕业设计论文LaTex模板

## LaTex常见语法记录
- 有编号分点
~~~
\begin{enumerate}
	\item 
	\item 
	\item 
\end{enumerate}
~~~
- 无编号分点
~~~
\begin{itemize}
	\item
	\item 
	\item 
\end{itemize}
~~~
- 图像引入与引用
~~~
\begin{figure}[!h]
	\centering
	\includegraphics[width=.85\textwidth]{P1}
	\caption{图片示意}
	\label{P1}
\end{figure}

\ref{P1}
~~~
- 表格表头添加
~~~
\begin{table}[!h]
	\centering
	\caption{符号说明表}
	\label{fuhao}
~~~
- 参考文献
~~~
\cite{}
bibtex格式
文献标记不包含数字
~~~
- 字体大小
~~~
Command     Nominal Point Size      Exact Point Size
\tiny               5                       5
\scriptsize         7                       7
\footnotesize       8                       8
\small              9                       9
\normalsize        10                      10
\large             12                      12
\Large             14                   14.40
\LARGE             18                   17.28
\huge              20                   20.74
\Huge              24                   24.88
~~~
- 添加斜杠
~~~
\usepackage{diagbox}

~~~
- 引用python语法（提前加入配置文件）
~~~
\begin{python}

\end{python}
~~~

模板还有很多不足之处待改进，欢迎大家在issue里提问。


------------------------------1.0/2022/10/21------------------------------
