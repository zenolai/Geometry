
<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <img src="http://latex.codecogs.com/gif.latex?\frac{\partial J}{\partial \theta_k^{(j)}}=\sum_{i:r(i,j)=1}{\big((\theta^{(j)})^Tx^{(i)}-y^{(i,j)}\big)x_k^{(i)}}+\lambda \theta_k^{(j)}" />
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

# Geometry


<img src="http://latex.codecogs.com/gif.latex?\frac{\partial J}{\partial \theta_k^{(j)}}=\sum_{i:r(i,j)=1}{\big((\theta^{(j)})^Tx^{(i)}-y^{(i,j)}\big)x_k^{(i)}}+\lambda \theta_k^{(j)}" />


 \begin{document}
\renewcommand\bibname{References} %Renames "Bibliography" to "References" on ref page
 
 %include other pages
\input{./title.tex}                 %调用标题的tex文件
\input{./certificate.tex}
\input{./abstract.tex}              %调用摘要的tex文件

\pagenumbering{roman} %numbering before main content starts
\tableofcontents
\listoffigures
\newpage
\pagenumbering{arabic} %reset numbering to normal for the main content

 \input{./prob-definition.tex} %objective changed to problem definition
\input{./introduction.tex} %literature survey included in this
\input{./work-done.tex}
\input{./future-work.tex}
 \input{./conclusion.tex}
\input{./acknow.tex}
\input{./ref.tex}

\end{document}
