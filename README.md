This code corresponds to the paper "Fast elastic net support vector machine with ramp squared loss for large-scale classification"
Huajun Wang,  Wenqian Li, Yuanhai Shao

If you are using our code, please give proper citation to the above given paper.

The codes of the real data is described as follows:

The code of real data is named as "demonRealData.m". Running the "demonRealData.m" file can obtain the results of real data of our algorithm.

Inputs: X -- the sample data, dimension, \in\R^{m-by-n}; (required) 
y -- the classes of the sample data, \in\R^m; (required) y_i \in {+1,-1}, i=1,2,...,m 
pars -- parameters (optional)

pars: Parameters are all OPTIONAL 

pars.kappa-- Starting point of kappa \in\R^m, (default, zeros(m,1)) 

pars.nu -- A positive scalar in (2^-4,2^-6,...,2^4).(default, 1) 

pars.delta -- A positive scalar in (2^-4,...,2^4).(default, 1) 

pars.nu1 -- A positive scalar in (10^-4,2^-6,...,10^4).(default, 1) 

pars.maxit -- Maximum number of iterations, (default,1000) 

pars.tol -- Tolerance of the halting condition, (default,1e-3)


Outputs: Out.iter: Number of iterations 

Out.time: CPU time 

Out.bbeta0: The solution of the primal problem, namely the classifier 

Out.h: The solution h 

Out.tau: The solution tau 

Out.alpha: The solution alpha 

Out.nsv: Number of support vectors 

Out.s: Sparsity level of the solution
 
Out.acc: Training classification accuracy 

Out.error: Classification error 

The all real dataset can be downloaded as follows：the libsvm library：(https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/), the kaggle library： (https://www.kaggle.com/datasets) and the uci library ：(http://archive.ics.uci.edu/ml/datasets.php)
