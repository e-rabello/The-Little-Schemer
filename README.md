# The-Little-Schemer
Code and solutions from the book "The Little Schemer"

![image](https://github.com/e-rabello/The-Little-Schemer/assets/8457978/8b96afac-d877-490a-823d-9011ddcc5671)


```scheme
(define atom?
  (lambda (x)
	  (and (not (pair? x)) (not (null? x)))))

(define sub1
  (lambda (n)
    (- n 1)))

(define add1
  (lambda (n)
    (+ n 1)))
```
