#lang racket

(build-list 5 (lambda (x) (+ x 1)))

(build-list 5 (lambda (x) (/ 1 (+ x 1))))

(build-list 5 (lambda (x) (* 2 x)))

(define (cubic a b c) (lambda (x) (+ (expt x 3) (* a (expt x 2)) (* b x) c)))

(define (twice x) (lambda (n)(x (x n))))