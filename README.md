# Polynomial-Fitting

There is a ground-truth model y = f(x) + ξ, x ∈ [0, 1], where
f(x) = 1 + 2 sin(5x) − sin(15x),
and ξ is additive noise that is Gaussian distributed with zero mean and unit variance. The added noises
for different x values are independent. Using this model, we would like to test polynomial fitting. You can
utilize existing packages for fitting.

Specifically,
1) Generate 51 equally spaced x values between 0 and 1: xi =
i
50 , i = 0, 1, · · · , 50.
2) Generate yi values for these xi values: yi = f(xi) + ξi
, i = 0, 1, · · · , 50, where ξi are independently
and identically distributed standard Gaussian random variables. The set of generated values (xi
, yi),
i = 0, · · · , 50, will serve as the training data.
3) Fit a polynomial of order k = 1 to the dataset, minimizing the residual sum of squares. Plot the
fitted polynomial using black color.
4) Repeat the steps 2) to 3) 30 times. Keep all the plotted polynomials.
5) Repeat the experiment for k = 3, 5, 7, 9, 11. For each k, use a new figure. Also, on each figure,
show the function f(x) using red color.

![1](https://github.com/user-attachments/assets/37df42d5-b703-4145-b9db-e1840f5f7dd7)
![2](https://github.com/user-attachments/assets/57e316d5-0d2a-4384-a17e-ca4c7e1a7768)
![3](https://github.com/user-attachments/assets/17ef3e7e-8dfe-44b2-ac95-2f67670fa58f)
![4](https://github.com/user-attachments/assets/63760457-092c-49c6-b3b3-16f6cda1a817)
![5](https://github.com/user-attachments/assets/090f996a-95bc-4469-b45d-7dfbb0be38cc)
![6](https://github.com/user-attachments/assets/6737a984-39f2-4251-b9fc-0c81b1bda3a3)
