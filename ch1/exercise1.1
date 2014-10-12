;; Exercise 1.1

10
12
8
3
6
a
b
17
false
(if) 4
(cond) 16
6
(*) 16

;; Exercise 1.2

(/ (+ 5 4 (- 2 (- 3 (+ 6 (4/5)))))
   (* 3 (- 6 2) (- 2 7)))

;; Exercise 1.3
(define (lsos a b c) (if (and (> a b) (> b c)) (+ (* a a)
                                               (if (> b c) (* b b)
                                                           (* c c)))
                                               (+ (* b b) (* c c))))

;; Exercise 1.4
By evaluating statements, and then applying their results, we're able
to take group of expressions and simplify them, using a small set of rules.
The text has mentioned exceptions to being able to do accomplish this, but I'm
not sure what those are yet. I can imagine anything dealing with mutability, but
I'm not sure

;; Exercise 1.5
normal order should return '0'. It does this because the value of p
is never actually computed. It's not computed because the predicate expression
is evaluated first, and only after that does it resolve the consequent or the alternative.

Where as if it were to run in applicative order, the subexpressions would all be reduced to their
primitive forms first, leading to it trying to evaluate p. Since p resolves to the name 'p',
it should then try to evaluate p again, and again. It seems like applicative order evaulation will
lead to an unending loop?

;; Exercise 1.6
When the interpreter evaluates the new-if condition, it computes what the values passed in, as arguments
are. When it does this, it attempts to execute `sqrt-iter` no matter if the cond would process it or not.
This is because, as shown in 1.1.5, scheme uses applicative-order evaluation, and it first calculates what
the passed arguments evaluate to before applying the function.

;; Exercise 1.7
(define (good-enough? guess x)
  (< (abs (- (square guess) x)) 0.001))

The book claims our good enough function function well for very small numbers, as arithmetic operations
are done with only limited precision. Apparently good-enough? is also inadequate for very large numbers
as well.

They suggest watching how `guess` changes from one iteration to the next, and stops when the change is a
small fraction of the guess.

They want us to design a square-root procedure which uses this as an end test. Additionally, they ask if
this method is better for handling small and large numbers

;; -----
The function breaks down around 0.001 and it's really problemmatic at 0.0001.
This is because when you have values which are smaller than the tolerance, the program simply doesn't
catch them. Additionally, for very large numbers it can take a long time to reach a point where the difference
between the guess and the x value is 0.001.

A rewrite would look something like the following:
;; This handles small numbers, but a number like 1*10^13 has issues. 
;; When you execute good-enough, you can reach a point where you're sitting at a number like
;; 1.000000000001025, which seems like it continues foreversies.
(define (good-enough? guess x)
  (and (or (= (/ (square guess) x) 1)
           (< (/ (square guess) x) 1))
       (> (/ (square guess) x) 0.98)))

;; Exercise 1.8
Don't feel like doing this. Come back later maybe?

