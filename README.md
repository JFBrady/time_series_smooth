# time_series_smooth
Unique formulation of Exponential Smoothing forecasting for managing computing system traffic overload.

This implementation of Exponential Smoothing:
1. Resolves forecasting startup issues that have limited Exponential Smoothing as a prediction tool
2. Satisfies implementation requirements to perform calculations in integer math,
3. Resets the forecast seamlessly when traffic subsides.

These features are described graphically and  analytically in an ICCDA 2020 conference paper titled [“Computing System Congestion Management Using Exponential Smoothing Forecasting”](https://dl.acm.org/doi/10.1145/3388142.3388146) that can be downloaded from the ACM Digital Library as an open access document.
## Program setup and execution
The time_series_smooth_doc.pdf file contains the computer program setup details, compilation instructions, and execution procedure. The C language program, time_series_smooth.c, included in the src directory implements the Exponential Smoothing forecasting algorithm.
## Background
Siemens filed for exclusive rights to this technique for telecom products in 2003 and obtained US patent [US7301903B2](https://pdfpiw.uspto.gov/.piw?PageNum=0&docid=07301903&IDKey=919E975B320C&HomeUrl=http%3A%2F%2Fpatft.uspto.gov%2Fnetacgi%2FnphParser%3FSect1%3DPTO1%2526Sect2%3DHITOFF%2526d%3DPALL%2526p%3D1%2526u%3D%25252Fnetahtml%25252FPTO%25252Fsrchnum.htm%2526r%3D1%2526f%3DG%2526l%3D50%2526s1%3D7301903.PN.%2526OS%3DPN%2F7301903%2526RS%3DPN%2F7301903) in 2007 with this author, an employee at the time of the filing, the sole inventor.

## References
\[1.\] Brown, R. G., 1963. Smoothing, Forecasting and Prediction of Discrete Time Series. Prentice-Hall, Inc., Englewood Cliffs, N.J. 
\[2.\] Giffin, W. C., 1971. Introduction to Operations Engineering. Irwin, Inc, Homewood Illinois.