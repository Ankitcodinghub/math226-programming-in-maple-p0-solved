# math226-programming-in-maple-p0-solved
**TO GET THIS SOLUTION VISIT:** [MATH226 Programming in Maple P0 Solved](https://www.ankitcodinghub.com/product/math226-1-programming-in-maple-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;125270&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MATH226 Programming in Maple P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Make sure Maple has been configured properly before trying any of the examples below for yourself. Configuration instructions are in the module handbook.

1.1 Getting started

• A Maple program is a sequence of statements, each of which tells Maple to perform some action(s). For example typing

restart

and pressing return causes Maple to clear any currently stored data. It is a good idea to issue a restart command immediately before starting a new problem (including at the beginning of the Maple worksheet).

• Pressing shift+return moves the cursor down one line without executing.

This is useful when writing complicated statements.

• The result of a statement that ends with a colon is not displayed. Otherwise, results will be displayed if they do not generate an excessive amount of output (e.g. a huge matrix). This behaviour can be altered by changing the printlevel and rtablesize parameters (see §1.12 and §1.9, respectively).

• The black square brackets to the left of the window indicate the scope of execution groups. If two statements are inside the same execution group, then they need to be separated by a colon or a semicolon.

• Maple is case sensitive; for example int and Int are different commands.

• Maple has a comprehensive online help system. To obtain information about a command, enter a question mark, followed by the command, e.g. ?evalf. It is usually easiest to scroll down to the examples at the foot of the help page.

• Maple very rarely crashes, but this does sometimes happen. When you start a new worksheet, save it immediately after putting restart on the first line. By default, a saved worksheet will save again automatically every three minutes. Do not turn off autosave.

1.2 Exact vs approximate results

Unless told to do otherwise, Maple tries to produce exact results, which can be problematic. Suppose we wish to determine whether the inequality

Z 1 x

dx &gt; 0.4 0 1 + x5

holds. The statement int( x / ( 1 + x^5 ) , x = 0..1 )

tells Maple to evaluate the integral, but the result is rather complicated, and doesn’tAssignment Project Exam Help really help. The evalf command tells Maple to calculate an approximate numerical value, so the result ofEmail:

evalf( Int( x / ( 1 + x^5 ) , x = 0..1 ) )

is much easier to interpret. Complicated exact results can cause Maple to slow down and appear to freeze if they are reused in later calculations.

Use evalf to avoid complicated exact results.

Remark: evalf( int( … ) ) with a lower case ‘i’ tells Maple to evaluate the integral exactly (if it can) and then convert the result to a decimal. See problem 2.1.

1.3 Comments

Maple ignores material from a # symbol until the end of the line. This is used to insert explanatory notes for statements whose effect is not obvious. # Create a 2 x 2 matrix Matrix( 2 )

If a comment is inserted after a statement, then a colon or semicolon must be included in between.

a := 1 ; # Would generate an error without the semicolon

1.4 Variables

Variables are used to store data. To assign a value to a variable, use the assignment operator :=.

a := 27 : b := 4 : c := a + b :

c

31

a := 27 : a := a + 1 : a 28

Maple allows sequences of assignments to be made in the same statement. a , b := 15 , 21 :

a

15 b

21

This provides a very useful shortcut for swapping variable values.

a := 15 : b := -6 : a , b := b , a :

a

-6

b

15

Often, Maple does not need to distinguish between different types of variable such as integer or complex, but there are situations where this is important.

a := 1 : b := 1.5 :

type( a , integer ) true

type( b , integer )

false

Variables in Maple can possess more than one type.

type( a , integer ) true

type( a , numeric ) true

type( a , complex ) true In this way, Maple differs from languages such as C and Fortran.

:

See sections 2.11 and 2.12 in Understanding Maple for more about variables.

1.5 Conditional statements

A conditional (if) statement causes Maple to test a condition, then carry out different operations depending on whether the condition is true or false. The simplest conditional statement instructs Maple to perform a set of actions only if a condition is true.

if condition then

statement[s]

end if

Note that this is a single statement (which contains other statements). The line breaks are produced by pressing shift+return, and the whole structure must be executed together.

Any statement that evaluates to true or false can be used in an if statement. cold_today := true :

if cold_today then

“Wear your hat!” :

end if

“Wear your hat!”

In cases where a conditional contains a sequence of statements (as opposed to a single statement), these must be separated by colons or semicolons. Otherwise Maple has no way to know where one statement ends and the next begins. a := 1 : b := a :

increase_vars := true :

if increase_vars then a := a + 1 : # &lt;— The colon on this line is crucial! b

:= b + 2 : end if

Boolean operators including and, not and or can be used to construct more complex conditions. : if a &gt; 0 and frac( a ) = 0 then “a is a positive integer.” :

end if

Here, the message is displayed if a is a positive integer. Note the frac command, which returns the fractional part of a number (i.e. the digits after the decimalEmail: point). Using else instructs Maple to take different actions (rather than none at all) if the condition is false.

if condition then statement[s]

else

alternative statement[s] end if

Finally, we can check additional conditions if the first turns out to be false. if condition then statement[s] # Execute if condition is true elif second condition then

alternative statement[s] # Execute if first condition is false, # but second condition is true.

else more alternative statement[s] # Execute if all above conditions # are false.

end if

In the next example, the message “a is negative” will only be printed if both conditions (a &gt; 0 and&nbsp; a = 0 are false). if a &gt; 0 then

“a is positive” : elif a = 0 then “a is zero” : else

“a is negative” : end if

See section 7.1 in Understanding Maple for more about conditional state-: ments.

1.6 do loops

A do loop causes Maple to repeatedly execute the same statements. The next example causes Maple to display the approximate value of π five times.

from 1 to 5 do evalf( Pi ) :

end do

3.141592654

3.141592654

3.141592654 3.141592654 3.141592654

Often we need to use the step number itself during the iteration. This is achieved using a loop with an index variable.

for index from start to finish do

statement[s] end do

Here, index, start, and finish are integers. Initially, index is set to equal start. After each iteration, index is increased by 1. If the result exceeds finish, the loop terminates. Otherwise another iteration is performed. If start exceeds finish, the statements inside the do loop are not executed at all. We can compute 10! as follows. p := 1 :

for j from 2 to 10 do p := p * j : # Updates the value of p

end do :

p

3628800

As another example, we can compute the sum 1 + + + ··· + n1 as follows.

n := 100 : # (Or any other natural number) s := 0 : : for j from 1 to n do s := s + evalf( 1 / j ) : end do : s

5.187377520 Increments

other than 1 are possible. for index from start by increment to finish do statement[s] end do

If increment is negative, the loop will terminate when index reaches a value that is smaller than finish, and will not execute at all if finish exceeds start.

for j from 5 by -1 to 1 do j ;

end do

5

4

3

2

1

To increment a variable through noninteger values, calculate a step size before the loop starts. In the next example, x varies from 0 to 3 in steps of size 3/7.

nsteps := 7 : # Number of steps dx := evalf( 3 / nsteps )

: # Step size for j from 0 to nsteps do x := j * dx ; end do

x := 0. x :=

0.4285714286 x :=

0.8571428572 x :=

1.285714286 x := 1.714285714 x := 2.142857143 x :=

2.571428572 x :=

3.000000000

dx := evalf( 3 / nsteps ) : # Step size for x from 0 to 3 by dx

doEmail: x ;

end do

x := 0.

x := 0.4285714286

x :=

0.8571428572

x := 1.285714286 x

:= 1.714285714 x

:= 2.142857144 x := 2.571428573

x

3.000000002

Never use a decimal as a do loop index.

Remark: In Maple, it is possible to use an exact fraction as a loop index (e.g. try the above example without evalf). However, very few other programming languages allow this, so we will always use integers.

1.7 Break statements

Sometimes it is not possible to predict how many iterations will be needed for a particular task. For these cases we can use a do loop with no final value for the index (or no index at all). In such cases the loop must be terminated by a break statement.

do statement[s]

if condition then break : end if :

end do Given X, we can find the smallest natural number n such that n! &gt; X as

follows.

X := 100.0 : # (Or any other number) f := 1 :

for n from 1 do f := f * n :

if f &gt; X then break : end if : end do :

n

5

This structure is only appropriate when we are absolutely certain that the condition for the break statement will be met at some point, otherwise Maple will enter an infinite loop. If we can’t be certain, we can impose a (large) maximum number of iterations, and check whether the loop has been terminated by the break statement (if this is not the case, the increment will be increased one last time before the loop terminates). max_its := 1000000 : # (Or some other large number.)

for j from 1 by 1 to max_its do statement[s]

if condition then break : end if : end do : if j &gt; max_its then error “Loop did not break” : end if :

Note the error command, which reports that something has gone wrong, and stops execution.

See section 7.2 in Understanding Maple for more about do loops.

1.8 Summing series

Approximately summing a convergent infinite series is a very common application of a do loop with a break statement.

Example

Consider the sum

X∞ ln(1 + j)

S = . j=1 (2 + j)8

We can use a basic do loop to calculate partial (i.e. finite) sums.

S := 0 :

for j from 1 to 100 do

S := S + evalf( ln( 1 + j ) / ( 2 + j )^8 ) : end do : S

0.0001274382682

However, it is difficult to determine the accuracy of this result. Rather than choosing an arbitrary upper limit, we can keep summing until the terms in the series are small.

S := 0 : epsilon := 0.5 * 10^(-10) : for j from 1 do t := evalf( ln( 1 + j ) / ( 2 + j )^8 ) :

if t &lt; epsilon * S then break : end if :

S := S + t : end do :

S

0.0001274382682

Remarks:

• Note that we compare the term t to the current partial sum S, multiplied by , which is small. That is, we stop summing when the next term is small relative to the result. See section 2 for more about relative errors.

• The significance of the value 0.5 × 10−10 is also discussed in section 2.

• Usually we have to take absolute values (i.e. compare |t| to |S|), but in this example all terms are positive.

• When we stop the summation, we discard the tail of the series, not just one term. In other words, if we use

N

SN = X tj, j=1

as an approximation to

∞

S = X tj, j=1

then we are assuming that the magnitude of the tail

S − SNtj j=N+1

is small. However, just checking that one term is small does not guarantee this. The process definitely is valid if

|tj+1| &lt; 0.5|tj| for j = N,N + 1,…

and in practice one can get away with |tj+1| &lt; 0.9|tj| (see problem 1.5).

1.9 Arrays

Often it is convenient to store data using indexed variables A1,A2,A3,… rather than variables A,B,C,… etc. This can be achieved by using an array, which is similar to a vector or matrix, but can have up to dimensions. A := Array( 1..5 ) ; # 1D array h0 0 0 0 0i

B := Array( 1..2 , 1..3 ) ; # 2D array

0 0 0

0 0 0

Note the upper case ‘A’, in Array, which is important. The array command (with a lower case ‘a’) has been deprecated, and should not be used in new worksheets.

By default, the indices for an array start from 1, but you can choose other values, for example

A := Array( 0..6 )

creates an array with seven entries, numbered from 0 to 6. Note that this has a strange effect on the display; see §1.9.4 for more details.

Arrays can also be generated from lists of initial values.

A := Array( [ 7 , 9 , 6 , 5 ] ) h 7 9 6 5i

The individual elements in an array are accessed using an index in square brackets. A[2]

9

A[3] := 27 :

A[4] := -1 : A

h7 9 27 −1i Attempting to access an

element that is out of range results in an error.:

A[6]

Error, Array index out of rangeAssignment Project Exam Help More than one element can be accessed using a range.

A[1..3]

h7 9 27i

A[1..]

h7,9 27 −1i A[..3]

h7 9 27i

A sequence of indices (e.g. 1,2 or 4,1,7) is used to access the entries in an array with more than one dimension.

M := Array( 1..2 , 1..2 )

0 0 M := 0 0

M[1,1] := 5 :

M[1,2] := 3 :

M

Table 1: Rectangular data structures in Maple.

1.9.1 Other rectangular data structures

Aside from arrays, Maple also has lists, vectors and matrices.: The differences between these are summarised in table 1. It is sometimes necessary to convert arrays to vectors or matrices, even though the conversions don’t really do anything.

A := Array( [ [ 1 , 2 ] , [ 3 , -1 ] ] )

A := 3 -1

with( LinearAlgebra ) : MatrixInverse( A )

Error (in MatrixInverse) …

MatrixInverse( convert( A , Matrix ) ) ;

# or MatrixInverse( Matrix( A ) )

A := 7

Bizarrely, some other linear algebra functions, such as Trace and Determinant work with both arrays and matrices.

1.9.2 Bounds

The lowerbound and upperbound functions can be used to enquire about the limits for the indices, so you don’t need to keep track of them manually. If A is a one-dimensional structure (list, vector, or 1D array) then

upperbound( A )

returns the upper bound for the index. For an array with more than one dimension or a matrix,

upperbound( A , n )

returns the upper bound in the nth dimension. Alternatively,

[ upperbound( A ) ] returns a list in which the nth element is the upper bound of A in the nth dimension (it’s probably best to avoid using this version). In all of the above examples, upperbound can be replaced with lowerbound, but remember that the lower bound for a vector, matrix or list is always 1.

A := Array( -1..1 , -2..2 ) :: lowerbound( A , 1 )

−1

upperbound( A , 2 )

2

[ lowerbound( A ) ]

[−1,−2] [ upperbound( A ) ] [1,2]

1.9.3 Example

We can store the first N Fibonacci numbers as follows.

N := 20 : # (Or any other natural number) f := Array(

1..N ) : # Note the capital ’A’. f[1] := 1 : f[2] := 1 :

for j from 3 by 1 to N do f[j] := f[j-2] + f[j-1] : end do :

f[19]

4181

1.9.4 Displaying arrays

There are three things that can prevent Maple from displaying an array in a convenient form.

(i) The array has three or more dimensions.

There is nothing you can do about this, since the screen has only two.

(ii) One or more of the indices does not start from 1.

In this case, convert the array to a matrix or vector to display it.

A := Array( -2 .. 2 ) :

A[1] := 57 ::

A[2] := Pi : Vector( A )

h0 0 0 57 πi B := Array( -1 ..

1 , -1 .. 1 ) :

Matrix( B )

0 0 0

0 0 0

0 0 0

(iii) The array is too large.

The display will truncate arrays (and also matrices and vectors) whose size in any dimension is greater than the parameter rtablesize, the default value of which is 10. You can change rtablesize using the interface command. interface( rtablesize = 20 ) :

1.9.5 Copying arrays

Assigning an array to a new name does not create a copy. Instead it leads to a confusing situation in which the same data is accessible through more than one name.

A := Array( [ 1 , 2 ] ) :

B := A

B := h1 2i B[2] := -27 : B

h1 −27i

A

h1 −27i

To make a copy, use the copy command.

A := Array( [ 1 , 2 ] ) :

B := copy( A )

B := h1 2i

B[2] := -27 : B

h1 −27i A

h1 2i

See section 7.5 in Understanding Maple for more about arrays.

1.10 Tables

Under some circumstances, we need to store a sequence of values without knowing in advance how many there are. A table can be used for this purpose. Unlike an array there is no need to declare bounds for a table; we can just keep adding entries as necessary.

t := table() : t[1] := 5 : t[2] := 72 : t[3] := 44 :

Unfortunately, there is no shorthand way to retrieve multiple values from a table (t[1..3] won’t work). Instead, we have to use the seq command for this. seq( t[j] , j = 1 .. 3 )

5,72,44

Often the most useful thing to do is extract the entries and put them in an array. B := Array( [ seq( t[j] , j = 1 .. 3 ) ] )

B := h5, 72, 44i

Note that using indices in square brackets without stating the type of object you want will produce a table.

A[1] := 55 : A[2] := 68 :

Describe( A )

A::table = table([(1)=55,(2)=68]):

Expecting an array in such circumstances is a common mistake. restart :

A[1] := 55 : A[2] := 68 :

upperbound( A , 1 )

Error, invalid input: …

Don’t forget to declare arrays with the Array command.

1.10.1 Example

Suppose we wish to store a sequence of random numbers each of which lies between 0 and 1, stopping the first time we encounter a value greater than 0.95. There is no way to determine the length of the sequence in advance, so we can’t use an array. Instead, we use a table.

# Initialise random number generator randomize() :

# Create a random number generator function f := rand( 0.0 .. 1.0 ) : t := table() :

for j from 1 do

#Get a random number, add it to the table t[j] := f() :

if t[j] &gt; 0.95 then break : end if : end do :

seq( t[p] , p = 1 .. j )

0.6816119705,0.8802371600,0.9546663364

1.11 Procedures

Simple mathematical functions can be defined using arrow notation (- followed by

&gt;). f := x -&gt; 2 * x :

f( 1 )

2

f( k )

2k

g := ( x , y ) -&gt; sin( x + y ) :

g( 3.1 , 1.2 )

-0.9161659367

Note that multiple variables before the arrow must be enclosed in brackets.

A procedure is similar to to a function, but it can use any Maple code to obtain its results (including do loops and conditional statements).

1.11.1 Example

This simple procedure implements the function f(x) = 2x. f := proc( x ) return 2 * x

: end proc :

f( -27 )

-54

f( a )

2a

1.11.2 Local and global variables

Procedures can have their own internal variables, which cannot be accessed from elsewhere in the worksheet. These are called local variables. Variables elsewhere in the worksheet with the same name are separate entities. : my_proc := proc()

local a : a := 1 :

return :

end proc : a := Pi :

my_proc() : # Doesn’t change a a

π

Here, the value of a is not changed, even though a local variable called a is used inside the procedure. The idea behind this is that the inner workings of procedures can be ‘hidden’ from the rest of the worksheet. It means we don’t need to keep track of which names are used inside procedures, which would be very difficult (any annoying) in large projects.

Variables that are not local are global. These can be accessed from anywhere in the worksheet. If we change local to global in the above example and execute it again, the value of a outside the procedure is now set to 1. This type of side effect can easily lead to errors, especially in large projects where it is difficult to keep track of which names have been used in which places. In general, a procedure should not access or (worse) change global data unless this is absolutely necessary.

1.11.3 Parameter sequences and return statements

We will use the convention that the parameters in brackets after proc are the input for the procedure, and that the results are specified by a return statement. We won’t try to change the parameters from within the procedure (though this is possible in some cases). The next example shows a procedure that solves the quadratic equation ax2 + bx + c = 0.

The coefficients a, b and c are the input for the procedure and the two roots r1 and r2 are the output. solve_quadratic := proc( a , b , c ):

#Solve the equation a * x^2 + b * x + c = 0 local d , r1 , r2 : d := sqrt( b^2 – 4

* a * c ) :

r1 := evalf( ( -b + d ) / ( 2 * a ) ) : r2 := evalf( ( -b – d ) / ( 2 * a ) ) : return r1 , r2 : end proc :

# Test

solve_quadratic( 1 , -1 -6 )

3,-2

Omitting the return statement causes the procedure to return the result of the last calculation. This is an unhelpful feature which can easily lead to mistakes (here only r2 would be returned if the return statement was missing). As a general rule, it is best to always include a return statement, even in cases where this is not strictly necessary. Note that any number of return statements can occur anywhere in a procedure. If processing reaches a return statement, the procedure is terminated immediately. This is useful for dealing with cases where certain situations should trigger an immediate return, but processing should otherwise continue.

In most cases, procedures are not executed directly by a human — they are executed automatically by other parts of the worksheet. Therefore it is important

Numerical Methods for Applied Mathematics

to check that the input is valid. For the quadratic solver, we could check that a, b and c are numbers by changing the first line to the following.

solve_quadratic := proc( a :: numeric , b :: numeric , &nbsp;c :: numeric )

We can also perform checks inside the procedure; thus we might ensure that a 6= 0 by inserting the following after the local declarations.

if a = 0 then error “Leading coefficient should not be zero.” : end if :

With these modifications, both of the statements solve_quadratic( Dr , Ian , Thompson ) : solve_quadratic( 0 , 1 , 1 ) :: result in an error. Maple has many different types that can be used with ::. Execute ?type and scroll down for a list. The most useful for checking procedureAssignment Project Exam Help input are boolean (true or false), integer, posint (positive integer), nonnegint (nonnegative integer), numeric (real) and procedure.

1.11.4 Writing a procedure

Before starting to write a program, break the problem up into parts, and ask yourself whether it makes sense to write each part as a separate procedure. Follow these steps to start writing a procedure.

(i) Think of a sensible name, and start with the proc and end proc statements.

my_proc := proc() end

proc :

By putting the end proc in now, rather than waiting until the procedure is finished, we keep the code in an executable state, so we can test parts of it along the way.

(ii) Insert a comment to briefly describe what the procedure does.

my_proc := proc()

#Does something really clever end proc

:

(iii) Determine the input that the procedure needs, and use the type operator ::

to prevent acceptance of invalid data types. my_proc := proc( n :: integer , m :: integer ) #Does something really clever end proc :

(iv) Use conditional statements and the error command to perform any other checks on the input data, and raise exceptions if anything is wrong.

my_proc := proc( n :: integer , m :: integer )

#Does something really clever if n = m then

error “Doesn’t work if n = m” : end if :

end proc :

(v) Only now should you begin the hard work of coding the actual machinery ofEmail: the procedure.

my_proc := proc( n :: integer , m :: integer )

#Does something really clever

local j , p :

if n = m then error “Doesn’t work if n = m” : end if :

for j from 1 by 1 to n do for p from 1 by 1 to m do statement[s]

Numerical Methods for Applied Mathematics

end do : end do

:

return whatever : end proc :

1.11.5 Example: summing a Taylor series Consider the function defined by the series

X∞ (−x)j

f(x) = j=0 (j + π)j!

We can sum this series using the ideas from section 1.8. There is only one input to the procedure, which is the numeric value x, so we start with the following.

f := proc( x :: numeric )

#Sums the series (-x)^j / ( ( j + Pi ) * j! ) , j = 0, 1, … : end proc :

There are no other checks to do on the input. We will need local variables j, t and s to represent the summation index, the current term and the partial sum, respectively.

f := proc( x :: numeric )

#Sums the series (-x)^j / ( ( j + Pi ) * j! ) , j = 0, 1, … local j , s , t : for j from 0 do

end do :

end proc :

If we calculate each term from scratch, the procedure will be as follows.

f := proc( x :: numeric )

#Sums the series (-x)^j / ( ( j + Pi ) * j! ) , j = 0, 1, …

local j , s , t : s := 0 :

for j from 0 do t := evalf( ( -x )^j / ( ( j + Pi ) * j! ) ) : if abs( t ) &lt; 0.5 * 10^(-10) * abs( s ) then break : end if :

s := s + t :

end do :

return s :

end proc :

However, we can increase efficiency by noting that if

:

rj = (−x)j/j! then

rj+1 = −xrj/(j + 1),

so part of the summand can be calculated recursively.

f := proc( x :: numeric ) #Sums the series (-x)^j / ( ( j + Pi ) * j! ) , j = 0, 1, … local s , j , t , r : s := 0 : r := 1 :

for j from 0 do t := evalf( r / ( j + Pi ) ) :

if abs( t ) &lt; 0.5 * 10^(-10) * abs( s ) then break : end if :

s := s + t : r := -x * r / ( j + 1 ) : end do : return s : end proc :

#Test

f( 1.2 )

0.1316506330

f( -4 )

8.299435700

f( 0 )

0.3183098861

Remarks:

• One should always test a function of this type at x = 0. In some problems one should treat this as a special case, i.e. use something like

if x = 0 thenAssignment Project Exam

Help

return evalf( 1 / Pi ) : end if :

However, if x = 0 here the first term always evaluates to 1/π and then r is updated to 0, so the loop will break on the second term.

• Numerically evaluating a sum of the form

∞ S = X cj(x − a)j&nbsp; j=0

works best when |x − a| &lt; 1, even if the series converges for all x. Many functions have alternative representations that can be used if the convergence of the Taylor series is too slow.

1.11.6 More examples

See the following resources on Canvas:

• Searching Arrays (video)

• Sorting Arrays (video)

• search_array_and_sort_array.mw

• Calculating Catalan numbers (video)

• calculate_catalan.mw

See chapter 8 of Understanding Maple for more about procedures.

1.12 Eliminating errors from a program

Programs are rarely written correctly at the first attempt. The process of removing errors is called debugging.

• Colons and semicolons inside do loops and conditionals have no effect on output. Only the terminating character following the outermostEmail: end do or end if matters in this respect.

• Whether a procedure produces output depends on the terminating character after the procedure call. On the other hand, end proc should always be terminated by a colon; you won’t gain anything useful by omitting this (or using a semicolon).

printlevel := 10 : sin( 2.5 ) ; # This is a procedure

call.

Often, increasing printlevel will cause Maple to output too much material. An alternative is to display the values of relevant variables using the print command. For example p := 1 :

for j from 2 to 10 do p := p * j : #Updates the

value of p print( j , p ) : end do :

The integers j and p are output at each step, regardless of the current value of printlevel. The more sophisticated command printf allows you to specify details of the output format, such as the number of character columns to use and the number of decimal places to show. p := 1 :

for j from 2 to 10 do p := p * j : #Updates the value of p printf( “j = %2d , p = %10d ” , j , p ) : end do :

See printf_demo.mw and also §7.4 of Understanding Maple for more details.

1.13 Style guidelines

The same program can be written in many different ways. Our main concerns are to maximise efficiency (primarily in processor time, but also in memory usage). However, it is also important to write programs that are logically structured and understandable, because this will help you to avoid making mistakes. In addition, parts of a program will often be useful again later, saving time and effort, but trying to reuse a badly written program long after its creation is difficult and error prone.

Format your code according to the following rules.

• Use explanatory comments (starting with a ‘#’ symbol) for lines or blocks of code whose purpose is not immediately obvious. Maple will ignore these.

• Use extra space in your code; i.e. h := 0.5 * ( a + b ) :

fh := evalf( f( h ) ) :

rather than h:=0.5*(a+b): fh:=evalf(f(h)):

Large blocks of unspaced code can be difficult to read.

• Use blank lines to separate different tasks within a program.

• Indent code inside procedures, do loops and if statements by two spaces. my_proc := proc( n :: integer , m :: integer ) #Does something really clever

local j , p :

for j from 1 by 1 to n do for p from 1 by 1 to m do statement[s] end do : end do :

return whatever :

end proc :

This makes it easier to see the overall structure of the program.

• Do not write long lines (more than about 100 characters) of code.

• No more than one assignment operator (:=) should appear on a line.

• The following elements should always appear on a line of their own:: I the first line of a procedure (containing proc),

I end procAssignment Project Exam Help,

I return statement,

I for … do, I end do,

I if … then, I end if.

• Do not abbreviate end if, end do or end proc to end, because this makes it difficult to see what statement is being terminated. If you must use abbreviations, you can use fi and od in place of end if and end if, respectively.
