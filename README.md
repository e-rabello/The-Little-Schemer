# The-Little-Schemer
Code and solutions from the book "The Little Schemer"

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
