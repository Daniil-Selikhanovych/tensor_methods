# tensor_methods
Implementation of Tensor Methods for convex optimization

In this project we implement tensor methods for the minimization of p-th order smooth convex functions. We compare the performance of the tensor method proposed in (Nesterov,2018) with $p = 2$ and $p = 3$.

[1]. Gasnikov, Alexander, et al. "The global rate of convergence for optimal tensor methods in smooth convex optimization." arXiv preprint arXiv:1809.00382 (2018).

[2]. Nesterov, Yu. "Implementable tensor methods in unconstrained convex optmization.—2018.—CORE Discussion Papers 2018005."

[3]. Yu. Nesterov, B. Polyak. “Cubic regularization of Newton’s method and its globalperformance”.Mathematical Programming,108(1), 177-205 (2006).

[4]. Yu. Nesterov. “Accelerating the cubic regularization of Newton’s method on convexproblems”.Mathematical Programming,112(1) 159-181 (2008).

[5]. A.R. Conn, N.I. M. Gould, and Ph.L. Toint. Trust Region Methods.MOS-SIAMSeries on Optimization, New York (2000).

[6]. Родоманов, А. О., Кропотов, Д. А., Ветров, Д. П. Анализ быстрого градиентного метода Нестерова для задач машинного обучения с $𝐿_1$-регуляризацией (2014).

We develop the particular code for two classes of problems, namely: (1) The class of convex functions described in (Nesterov,2018) which are hard for tensor methods, we will refer to this functions as "hard tensor functions", (2) logistic regression problem.
