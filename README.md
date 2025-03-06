java c
Numerical Computing, CSCI-UA 421 
Spring 2025 
Course Instruction Mode 
This course will be taught in person. Lectures will be given using the classroom blackboard   and computer   demos.   Participation   in   the   class   is   required,   and   you will be expected to respond to questions via electronic polls. The topic of each class   will be   posted   on   this   web   page,   along   with   references   to   the relevant parts of the textbooks as well as class notes. Don't hesitate to ask   questions   during   lectures,   either by raising   your   hand   or   directly   speaking   out   if   I don't notice you. 
. Small Group Meetings 
At the start of the semester I would like to meet all   students   in   small   groups   in   my   ofﬁce.   The   purpose   of these meetings   is   for me   to   get   to   know   you   and   also for you to meet some other students in the   class.   Please   sign   up here. If none of the times work   for   you,   send   me   email.
● Ofﬁce Hours 
I will hold regular ofﬁce hours on Wednesdays at 3-4 p.m. in   CIWW 429,   starting Jan   29.   If this time   does not   work   for   you,   send   me   email   to   set   up   an   appointment, or   just try dropping by my ofﬁce any time.
Tutor 
Ellen Persson, a Ph.D. student in mathematics, will be a   tutor   for   this   class   ﬁve   hours   per   week.   Starting   Jan   27,   she   will   hold   ofﬁce   hours   on   Mondays, Wednesdays at   1-2pm and Tuesdays, Thursdays at   10-11am, all in CIWW 412,   and   online by   appointment   if necessary   (send email to   [email   protected])   .
. Course Summary 
Introduction to numerical computation: the need for ﬂoating-point arithmetic, the IEEE ﬂoating-point   standard,   correctly   rounded   arithmetic,   exceptions.   Conditioning and stability. Direct methods for numerical linear algebra   (Gauss elimination   (LU   factorization)   and   Cholesky   factorization   for   systems   of linear equations, normal equations and QR factorization for least   squares problems)   . Eigenvalues   and   singular values.   Iterative   methods   (Newton's   method   for solving a single nonlinear equation or a   system   of nonlinear equations).   Discretization   methods   (approximating   a   derivative,   solving   a   differential equation with boundary conditions). Polynomial interpolation and cubic splines. Convex   optimization:   the   gradient   method   and   Newton's   method.
Importance of numerical computing in a wide variety of scientiﬁc applications. How can   you   tell   how   accurate   your   answers   are?   We   will   use   the computer a lot in class and you should become quite   proﬁcient   with   MATLAB   by   the   end   of the course.   If you like math   as   well   as   programming,   you   should enjoy this class! 
. Prerequisites 
Computer Systems Organization (CSCI-UA 201), either Calculus I (MATH-UA   121)   or both   of Mathematics for Economics   I   and   II   (MATH-UA 211   and   212), and Linear Algebra (MATH-UA 140), or permission of instructor. Knowledge of MATLAB in advance   is   not   expected.   The   Linear Algebra prerequisite is particularly important; if you are not sure if you have enough background, send me   email   to   discuss   this.   If you have   already taken the   math   department's Numerical Analysis course, you will ﬁnd there is a lot of overlap with this   course; if you   are not   sure   if you   should take the   course   anyway, please send me email to   discuss this.
. Requirements 
o       Attend class, responding to polls (10% of the ﬁnal grade)   (if you are unable to   attend   a   class, because   of   sickness   or   for   another   reason,   please   let   me   know by email)
o       Read the assigned chapters from the two text books, and   other   assigned   notes
o Do the homework (30% of the ﬁnal   grade)
o Write the midterm exam and ﬁnal exam (each   30% of the ﬁnal   grade)
. Required Text Books 
o Numerical Computing with IEEE Floating Point Arithmetic, by the instructor
The ﬁrst edition of this book was published by SIAM in 2001, and my   web page   for the   ﬁrst   edition   is here . Although the basic principles   of IEEE ﬂoating point arithmetic have not changed much since 2001, the technology implementing   them   has.   I   have   just   ﬁnished   writing   the   second   edition   of this book, which will be published by SIAM later this year. You can access the ﬁnal   draft   of the   second edition here but please   do   not post this anywhere. You will be expected to read Chapters   4, 5, 6, 7,   11,   12   and   13,   and   I   will   ask   questions   about these   chapters   in   the   homeworks   and midterm exam, but I recommend that you read the whole book (it is only   140   pages,   and   you   may   ﬁnd   Chapter   15,   which   is   about   the   new   ﬂoating   point formats for AI, quite interesting). If you ﬁnd typos or have other comments please send them   to   me   by   email. 
o A First Course on Numerical Methods, by Uri Ascher and   Chen Greif
This book is currently being revised by the authors. The revised chapters will be posted here   as we   get to   the   relevant   topics.
Chapter 1 (good to read, but not required as this is mostly covered in my book) 
Chapter 2 (not required now, we'll cover this later)
Chapter 3 (linear algebra background, read except as noted) 
Chapter 4 (direct methods for linear systems, important to read this) 
Chapter 5 (please read Section 5.1 only) 
Chapter 6 (please read, except as noted in pdf ) 
o Required Software 
MATLAB: available for free to NYU students 
There are many books on MATLAB; I recommend MATLAB Guide, by D.J. Higham   and   N.J.   Higham,   SIAM,   2000.   Chapters   can be   freely   downloaded via the NYU library subscription using   this link.
o Class Forum The class forum will use the Ed Discussion tool in Brightspace. Feel free to   ask   questions   about   the   class   and   homework   here,   either   to   everyone,   or   just to me and the graders, and feel free to   answer questions posed by   other   students.   However,   don't   post   solutions   to   the   homework!   Helpful   hints      are   ok. Please   participate!
o Lecture Schedule and Notes (future dates are tentative) 
1. Tue Jan 21: Introduction and overview, IEEE ﬂoat代 写Numerical Computing, CSCI-UA 421 Spring 2025Matlab
代做程序编程语言ing point representation   (my book,   Ch   1-4), notes 
2. Thu Jan 23: Rounding, absolute and relative rounding errors (my book,   Ch   5), notes 
3. Tue Jan 28: Two loop programs (see Ch   10),correctly rounded ﬂoating point operations,   exceptions   (my book,   Ch   6-7), notes ,   mﬁles ﬁrstLoopProgram.m , secondLoopProgram.m , parRes.m , roundModes.m 
4. Thu Jan 30: Floating point microprocessor and programming language support for   the   standard,   cancellation,   approximating   a   derivative   by   a   difference quotient (my book, Ch 8,9,11), notes , mﬁle differenceQuotientErrors.m 
5. Tue Feb 4: Conditioning of problems, intro to stability of algorithms   (my book,   Ch   12-13), notes ,   mﬁles condNumExpt.m , compoundInterest.m 
6. Thu Feb 6: More on stability of algorithms (my   book,   Ch   13), notes ,   mﬁle approxExp.m 
7. Tue Feb   11: Linear   algebra review: linear independence of vectors, conditions for square   matrix   to be   nonsingular,   matrix rank.   Vector   and   matrix norms, computing the matrix ∞ norm (AG, Ch   3).   Skip   sections   on positive   deﬁnite   matrices,   orthogonal   matrices,   eigenvalues, singular values, SVD and differential equations for   now (we   will return   to   these   later), notes 
8. Thu Feb   13: Polynomial interpolation via Vandermonde matrices (AG, sec   3.5).   Matlab's \ (backslash).   Solving linear   systems   of equations   (AG, sec 4.1-4.2): back substitution, Gaussian elimination without pivoting, equivalence to   LU   factorization   (decomposition), notes ,   mﬁles plotInterpPoly.m , gauss_el.m , backsolve.m 
NO CLASS on Tue Feb   18
9. Thu Feb 20: more details on the   LU factorization (AG,   sec   4.2),   Gauss   elimination   with partial   pivoting   (GEPP)   and   the   PA=LU   factorization   (AG, sec 4.3), notes
10. Tue Feb 25: Continuation of GEPP and its equivalence to PA=LU, demo that   on random   matrices,   GEPP is   stable,   rare   worst   case   instability   of GEPP (AG, sec 4.3), banded matrices (AG, sec 5.1), Matlab's   sparse   matrices, notes ,   mﬁles geppUnstableExample.m , geppUnstableExampleDemo.m 
11. Thu Feb 27: Cholesky factorization of   positive deﬁnite matrices. Use my Cholesky notes instead   of   AG   sec   4.4. notes ,   mﬁle chol3.m 
12. Tue Mar 4: Least squares: the normal equations and   solution by Cholesky   factorization   (AG,   sec   6.1,   p.173-183),   orthogonal   vectors   and   matrices (AG, p.   87-88), notes ,
13. Thu Mar 6: Least squares: solution via QR   factorization   using   Householder   reﬂections   (AG,   sec   6.2   and   6.3,   but   skip   the   subsection   on   the
Gram-Schmidt process   which is classical but not used much, and skip the   part   on   the   SVD   and   the   pseudo-inverse   for   now), my notes on QR , notes 
14. Tue Mar   11: Errors, residuals, condition numbers and stability for   solving Ax=b   (AG,   sec 4.5, p.132--134), notes ,   mﬁles errorResidualConditioningStabilityDemo.m , getIllCondRandomSymPosDefMtx.m 
15. Thu Mar   13: TBA, release   practice midterm
16. Tue Mar   18: Review of   practice midterm
17. Thu Mar 20: Midterm Exam. No notes, laptops, phones or other devices permitted.
o Exams 
The midterm will cover all lecture topics before spring break. The focus   will   be   on:   my   book   chapters   4-7   and   11-13,AG   chapters   4-6
(skipping sections as noted in the PDF notes),   with emphasis   on   the   topics   covered   in   the homeworks,   but   also   other   topics   covered   in   class.   You will be asked to write MATLAB code in some   questions.   The   midterm   will   be   in   class   on   Thu   Mar   20,   11-12:15,   CIWW   101.   No   notes,   laptops, phones or other devices permitted.
The ﬁnal exam will focus mostly on the topics discussed   after   spring break, with   an   emphasis   on   the   topics   covered   in   the   homeworks.   You
will be asked to write MATLAB code in some questions.   The   ﬁnal   exam   will   be Wed   May   7   ("reading   day"),   12:00--1:50   pm,   CIWW   101.   No   notes, laptops, phones or other devices permitted.
o Homework 
There will be 8 homework assignments, 5 before spring break   and   3   after.   If you have questions   about   the   homework,   please   post   them   on   Ed Discussion, where the tutor or I, or maybe other students if they wish, can   answer   them.   It   is   important   that   you   do   the   homework   mostly   by   yourself   (not   jointly with another student), but   when you get stuck,   I   encourage   you   to   consult   with   other   students,   the   class   tutor   or   me,   or   the   web,   or   even AI tools, to get help when necessary. However, when you get help from ANY of these sources, or any other source, or give help to other students, it's important to acknowledge that in writing in your homework submission, explicitly explaining how much help you got and how much of the work you did yourself. Submitting work not done by   you   as if it were your   own   is   called   plagiarism   and   is   not   acceptable.   For   more information, see the CS department's policy on integrity.   Penalty for not   acknowledging   your   sources:   zero   for the   homework.   Finally,   remember   that if you don't mostly do the homework yourself, you will not learn the skills   you   need   to   be   able   to   pass   the   midterm   and   ﬁnal   exams   . 
Homework assignments will be posted here but you should submit your homework   on   Gradescope. Homework is due at 11:59 pm on the given date. Late homework will be penalized 10% if just one day late, and 20% if between two and seven days late. Homework will not be accepted more than one week late, except in special circumstances. If you have questions about the   grading   of the homework, post   a private question to me and the grader on Ed Discussion.
Homework 1, posted Jan 23, due Jan 30
Homework 2, posted Jan 30, due Feb 11
Homework 3, posted Feb 11, due Feb 20
Homework 4, posted Feb 20, due Mar 4
Homework 5, posted Mar 4, due Mar 13
o Don't Hesitate to Ask for Help 
If you have questions, ask them in class or on the class forum,   come to   my   ofﬁce   hour   or   send   me   email   to   set   up   an   appointment.   Don't   wait   until   it's too late!



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
