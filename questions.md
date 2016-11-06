# Personality

#### Why do you want to work for us?

    RELAX!
    THINK!
    DO NOT HURRY!

#### Questions for new employer?

- What is the usual team size?
- What are my changes to get training and mentoring?
- How do you resource a project?
- What kind of projects do you have? (which technologies are in use?)
- Which are working benefits/perks?

#### Which are your strenghts?

- I communicate openly
- I try to be unbiased - I try to research problem domain carefully
before making deduction to go too far. (This is also my weakness;
I don't like to speculate.)

#### Which are your weaknesses?

Menen joskus liian syvälle ongelmaan. Tällöin unohtuu helposti
kokonaiskuva ja se että joskus pitää myös toimittaakin (softaa) eli
saada valmista; mä yritän ehkä liian usein löytää aina parempaa
(jos ei parasta) ratkaisua (esim. nopein algoritmi, kaunein koodinpätkä).
Joskus pitää muistaa että paras ratkaisu ei välttämättä tarkoita sitä
että koodi näyttää kauniilta vaan sitä että pysyy aikataulussa ja että
koodi yleen sä toimii.

#### Which are the most important skills a software developer should possess?

- ability to learn continuously
- ability to communicate clearly and open-mindedly

#### What should modern software developer know to manage in his profession?

#### Which programming languages should modern software developer master?

    No one should call himself a professional if knowing only one language. - Bjaerne.

- Rule of thumb: 5 programming languages, preferably from different paradigms.
Why? It humbles and teaches that there is no single right way to do things.

- JavaScript, Java, Haskell, C, Perl (or some other scripting language
like Ruby/Python) (Larry Wall - developer of Perl)

- Most known and most used: C++, Java, Python (Ruby, JavaScript). -Bjaerne

- olisi fiksua osata jotain erilaista näiden viiden lisäksi
(perspektiivin vuoksi); tähän funktionaaliset kielet sopivat hyvin.
Esim. Haskell.

- High performance numerical calculation (useimmille ne ovat kuitenkin esoteerisiä):

esoteerinen: tietämystä, joka on vain tietyn suljetun piirin, toisin
sanoen ″tietoon vihittyjen″ saavutettavissa.

#### What are the topics you are most excited about?

#### How do you build quality into a software product?

**READ**: The Pragmatic Programmer: from journeyman to master

- Minimise time between stages; important technique for building quality
into the development process is to minimise the time between development,
testing and bug fixing. Rather than logging bugs, deal with them immediately.
Logging bugs in a lot of cases is in fact waste. If the tester can test the code as
soon as it’s developed, and the developer can fix any bugs as soon as they are
found, what is the value in logging them? On the other hand, a long gap between
producing the code, testing it, and before fixing the bugs results in a loss of continuity.
A loss in continuity that causes delays from task switching, knowledge gaps, and
a lack of focus.

- Frequent Integration; build regularly and frequently - at least daily, if not hourly.
Minimising the gap between builds also reduces another form of waste, that is
integration. On large waterfall projects, the integration and regression testing
phases of the project can be very lengthy. Regular builds and frequent integration
avoid that problem.

- Automation; automate steps that you need to repeat often.

#### What is "lean" thinking?

- Agile is dead. Lue codinghorror.com

#### What have been your challenges in earlier projects?

- Quality of the product, bug freeness
- Keeping schedule
- Time

# Technical questions

https://www.interviewcake.com/ruby-interview-questions
http://www.skilledup.com/articles/ruby-on-rails-interview-questions-answers
https://www.toptal.com/ruby-on-rails/interview-questions
https://www.toptal.com/javascript/interview-questions
https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95#.94cn7go3a
https://gist.github.com/ryansobol/5252653
http://vlad.omnipragmatic.com/10-best-ruby-and-rails-interview-questions-and-answers/
https://www.toptal.com/ruby/interview-questions

#### What is the problem that "MVC" solves?

- Model-View-Controller...long explanation...

#### What is MVC?

- MVC on tapa jakaa sovellus kolmeen osaan:
    - "malli-näkymä-käsittelijä", on ohjelmistoarkkitehtuurityyli
     (suunnittelumalli) jonka tarkoituksena on käyttöliittymän erottaminen sovellusaluetiedosta.
    - a model, which holds the business data^?^
    - a view, (or views) which is the presentation layer for application
    - a controllel, which exists to separete model from view - a layer between a model and a view.

- business data
- presentation layer

#### What is the difference between MVC vs. MVP vs. MVVC?

#### What is an object? What is a class?

In computer science, an object can be a variable, a data structure,
or a function or a method, and as such, is a location in memory having
a value and possibly referenced by an identifier.

In short, a class is the definition of an object, and an object is instance
of a class. We can look at the class as a template of the object; it describes
all the properties, methods, states and behaviour that the implementing
object will have.

#### What is a thread?

In computer science, a thread of execution is the smallest sequence of
programmed instructions that can be managed independently by a scheduler,
which is typically a part of the operating system. The implementation
of threads and processes differs between operating systems, but in most
cases a thread is a component of a process. Multiple threads can exist
within one process, executing concurrently and sharing resources such
as memory, while different processes do not share these resources. In
particular, the threads of a process share its executable code and the
values of its variables at any given time.

Threads vs. processes

Threads differ from traditional multitasking operating system processes
in that:

- processes are typically independent, while threads exist as subsets
  of a process

- processes carry considerably more state information than threads,
  whereas multiple threads within a process share process state as well
  as memory and other resources

- processes have separate address spaces, whereas threads share their
  address space

- processes interact only through system-provided inter-process
  communication mechanisms

- context switching between threads in the same process is typically
  faster than context switching between processes.

#### What is the difference between stack and heap?

#### What is polymorphism

#### What is duck-typing?

#### Explain virtual function?

In object-oriented programming, in languages such as C++, a virtual
function or virtual method is an inheritable and overridable function
or method for which dynamic dispatch is facilitated. This concept is
an important part of the (runtime) polymorphism portion of
object-oriented programming (OOP).

The concept of the virtual function solves the following problem:

In object-oriented programming, when a derived class inherits from
a base class, an object of the derived class may be referred to via
a pointer or reference of the base class type instead of the derived
class type. If there are base class methods overridden by the derived
class, the method actually called by such a reference or pointer can
be bound either 'early' (by the compiler), according to the declared
type of the pointer or reference, or 'late' (i.e., by the runtime
system of the language), according to the actual type of the object
referred to.

Virtual functions are resolved 'late'. If the function in question is
'virtual' in the base class, the most-derived class's implementation
of the function is called according to the actual type of the object
referred to, regardless of the declared type of the pointer or
reference. If it is not 'virtual', the method is resolved 'early' and
the function called is selected according to the declared type of the
pointer or reference.

Virtual functions allow a program to call methods that do not
necessarily even exist at the moment the code is compiled.

In C++, virtual methods are declared by prepending the virtual keyword
to the function's declaration in the base class. This modifier is
inherited by all implementations of that method in derived classes,
meaning that they can continue to over-ride each other and be
late-bound. And even if methods owned by the base class call the
virtual method, they will instead be calling the derived method.

#### Explain dynamic dispatch?

In computer science, dynamic dispatch is the process of selecting
which implementation of a polymorphic operation (method or function)
to call at run time. It is commonly employed in, and considered
a prime characteristic of, object-oriented programming (OOP) languages
and systems.

Object-oriented systems model a problem as a set of interacting
objects that enact operations referred to by name. Polymorphism is
the phenomenon wherein somewhat interchangeable objects each expose
an operation of the same name but possibly differing in behavior. As an
example, a File object and a Database object both have a StoreRecord
method that can be used to write a personnel record to storage. Their
implementations differ. A program holds a reference to an object which
may be either a File object or a Database object. Which it is may have
been determined by a run-time setting, and at this stage, the program
may not know or care which. When the program calls StoreRecord on the
object, something needs to decide which behavior gets enacted. If one
thinks of OOP as sending messages to objects, then in this example the
program sends a StoreRecord message to an object of unknown type,
leaving it to the run-time support system to dispatch the message to
the right object. The object enacts whichever behavior it implements.

Dynamic dispatch contrasts with static dispatch, in which the
implementation of a polymorphic operation is selected at compile-time.
The purpose of dynamic dispatch is to support cases where the
appropriate implementation of a polymorphic operation cannot be
determined at compile time because it depends on the runtime type of
one or more actual parameters to the operation.

Dynamic dispatch is different from late binding (also known as dynamic
binding). In the context of selecting an operation, binding associates
a name to an operation. Dispatching chooses an implementation for the
operation after you have decided which operation a name refers to. With
dynamic dispatch, the name may be bound to a polymorphic operation at
compile time, but the implementation not be chosen until run time.
While dynamic dispatch does not imply late binding, late binding does
imply dynamic dispatching since the binding is what determines the set
of available dispatches.

#### Explain late binding?

Late binding, or dynamic binding, is a computer programming mechanism
in which the method being called upon an object or the function being
called with arguments is looked up by name at runtime.

#### Explain lambda function?

Lambda comes from the Lambda Calculus and refers to anonymous
functions in programming.

Why is this cool? It allows you to write quick throw away functions
without naming them. It also provides a nice way to write closures.
With that power you can do things like this.

**Python**

    def adder(x):
        return lambda y: x + y
    add5 = adder(5)
    add5(1)
    6

As you can see from the snippet of Python, the function adder takes in
an argument x, and returns an anonymous function, or lambda, that takes
another argument y. That anonymous function allows you to create
functions from functions. This is a simple example, but it should
convey the power lambdas and closures have.

**Examples in other languages**

**JavaScript**

    var adder = function (x) {
        return function (y) {
            return x + y;
        };
    };
    add5 = adder(5);
    add5(1) == 6

**Haskell**

    (\x y -> x + y)

#### Lambda calculus?

Also written as λ-calculus is a formal system in mathematical logic
for expressing computation based on function abstraction and
application using variable binding and substitution. It is a universal
model of computation that can be used to simulate any single-taped
Turing machine and was first introduced by mathematician Alonzo Church
in the 1930s as part of an investigation into the foundations of
mathematics.

#### Explain pure function?

*Pure* function is a function without side effects; it takes 1..n
parameters and returns a value.

A function may be considered a pure function if both of the following
statements about the function hold:

- The function always evaluates the same result value given the same
argument value(s). The function result value cannot depend on any
hidden information or state that may change while program execution
proceeds or between different executions of the program, nor can it
depend on any external input from I/O devices (usually—see below).

- Evaluation of the result does not cause any semantically observable
side effect or output, such as mutation of mutable objects or output
to I/O devices.

Examples of pure functions

- sin(x), returning the sine of a number x
- length(s), returning the size of a string s

Examples of impure functions

- Any function that uses a non-local variable is potentially impure.
I.e., if there are any free variables in the function definition.
For example inc(x): x + a returns the value of x incremented by the
free variable a, and thus depends on the value of a.

- A function that returns the current day of the week is impure because
at different times it will yield different results—it refers to some
global state. random() is impure because each call potentially yields
a different value. This is because pseudorandom generators use and
update a global "seed" state. If we modify it to take the seed as an
argument, i.e. random(seed); then random becomes pure, because multiple
calls with the same seed value return the same random number.

#### Explain "Inversion of control" and "dependency injection"?

#### Explain quicksort and give some applications?

#### Explain mergesort and give some applications?

#### Give examples of "models of computation"?

In computability theory and computational complexity theory, a model
of computation is the definition of the set of allowable operations
used in computation and their respective costs. It is used for
measuring the complexity of an algorithm in execution time and or memory
space: by assuming a certain model of computation, it is possible to
analyze the computational resources required or to discuss the
limitations of algorithms or computers.

Some examples of models include:

- Turing Machine
- Finite state machines
- Recursive functions
- Lambda calculus
- Combinatory logic
- Cellular automaton
- Abstract rewriting systems

#### How do you make a system scalable?

- "System design and memory limits" - onko sellainen kirja?

#### When it is better to use key-value databases over SQL databases?

#### Which is the best language for numerical calculation?

https://www.quora.com/What-is-the-best-programming-language-for-numerical-analysis

There is not enough information in the question.

Traditionally, the answer would have been Fortran because Fortran is
fast. It puts the fewest obstacles between the programmer and the
machine: like assembly code, but focused on doing mathematical
operations.  It's important to remember that software speed is a
matter of reduction, not some kind of special sauce: when one program
runs faster than another, it is because it is doing fewer things.
All runners run at the same speed, but some of them have more hurdles
in the way. Traditionally, Fortran was fastest because it did the
fewest things.

In the past few decades, more feature-rich languages have caught up to
this limiting speed. When I want to write something at native machine
speed, I use C, and it's probably generating the same minimalist byte
code.  More surprisingly, some very high level languages are also
reaching the plateau (see: How to Make Lisp Go Faster than C). However,
the reasons for this are not magical: these techniques require you to
add hints (e.g. static types) to your high-level language, which is
more or less how Fortran and C do it (e.g. avoiding runtime type-checks),
though the compilers must be considerably more complex to do it.

Since the speed difference is getting ever more marginal, other factors
become important. Most of the recent big data pipelines like Hadoop,
Storm, Spark, as well as higher-level abstractions on them, are
implemented in Java.  Java has almost caught up to the speed of C (factor
of 10 in some of my studies), but the set of tools available makes a big
difference in development time.  It's not too surprising that cluster-wide
data pipelines are Java-based: they draw from experience of web development
to handle high-volume data transfers.

Another nice thing about the Java world is that you get to use new
languages.  I personally like Scala because it completely interoperates
with Java, it has an interactive command-line, it is statically typed
(more on that in a moment), and it encourages a functional style, which
is good for parallelization.

Static typing is controversial: it limits the set of programs that you
can write, arguably in a good way.  I find that it is very helpful for
mathematical programming because it aligns my thoughts about the data
(e.g. "this list must always contain floating point numbers") with the
restrictions that the compiler checks.  The fact that these type annotations
also help to boil the program down into tighter, faster byte code is a
side benefit.

Sometimes, you don't want to write a formal program, you just want to
compute something quickly to guide your intuition or find a counter
example.  A language like Python, Matlab, or R is designed for this need.
These are dynamically typed, interpreted languages, so the basic
constructs, like for-loops, are significantly slower than the equivalent
compiled language, but this is usually not the point. Any reasonably
sized program will finish instantaneously on a human timescale, and for
interactive work, the human timescale is the only relevant one.

However, small programs tend to grow into big ones, so these languages
have some optimizations. Each one has a large library of precompiled
functions, and most of the heavy work is usually done in those libraries.
For Python, this is NumPy and SciPy (external packages), and for Matlab
and R, they are built-in.  I have used NumPy a lot, but I find that I
always have to re-think every algorithm I write to convert it into NumPy
because I always think in terms of operations on rows of an extremely
tall matrix, but NumPy requires you to think in terms of columns.  (That
is, I want to add x_i and y_i then move on to the next i, but NumPy wants
me to add all x to all y at once, then move on to the next operation.)

I am curious about a few new languages, though I haven't tried them myself.
Julia is supposed to combine Python's interactive ease of use with a
sometimes statically typed compiler, compile-time macros from Lisp, and
other best-of-worlds.  I'm also morbidly curious about Haskell, which
takes static typing and functional programming to an extreme.  It limits
the programmer in many ways, but these may be good limitations, lending
themselves to more automatic management of parallelization.

All of the above presume that you're going to be working on a CPU, but
some algorithms can be improved by offloading them on a coprocessor.
There's a lot of interest in GPUs because they take a very different
stance on optimization: they run a huge number of parallel threads at
a modest speed.  FPGAs are interesting, too, because you can burn your
algorithm into a special-purpose circuit, but whereas most computers
have a built-in GPU, FPGAs are special purpose and the software needed
to configure them is complicated.  That said, all of these coprocessors
are better used for algorithms that have more computation than data-moving:
you can lose a significant amount of speed just by copying data from CPU
to coprocessor.

The natural interface to GPUs is through C, using extensions like CUDA
and OpenCL. However, Haskell's Accelerate and CUFP libraries take
advantage of language limitations to rewrite the high-level code as
highly parallelized code.

More [How to make Lisp go faster than C](http://www.iaeng.org/IJCS/issues_v32/issue_4/IJCS_32_4_19.pdf)

#### What is the problem that the use of 'threads' solve? (When do you use threads?)

#### What is NoSQL?

From https://www.mongodb.com/nosql-explained

NoSQL encompasses a wide variety of different database technologies
that were developed in response to the demands presented in building
modern applications:

- Big Data is the driver for NoSQL’s rise, but not the only reason to
use NoSQL

- Developers are working with applications that create massive volumes
of new, rapidly changing data types - structures, semi-structured,
unstructures and polymorphic data.

- Long gone is the twelve-to-eighteen month waterfall development cycle.
Now small teams work in agile sprints, iterating quickly and pushing
code every week or two, some even multiple times a day.

- Applications that once served a finite audience are now delivered as
services that must be always-on, accessible from many different devices
and scaled globally to millions of users.

- Organizations are now turning to scale-out architectures using open
source software, commodity servers and cloud computing instead of large
monolithic servers and storage infrastructure.

- Many NoSQL databases are designed to run well on large clusters, which
makes them more attractive for large data volumes.

Relational databases were not designed to cope with the scale and agility
challenges that face modern applications, nor were they built to take
advantage of the commodity storage and processing power available today.

But often people select NoSQL due to easier database interaction in their
applications.

**NoSQL Database Types**

- **Document databases** pair each key with a complex data structure
known as a document. Documents can contain many different key-value pairs,
or key-array pairs, or even nested documents.

- **Graph stores** are used to store information about networks of data,
such as social connections. Graph stores include Neo4J and Giraph.

- **Key-value stores** are the simplest NoSQL databases. Every single
item in the database is stored as an attribute name (or 'key'), together
with its value. Example of key-value stores are Riak and Berkeley DB.
Some key-value stores, such as Redis, allow each value to have a type
- such as 'integer' - which adds functionality.

- **Wide-column stores** such as Cassandra and HBase are optimized for
queries over large datasets, and store columns data together, instead of
rows.

#### Explain coroutines?

#### Explain monads?

#### Explain continations?

#### Explain combinators?

#### Explain Big-O notation?

https://www.interviewcake.com/article/ruby/big-o-notation-time-and-space-complexity?

#### Problem: Let's say you have a list of N+1 integers between 1 and N. You know there's at least one duplicate, but there might be more. For example, if N=3, your list might be 3, 1, 1, 3 or it might be 1, 3, 2, 2. Print out a number that appears in the list more than once. (That is, in the first example, you can print '1' or '3' -- you don't have to print both.)

Here's an idealized conversation:

**Interviewer**: [states problem]

**Candidate**: Well, I guess the most obvious approach is to compare every number in the list to every
other number until you find a duplicate.

**Interviewer**: That's a good start. What are the space and time complexities of that solution?

**Candidate**: O(n^2) time and O(1) space.

**Interviewer**: Great. Okay, well let's say the list is pretty big, so you need something that's faster than O(n^2).

**Candidate**: Hm, I guess I could iterate through the list and use a hash to keep track of the values
I've seen so far. Once I encounter a number that's already in the hash, I am done.

**Interviewer**: That's a good idea, but does it need to be a hash given that all of the inputs are integers
between 1 and N?

**Candidate**: Ah, I guess I could just use a boolean array and use the integer values as indices.

**Interviewer**: What are the space and time complexities of that solution?

**Candidate**: O(n) time to iterate through the list and O(n) space for the array/hash.

**Interviewer**: Very good. Okay, let's say the list of numbers is quite large, so you'd like to avoid
creating a copy of it. Maybe you have 8GB of RAM, and the list takes up 6GB.

**Candidate**: Well, I could sort the numbers and compare adjacent pairs. That would take O(n*log n) time 
and O(1) space if I use an in-place sort like mergesort.

**Interviewer**: Excellent. Let's throw in one final constraint:
what if you want something faster than O(n^2) and you can't afford
to use a lot of extra space, but you also can't manipulate the original
list. For example, maybe the list is on a read-only CD.

(Almost every candidate needs a hint or two at this point..)

**Candidate**: I think I can binary search for a duplicated number.
For example, I go through the list and count the number of integers
between 1 and N/2. If the count is greater than the number of possible
integers in that range, then I know there's a duplicate in that range.
Otherwise, a duplicate must exist in the range of N/2+1 to N. Once I
know which half of the range the duplicate is in, I can recurse and
binary search in that half, then keep repeating the process until
I've found a duplicated number. The time complexity is O(n*log n)
and the space complexity is O(1).

#### Explain how funktional programming differs from traditional imperative programming?

#### What does IoT mean (for you)?

#### What is the next big thing in information technology?

#### What would you do if you were not a software engineer?

## Front-end

#### What is cross-site request forgery?

## CODING QUESTIONS

**Remove duplicates in a string - in-place**

**Reverse a string - in-place**

**Decide if two strings are anagrams or not**

**Generate all permutations of a given string**

## PRO LEVEL QUESTIONS

- C related questions
- Haskell related questions
- Lisp/Clojure related questions
- Erlang related questions

# Language specific questions

## C#

**Explain the difference between managed and unmanged code?**

Managed code is a code created by the .NET compiler. It does not depend on
the architechture of the target machine because it is executed by the CLR
(Common Language Runtime), and not by the operating system itself. CLR
and managed code offers developers few benefits, like garbage collection,
type checking and exceptions handling.

On the other hand, managed code is directly compiled to native machine code
and depends on the architecture of the target machine. It is executed directly
by the operating system. In the unmanaged code, the developer has to make
sure he is dealing with memory usage and allocation (especially because of
memory leaks), type safety and exceptions manually.

In .NET, Visual Basic and C# compiler creates managed code. To get managed
code, the application has to be written in C or C++ (or other similar languages).


**Explain the diff. between while and for loop? (provide examples)**

Both loops are used when a unit of code needs to be executed repeatedly.
The difference is that the for loop is used when you know how many times
you need to iterate through the code. On the other hand, the while loop is used
when you need repeat something while a given statement is true. Syntax:

    // example of while-loop
    while(condition [is true]) {
        //...do something
    }
    // example of for-loop
    for(unsigned int i = 0; i < 10; i++) {
        //...do something
    }
    // or generally
    for (initializer; condition; iterator) {
        // statements
    }

**Explain the difference between boxing and unboxing? (give examples)**

Boxing is the process of converting a value type to the type object, and unboxing
is extracting the value type from the object. While boxing is implicit, unboxing is
explicit.

    int i = 13;
    object myObject = i;  // boxing
    i = (int)myObject;  // unboxing

**What is the diff. between constants and read-only variables?**

While constants and read-only variables share many similarities, there are some
important differences:

- Constants are evaluated at compile-time, while read-only variables
are evaluated at runtime.

- Constants support only value-type variables, while read-only variables can
hold reference type variables.

- Constants should be used when the value is not changing during runtime,
and read-only variables are used mostly when their actual value is unknown
before the run-time.

**What is LINQ?**

LINQ is an acronym for Language Integrated Query, and was introduced with VS2008.
LINQ is a set of features that extend query capabilities to the .NET language syntax
by adding sets of new standard query operators that allow data manipulation, regardless
of the date source. Supported data sources are

- .NET Framework collections.
- SQL Server databases,
- ADO.NET Datasets,
- XML documents, and
- any collection of objects that support *IEnumerable* or the generic *IEnumerable<T>* interface,
in both C# and Visual Basic.

In short, LINQ bridges the gap between the world of objects and the world of data.

**Explain garbage collection and how it works in. NET?**

Garbage collection is a low-priority process that serves as an automatic mamory
manager which manages the allocation and release of memory for the applications.
Each time a new object is created, the common language runtime allocates memory
for that object from the managed *heap*. As long as free memory space is available
in the managed heap, the runtime continues to allocate space for new objects.

However, memory is not infinite, and once an application fills the heap memory space,
garbage collection comes into play to free some memory. When gc performs *a collection*,
it checks for objects in the managed heap that are no longer being used by the application
and performs necessary operations to reclaim the memory. GC will stop all running 
threads; it will find all objects in the heap that are not being accessed by the main
program and delete them. It will then reorganize all the objects left in the heap to
make space and adjust all the pointers to these objects in both the stack and the heap.

To enforce garbage collection in you code manually, run following command

    System.GC.Collect(); // written in C#

**Explain .NET acronyms: IL, CIL, MSIL, CLI and JIT?**

- IL; Intermediate Language
- CIL; Common Intermediate Language
- MSIL; Microsoft Intermediate Language
- CLI; Common Language Infrastructure
- JIT; Just-In-Time

IL - or Intermediate Language - is a CPU independent partially compiled code. IL code
will be compiled to native machine code using current environmental properties by
Just-In-Time compiler (JIT). JIT compiler translates the IL code to an assembly code
and uses the CPU architecture of the target machine to execute a .NET application.
In .NET, IL is called Common Intermediate Language (CIL), and in the early .NET days,
it was called Microsoft Intermediate Language (MSIL).

CLI, or Common Language Infrastructure, is an open specification developed by Microsoft.
It is a compiled library used for deployment, versioning, and security. In .NET there are two
CLI types; process assemblies (EXE) and library assemblies (DLL). CLI assemblies contains
code in CIL, and as mentioned, during compilation of CLI programming languages, the
source code is translated into CIL code rather than into platform or processor specific
object code.

*To summarize*:

- When compiled, source code is first translated to IL (in .NET - that is CIL, and previously called MSIL)

- CIL is then assembled into bytecode and a CLI assembly is created

- Before code execution, CLI code is passed through the runtime's JIT compiler to generate
native machine code.

- The computer's processor executes the native machine code.

**Explain difference between 'stack' and 'heap'?**

In short; in stack, are stored value types (types inherited from System.ValueType),
and in heap are stored reference types (types inherited from System.Object).

We can say that stack is responsible for keeping track of what is actually executing
and where each executing thread is (each thread has its own stack). The heap is
responsible for keeping track of the data, or more precisely - objects.

**Explain 'inheritance' and why is important?**

Inheritance allows developers to create new classes that reuse, extend and modify
behaviour definined in other classes. This enables code reuse and speeds up development.
With inheritance, developer can write and debug a class only once, and then reuse the same
code as the basis for the new class(es). By default, all classes in .NET are inheritable.

**Explain the differences between an Interface and an Abstract Class in .NET**

An interface merely declares a contract or a behavior that implementing classes should have. It may declare only properties, methods, and events with no access modifiers. All the declared members must be implemented.

An abstract class provides a partial implementation for a functionality and some abstract/virtual members that must be implemented by the inheriting entities. It can declare fields too.

Neither interfaces nor abstract classes can be instantiated.

**Explain deferred execution vs. immediate execution in LINQ. Examples**

In LINQ, deferred execution simply means that the query is not executed at the time it is
specified. Specifically, this is accomplished by assigning the query to a variable. When this is
done, the query definition is stored in the variable but the query is not executed until the query
variable is iterated over. For example:

    DataContext productContext = new DataContext();

    var productQuery = from product in productContext.Products
        where product.Type == "SOAPS"
        select product;   // Query is NOT executed here

    foreach (var product in productQuery)   // Query executes HERE
    {
         Console.WriteLine(product.Name);
    }

You can also force immediate execution of a query. This can be useful, for example,
if the database is being updated frequently, and it is important in the logic of your
program to ensure that the results you’re accessing are those returned at the point in
your code where the query was specified. Immediate execution is often forced using
a method such as Average, Sum, Count, List, ToList, or ToArray. For example:

    DataContext productContext = new DataContext();

    var productCountQuery = (from product in productContext.Products
        where product.Type == "SOAPS"
        select product).Count();   // Query executes HERE

**What is a delegate in .NET?**

A delegate in .NET is similar to a function pointer in C or C++. Using a delegate
allows the programmer to encapsulate a reference to a method inside a delegate
object. The delegate object can then be passed to code which can call the referenced
method, without having to know at compile time which method will be invoked.
In addition, we could use delegate to create custom event within a class.
For example,

    public delegate void FooDelegate();

    class FooClass
    {
        // custom event
        public event FooDelegate FooEvent;
    }

    FooClass FooObj = new FooClass()
    FooObj.FooEvent += new FooDelegate();

**What is the output of the program below? Explain!**

    delegate void Printer();

    static void Main()
    {
        List printers = new List();
        for (int i = 0; i < 10; i++)
        {
             printers.Add(delegate { Console.WriteLine(i); });
        }

        foreach (var printer in printers)
        {
             printer();
        }
    }

**Answer**

This program will output the number 10 ten times.

Here’s why: The delegate is added in the for loop and “reference”
(or perhaps “pointer” would be a better choice of words) to i is stored,
rather than the value itself. Therefore, after we exit the loop, the variable
i has been set to 10, so by the time each delegate is invoked, the value
passed to all of them is 10.

**What is the output of the program below? Explain!**

    class Program {
        private static string result;
 
        static void Main() {
            SaySomething();
            Console.WriteLine(result);
        }
 
        static async Task<string> SaySomething() {
            await Task.Delay(5);
            result = "Hello world!";
            return “Something”;
        }
    }

Also, would the answer change if we were to replace

    await Task.Delay(5);

with 

    Thread.Sleep(5);
    
Why or why not?

**Answer**

The answer to the first part of the question (the version of the code with

    await Task.Delay(5);) 

is that the program will just output a blank line (not “Hello world!”).
This is because result will still be uninitialized when Console.WriteLine is called.

Most procedural and object-oriented programmers expect a function to
execute from beginning to end, or to a return statement, before returning
to the calling function. This is not the case with C# async functions. They
only execute up until the first await statement, then return to the caller.
The function called by await (in this case Task.Delay) is executed asynchronously,
and the line after the await statement isn’t signaled to execute until Task.Delay
completes (in 5 milliseconds). However, within that time, control has already
returned to the caller, which executes the Console.WriteLine statement on
a string that hasn’t yet been initialized.

Calling await Task.Delay(5) lets the current thread continue what it is doing,
and if it’s done (pending any awaits), returns it to the thread pool. This is the
primary benefit of the async/await mechanism. It allows the CLR to service
more requests with less threads in the thread pool.

Asynchronous programming has become a lot more common, with the prevalence
of devices which perform over-the-network service requests or database requests
for many activities. C# has some excellent programming constructs which greatly
ease the task of programming asynchronous methods, and a programmer who is
aware of them will produce better programs.

With regard to the second part of the question, if await Task.Delay(5); was replaced
with Thread.Sleep(5), the program would output *Hello world!*. An async method
without at least one await statement in it operates just like a synchronous method;
that is, it will execute from beginning to end, or until it encounters a return statement.
Calling Thread.Sleep() simply blocks the currently running thread, so the
Thread.Sleep(5) call just adds 5 milliseconds to the execution time of the
SaySomething() method.


**Given an instance 'circle' of the following class**

    public sealed class Circle {
        private double radius;
  
        public double Calculate(Func<double, double> op) {
            return op(radius);
        }
    }

write code to calculate the circumference of the circle, without modifying the Circle class itself.

**Answer**

The preferred answer would be of the form:

    circle.Calculate(r => 2 * Math.PI * r);

Since we don’t have access to the private radius field of the object, we tell
the object itself to calculate the circumference, by passing it the calculation
function inline.

A lot of C# programmers shy away from (or don’t understand) function-valued
parameters. While in this case the example is a little contrived, the purpose is
to see if the applicant understands how to formulate a call to Calculate which
matches the method’s definition.

Alternatively, a valid (though less elegant) solution would be to retrieve the
radius value itself from the object and then perform the calculation with the
result:

    var radius = circle.Calculate(r => r);
    var circumference = 2 * Math.PI * radius;

Either way works. The main thing we’re looking for here is to see that the
candidate is familiar with, and understands how to invoke, the Calculate
method.

**What is the output of the short program below? Explain!**

    class Program {
        static String location;
        static DateTime time;
 
        static void Main() {
            Console.WriteLine(location == null ? "location is null" : location);
            Console.WriteLine(time == null ? "time is null" : time.ToString());
        }
    }

**Answer**

The output will be:

    location is null
    1/1/0001 12:00:00 AM

Although both variables are uninitialized, String is a reference type and
DateTime is a value type. As a value type, an unitialized DateTime variable
is set to a default value of midnight of 1/1/1 (yup, that’s the year 1 A.D.),
not null.

**Given an array of ints, write a C# method to total all the values that are even numbers**

There are of course many ways to do this, but two of the most straightforward would be either:

    static long TotalAllEvenNumbers(int[] intArray) {
        return intArray.Where(i => i % 2 == 0).Sum(i => (long)i);
    }

or

    static long TotalAllEvenNumbers(int[] intArray) {
        return (from i in intArray where i % 2 == 0 select (long)i).Sum();
    }

Here are the key things to look for in the answer:

- Does the candidate take advantage of the C# language constructs which
make a one-liner solution possible (i.e., rather than employing a more lengthy
solution which contains a loop, conditional statement, and accumulator)?

- Does the candidate consider the possibility of overflow. For example,
an implementation such as 

        return intArray.Where(i => i % 2 == 0).Sum();
    (regardless of the return type of the function) might be an “obvious” one-line
solution, but the probability of overflow here is high. While the approach used in
the answers above of converting to long doesn’t eliminate the possibility, it
makes it a highly unlikely that an overflow exception will occur. Note that, if the
candidate asks about the expected size of the array and the magnitude of its
members, he or she is obviously considering this overflow issue, which is part of
what we’re looking to ascertain.

## C++

**Write code to check if two words are anagrams**

Good code, employing STL functions etc.

**Write a class that calculates factorials**

Good code, caching previous results, testing for boundary conditions etc.

**Tell me about the keyword ‘virtual’**

    Knowledge virtual functions, virtual inheritance etc. Ability to talk confidently about virtual function tables etc.

**I have a program which is the world’s best rock, paper, scissors player. From the ground up - how would you go about testing it?**

Solid understanding of organised testing procedures from frameworks all the
way up to test cases calculating how good the program actually is at the game
(can it beat random input, can it beat someone just picking rock all of the time etc.). 
There are no right answers as such, I just want to know how they think.**

**Tell me about a complicated project you have worked on**

A complicated project. I want to know what they did, why they did it, how it worked,
what they learned, how they were involved outside of technical aspects etc. I will be
listening very keenly and will be asking detailed questions.

**What will the line of code below print and why?**

    cout << 25u - 50;

**Answer**

The answer is not '-25'. Rather, the answer is 4294967271 (assuming 32 bit integers).

In C++, if the types of two operands differ from one another, then the operand with
"lower type" will be promoted to the type of the "higher type" operand, using the
following type hierarchy (listed from highest to lowest):

    long double
    double
    float
    unsigned long int
    long int
    unsigned int
    int (lowest)

So, when two operands are 25u (unsigned int) and 50 (int), the 50 is promoted to
unsigned integer, i.e 50u. The result of the operation will be of the type of the operands.
Therefore, result will be unsigned integer as well. So the result -25 converts to 4294967271
when promoted to unsigned integer.

**What is "diamond problem" that can occur with multiple inheritance?**

Example: university has people who are affiliated with it. Some are students, some are
faculty members, some are administrators, and so on. Some simple inheritance scheme
might have different types of people in different roles, all of whom inherit from one common
*Person* class. The *Person* class could define an abstract *getRole()* method which would
be overridden by its sub-classes to return correct role.

What happens if we want to model a role of the *teaching assistant*? Typically, TA is both
a *grad student* and a *faculty member*. This yields the classic diamond problem of
multiple inheritance and the resulting ambiguity regarding the TA's *getRole()* method.


                  | Person                         |
                  | public abstract Role getRole() |
                  |                                |
                             /      \

    | Faculty Member           |  | Graduate Student           |
    | public Role getRole() {} |  | public Role getRole() {    |
    |   return Role.Faculty;   |  |   return Role.GradStudent; |
    | }                        |  | }                          |
                             \       /

                    | Teaching Assistant    |
                    | public Role getRole() |
                    | { return ??? }        |

Which *getRole()* impl. should the TA inherit? Simple answer might be to have the TA
class override the *getRole()* method and return newly defined role called *TA*. But
that answer is also imperfect as it would hide the fact that a TA is, in fact, both faculty
member and grad student.

**What is the error in the code below and how to correct?**

    my_struct_t *bar;
    /*...do stuff, incl. setting 'bar' to point to a defined my_struct_t object
    memset(bar, 0, sizeof(bar));

**Answer**

The last argument of memset should be sizeof(*bar), not sizeof(bar); sizeof(bar) calculates
the size of *bar* (the pointer *itself*) rather than the size of the structure pointed to by *bar*.

Code can be corrected by using

    sizeof(*bar)

as the last argument in the call to memset.

Note: *bar will cause dereferencing error if bar has not been assigned. Even safer solution
would be to use

     sizeof(my_struct_t).

However, using *bar is safe withing the call to sizeof, even if bar has not been initialized yet,
since sizeof is a compile time construct.

**What will i and j equal to after the code is executed?**

    int i = 5:
    int j = i++;

**Answer**



## Ruby

**What will val1 and val2 equal after the code below is executed? Explain your answer.**

    val1 = true and false  # hint: output of this statement in IRB is NOT value of val1!
    val2 = true && false

**Answer**

    '&&' operator has higher precedence than 'and' operator.
    This means that expression
    'val1 = true and false' is the same as '(val1 = true) and false', while
    'val2 = true && false' is the same as 'val2 = (true && false)'.

This is, incidentally, a great example of why using parentheses to clearly specify your intent is generally a good practice, in any language.
    
    Ruby style guide: use '&&', '||' for boolean expressions; use 'and', 'or' for control flow.
    
    // Returns value of evaluated expression!

    // Testing with different Ruby versions
    esa@firefly:~$ irb
    1.8.7-p376 :001 > RUBY_VERSION
    => "1.8.7"
    1.8.7-head :001 > val1 = true and false
     => false
    1.8.7-head :002 > val2 = true && false
     => false
    1.8.7-head :003 > val1
     => true
    1.8.7-head :004 > val2
     => false

    1.9.2-p330 :001 > val1 = true and false
     => false
    1.9.2-p330 :002 > val2 = true && false
     => false
    1.9.2-p330 :003 > val1
     => true
    1.9.2-p330 :004 > val2
     => false

    2.3.0 :001 > val1 = true and false
     => false
    2.3.0 :002 > val2 = true && false
     => false
    2.3.0 :003 > val1
     => true
    2.3.0 :004 > val2
     => false

**Which of the expressions listed below will result in "false"?**

    true    ? "true" : "false"
    false   ? "true" : "false"
    nil     ? "true" : "false"
    1       ? "true" : "false"
    0       ? "true" : "false"
    "false" ? "true" : "false"
    ""      ? "true" : "false"
    []      ? "true" : "false"

**Answer**

In Ruby, the only values that evaluate to false are 'false' and 'nil'.
Everything else – even zero (0) and an empty array ([]) – evaluates to true.
This comes as a real surprise to programmers who have previously been
working in other languages like JavaScript.

**Write a function that sorts the keys in a hash by the length of the key as a string?**

    # For instance, the hash:
    # { abc: 'hello', 'another_key' => 123, 4567 => 'third' }
    # should result in:
    # ["abc", "4567", "another_key"]

**Answer**

    def sort_by_keys(hsh = {})
      arr = hsh.sort_by { |k, v| "#{k}".size }
      # sort_by produces array of arrays; if we want to return original hash, then
      Hash[*arr.flatten] # return original hash
    end
    
    hsh = { abc: 'hello', 'another_key' => 123, 4567 => 'third' }
    sort_by_keys(hsh).keys
    => ["abc", "4567", "another_key"]

    # For large data sets, it might be better to use #each_slice (or atleast benchmark).

The most straightforward answer would be of the form: (returns keys in order)

    hsh.keys.map(&:to_s).sort_by(&:length)
    # or
    hsh.keys.collect(&:to_s).sort_by { |key| key.length }

**What is 'splat' operator in Ruby?**

There are quite a few examples where "splat" is used. For example in method definitions:

    def shout_out(message, *friends)
      friends.each { |f| puts "#{f}: #{message}"}
    end
    
    shout_out("Hi!", "Bob, "Steve", "Dave")
    
    # results
    Bob: Hi!
    Steve: Hi!
    Dave: Hi!
     => ["Bob", "Steve", "Dave"]

This is probably the most common usage of the splat operator - slurping
up all remaining arguments. (Yes, *slupring* - it's a technical term).
C# developers will probably recognize a similarity to the **params**
keyword in .NET.

Another example

    def shout_out(message, *friends, signoff)
      friends.each { |f| puts "#{f}: #{message}"}
      puts signoff
    end

    shout_out("Hi!", "Bob", "Steve", "Dave", "I'll see you later")
    # results
    Bob: Hi!
    Steve: Hi!
    Dave: Hi!
    I'll see you later
     => nil

Using splat in multiple variable assignment

    letters = ["a", "b", "c", "d", "e"]
    first, second = letters
    puts "#{first}, #{second}"
    a, b
     => nil
    
    first, *second = letters
    puts "#{first}, #{second}"
    a, ["b", "c", "d", "e"]
     => nil

Using splat to flatten arrays

    numbers = [1, 2, 3]
    more = [*numbers, 4, 5]
    p more
    [1, 2, 3, 4, 5]
     => [1, 2, 3, 4, 5]

Using splat for array coercion

    numbers = *1..10
    p numbers
    [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
     => [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

**What is 'double splat' operator in Ruby?**

It captures all keyword arguments.
Ruby 2.0 introduced keyword arguments, and '**' acts like '*', but for keyword arguments;
it returns a hash with key-value-pairs. Example

     def foo(a, *b, **c)
       [a, b, c]
     end

    foo 10
    => [10, [], {}]
    
    foo 10, 20 ,30
    => [10, [20, 30], {}]
    
    foo 10, 20, 30, d: 40, e: 50
    => [10, [20, 40, { :d=>40, :e=>50}]]


**Explain how #inject works?**

"inject" is a part of Ruby's enumerable module which provides collection
classes with several traversal and searching methods, and with the
ability to sort.

    inject(initial, sym) → obj
    inject(sym) → obj
    inject(initial) { |memo, obj| block } → obj
    inject { |memo, obj| block } → obj

Combines all elements of enum by applying a binary operation, specified
by a block or a symbol that names a method or operator.

If you specify a block, then for each element in enum the block is passed
an accumulator value (memo) and the element. If you specify a symbol
instead, then each element in the collection will be passed to the named
method of memo. In either case, the result becomes the new value for memo.
At the end of the iteration, the final value of memo is the return value
for the method.

If you do not explicitly specify an initial value for memo, then the first
element of collection is used as the initial value of memo.

**Explain proc, block and lambda?**

**Explain Ruby 'mixins'?**

A *mixin* can basically be thought of as a set f code that can be
added to one or more classes to add additional capabilities without
using inheritance. In Ruby, a mixin is code wrapped up in a module
that a class can include or extend. In fact, a single class can have
many mixins.

One area where mixins could be used is for logging. In Rails
application, each model can have access to a logger without having
global constant of some sort.

(Think - Ruby only supports single inheritance.)

**Include vs Extend?**

**Consider following two methods**

    def times_two(arg1);
      puts arg1 * 2;
    end

    def sum(arg1, arg2);
      puts arg1 + arg2;
    end

    What will be the result of each of the following lines of code:

    times_two 5
    times_two(5)
    times_two (5)
    sum 1, 2
    sum(1, 2)
    sum (1, 2)

**Answer**

First three lines will print out 10, as expected.
Next two lines will print out 3, as expected.
Last line will result in syntax error; the problem is the space between
the method name and the open parenthesis. Because of the space, the
Ruby parser things that (1, 2) is an expression that represents a
single argument, but (1, 2) is not a valid Ruby expression, hence the
error.

Note that the problem does not occur with single argument methods
(as shown with our timesTwo method above), since the single value is
a valid expression (e.g., (5) is a valid expression which simply
evaluates to 5).

**Consider following code**

    VAL = 'Global'
    
    module Foo
      VAL = 'Foo Local'
      
      class Bar
        def value1
          VAL
        end
      end
    end
    
    class Foo::Bar
      def value2
        VAL
      end
    end

    # What will be the value of each of the following? (Explain why!)
    Foo::Bar.new.value1
    Foo::Bar.new.value2

**Answer**

    2.3.0 :121 > Foo::Bar.new.value1
     => "Foo Local"
    2.3.0 :122 > Foo::Bar.new.value2
     => "Global"

Here's why:

The *module* keyword (as well as the *class* and *def* keywords) will
create a new lexical scope for all of its contents. The above module
*Foo* therefore creates the scope *Foo* in which the VAL constant equal
to 'Foo Local' is defined. Inside *Foo*, we declare class *Bar*, which
creates another new lexical scope (name Foo::Bar), which also has access
to its parent scope (i.e. Foo) and all of its constants.

However, when we then declare Foo::Bar, we are actually creating yet
*another* lexical scope, which is also named Foo::Bar. However, this
new lexical scope has no parent (i.e. it is entirely independent of
the lexical scope Foo created earlier) and therefore does not have any
access to the contents of the 'Foo' scope. Therefore, inside class
Foo::Bar, we only have access to the VAL constant declared at the
beginning of the script (i.e. outside of any module) with the value
'Global'.

**Is the line below valid Ruby code? If yes, what does it do?**

    -> (a) {p a}["Hello world"]

**Answer**

Yes, this is valid Ruby. We are creating a lambda (a new Proc) using
'Dash Rocket' (aka. stabby lambda), to which we pass a block '{ p a }'.
All lambdas are Procs, but not all Procs are lambdas. This particular
Proc takes one parameter. When Proc is called, Ruby executes the block
'p a'. This line of code prints "Hello world".

You can call a Proc by using either the call method on Proc, or by
using the square bracket syntax; so this line of code also invokes the
Proc and passes it the string "Hello World".

'p a' is equivalent of puts a.inspect.

**What is the difference between calling super and calling super()?**

**Answer**

A call to *super* invokes the parent method with the same arguments
that were passed to the child method. An error will therefore occur if
the arguments passed to the child method do not match what the parent
is expecting.

A call to *super()* invokes the parent method without any arguments,
as presumably expected. As always, being explicit in your code is
a good thing.

**Explain each of the following operators and how should be used?**

    ==, ===, eql?, equal?

**Answer**

    ==
    # Checks if the value of two operands are equal
    # (often overridden to provide class-specific definition of equality)
    
    ===
    # Specifically used to test equality within the when clause of
    # a case statement (also often overridden to provide meaningful
    # class-specific semantics in case statements)
    
    eql?
    # Checks if the value and the type of the two operands are the
    # same (as opposed to the == operator which compares values but
    # ignores types). For example, 1 == 1.0 equals to truem but
    # 1.eql?(1.0) evaluates to false.
    
    equal?
    # Compares the identity of two objects; i.e. returns true if both
    # operands have the same object id (i.e, if they both refer to the
    # same object). Note! This will return false when comparing two
    # identical copies of the same object.

**Explain difference in following ruby code?**

    x = "Hello"
    x += " world"       # a)
    x.concat " world"?  # b)

**Answer**

The '+=' operator re-initializes the variable with a new value,
so 'a += b' is equivalent to 'a = a +b'. Therefore, while it may seem
that += is mutating the value, it's actually creating a new object and
pointing the old variable to that new object.

This is perhaps easier to understand if written as follows:

    foo = "foo"
    foo2 = foo
    foo.concat "bar"
    
    puts foo
    => "foobar"
    puts bar
    => "foobar"
    
    foo += "baz"
    puts foo
    => "foobarbaz"
    puts foo2
    => "foobar"

Examining the *object_id* of *foo* and *foo2* will also demonstrate
that new objects are being created. The difference has implications
for performance.

**Explain array.map(&:method) as a shorthand of array.map { |v| v.method }. How exactly does it work?**

**Answer**

When parameter is passed with & in front of it (indicating that it is
to be used as a block) Ruby will call to_proc on it in an attempt to
make it usable as a block. Symbol#to_proc quite handily returns a Proc
that will invoke the method of the corresponding name on whatever is
passed to it, thus enabling this trick to work.

**Write a single line (of Ruby) that prints the Fibonacci sequence of any length as an array**

**Answer**

Fibonacci series is defined recursively as follows

    F(n) =
    0, when n = 0
    1, when n = 1
    F(n-1) + F(n-2), when n > 1

In other words, to get current *n*, you sum two previous numbers 'n-1' and 'n-2' to get *n*.

    # as a recursive method, to get any fibonacci number
    def fibo(n)
      return 0 if n == 0
      return 1 if n == 1
      return fibo(n-1) + fibo(n-2)
    end

    # as a one-liner, to get a sequence until n
    (1..20).inject( [0, 1] ) { |fib| fib << fib.last(2).inject(:+) }
    => [1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, 610, 987, 1597, 2584, 4181, 6765, 10946, 17711, 28657]

## Embedded Systems

**must have** skills/knowledge:

- A good understanding of digital and small signal analog electronics.
- Ability to read and understand schematics.
- Ability to effectively use a Volt/Ohm meter and an Oscilloscope.
- Ability to perform at least basic electronics debugging/troubleshooting.
- Competency in at least one assembly language.
- Competency in the ‘C’ programming language.
- A good understanding of microprocessor internals (mostly the registers).
- An understanding of memory regions, and their uses (heap, stack, IVT, code).
- Working with hexadecimal numbers and hexadecimal math.
- A very good understanding of boolean math (logic).
- An excellent knowledge of what interrupts are and how they work in code.
- An understanding of the different kinds of memory (RAM, ROM, Flash),
the differences between them and how they are read, written, accessed.
- An understanding of multi-tasking (in the embedded world we use the
original term “multi-tasking”. The term “multi-threaded” was a term somebody
made up later to mean the exact same thing. What others call “threads” we
have called “tasks” since the 1970s).
- Ability to use a debugger to perform at least simple operations such as setting
breakpoints, single stepping, examining variable values, examining memory,
examining registers - and understanding the when to enable and disable interrupts
when single stepping using a debugger.
- Ability to debug multi-tasking code.
- The ability to read and understand datasheets, and produce driver code for
a given device based on the information contained in its datasheet.
- Understanding the advantages & disadvantages of using a foreground
loop with interrupts vs. using a multi-tasking kernel.
- Developing code to run under an RTOS (Real Time Operating System),
and how to use semaphores, mutexes, queues, inter-task communications.
- How to develop and debug code for peripherals such as UARTs, A/D & D/A
converters, timers, PWM generation from a timer, real-time clocks, etc.
- How to develop and debug code for communications using RS-232
(and it’s variants), SPI, I2C, and parallel data ports.
- How to develop and debug code with stacks, queues, linked-lists, and
other common data constructs.
- A good understanding of DMA (Direct Memory Access), and how to
implement it for systems which have DMA capability.
- C, C++, Data Structures, Basic Concepts of OS, Multi-threading.
- 8085, 80x86, ARM7 TDMIS based MCU, ARM Cortex-M3.
- RTOS like Vxworks, WindRiver, Ucos II, ThreadX, QNX Neutrino.
- Basics of Linux Kernel.
- Device Driver fundamentals and basics.
- patience - the design never works. It takes hell a lot of time and retries to solve the bugs.
- COMMON SENSE

**What is dirac delta function and its Fourier transform and its importance? DMA deals with which address (physical/virtual addresses)?**

**Why do we need a infinite loop in embedded systems development?**

**What are the different ways by which you can code in a infinite loop?**

**Is it necessary to start the execution of a program from the main() in C?**

**Explain what are the different storage classes in C?**

**What is watchdog timer?**

**What are little endian and big endian types of storage? How can you identify which type of allocation a system follows?**

**Scope of static variables?**

**What is the size of the int, char and float data types?**

**What is the difference between a ‘thread’ and a ‘process’?**

**Explain why arrays cannot be passed by values to functions?**

**What is interrupt latency?**

**What type of registers ARM/INTEL chip contains**

**Can structures be passed to the functions by value?**

**How to define a structure with bit field members?**

**What is an anti-aliasing filter? Why is it required?**

**Advantages and disadvantagesof using macro and inline functions?**

**Explain scope of static variables in C?**

**Explain what are the different qualifiers in C?**

**What are hard and soft real-time systems?**

**How is function itoa() written in C**

**What is difference between micro processor and micro controller?**

**Explain order of constructor and destructor call in case of multiple inheritance?**

**Explain what will this return malloc(sizeof(-10))?**

**What is interrupt latency?**

**What is a semaphore? Give examples of different types of semaphores?**

**Can structures be passed to the functions by value? Explain!**

**What is 8085 ? An embedded system?**

**What are the advantages and disadvantages of using macro and inline functions?**

**Explain different types of inheritance relationship?**

**What is ISR? Can they be passed any parameter and can they return a value?**

**What typecast is applied when we have a signed and an unsigned int in an expression?**

**What is the order of calling for the constructors and destructors in case of objects of inherited classes?**

**What is the output of following code?**

    a=7; b=8; x=a++-b; printf(“%d”, x );

**What is the role of segment register?**

**What is pass by value and pass by reference?**

**How would you pass a structure as a call to function?**

**What does 'malloc' do?**

**What will happen if we have a statement like malloc(sizeof(0));**

**What is concurrency?**

**Explain (with example) deadlock and starvation**

**Can we have 'constant' 'volatile' variable?**

**Explain virtual memory and how it works?**

**What is a memory leak?**

**What is a segmentation fault?**

**How would you debug segmentation faults?**

**What do you need to consider when writing interrupt handlers (ISR)?**

**When do we use 'const' qualifier?**

**For what is 'volatile' keyword used for?**

**What is difference between using macro and in-line function?**

**Explain difference between object-oriented and object-based languages?**

**Can we use semaphore or mutex or spin lock in interrupt context in linux kernel?**

**What is meant by a forward reference in C?**

**How are variables mapped across to the various memories by the C compiler?**

**How to implement a fourth order Butterworth LP filter at 1kHz if sampling frequency is 8kHz?**

**What is the scope of a function that is declared as 'static'?**

### Embedded C interview Questions for Embedded Systems Engineers

**Which is the best way to write Loops?**

**Q: Is Count down-to-zero loop better than count-up loop?**

Always, count down-to-zero loops are better.This is because, at loop
termination, comparison to zero can be optimized by complier. (e.g.
using SUBS) Else, At the end of the loop there is ADD and CMP.

**What is loop un-rolling?**

Small loops can be unrolled for higher performance, with the
disadvantage of increased code size. When a loop is unrolled, a loop
counter needs to be updated less often and fewer branches are executed.
If the loop iterates only a few times, it can be fully unrolled, so
that the loop overhead completely disappears. For example:

    int countbit1(uint n)
    {
      int bits = 0;
      while (n != 0)
      {
        if (n & 1)
        bits++;n &gt;&gt;= 1;
	  }
      return bits;
    }
    int countbit2(uint n)
	{
	  int bits = 0;
	  while (n != 0) {
	    if (n & 1) bits++;
	    if (n & 2) bits++;
	    if (n & 4) bits++;
	    if (n & 8) bits++;
	    n &gt;&gt;= 4;
	  }
	  return bits;
    }

**How does, taking the address of local variable result in unoptimized code?**

The most powerful optimization for compiler is register allocation.
That is, it operates the variable from register, than memory.
Generally, local variables are allocated in registers. However if we
take the address of a local variable, compiler will not allocate the
variable to register.

**How does global variable result in unoptimized code?**

For the same reason as above, compiler will never put the global
variable into register. So it is bad.

**So how to overcome this problem?**

When it is necessary to take the address of variables, (for example
if they are passed as a reference parameter to a function). Make a copy
of the variable, and pass the address of that copy.

**Which is better a char, short or int type for optimization?**

Where possible, it is best to avoid using char and short as local
variables. For the types char and short the compiler needs to reduce
the size of the local variable to 8 or 16 bits after each assignment.
This is called sign-extending for signed variables and zero extending
for unsigned variables. It is implemented by shifting the register
left by 24 or 16 bits, followed by a signed or unsigned shift right
by the same amount, taking twoinstructions (zero-extension of
an unsigned char takes one instruction).These shifts can be avoided by
using int and unsigned int for local variables. Thisis particularly
important for calculations which first load data into local variables
and thenprocess the data inside the local variables. Even if data is
input and output as 8- or 16-bit quantities, it is worth considering
processing them as 32-bit quantities.

**How to reduce function call overhead in ARM based systems?**

- Try to ensure that small functions take four or fewer arguments.
These will not use the stack for argument passing. It will copied into
registers.

- If a function needs more than four arguments, try to ensure that it
does asignificant amount of work, so that the cost of passing the
stacked arguments is out weighed.

- Pass pointers to structures instead of passing the structure itself.

- Put related arguments in a structure, and pass a pointer to the
structure tofunctions. This will reduce the number of parameters and
increase readability.

- Minimize the number of long long parameters, as these take two
argument words.This also applies to doubles if software
floating-point is enabled.

- Avoid functions with a parameter that is passed partially in a
register and partiallyon the stack (split-argument). This is not
handled efficiently by the currentcompilers: all register arguments
are pushed on the stack.· Avoid functions with a variable number of
parameters. (Varargs functions)

**What is a pure function in ARM terminology?**

Pure functions are those which return a result which depends only
on their arguments.They can be thought of as mathematical functions:
they always return the same result ifthe arguments are the same.
To tell the compiler that a function is pure, use the special
declaration keyword __pure. __pure int square(int x){ return x * x;}
Compiler does optimization for pure functions. For example, the values
which areallocated tomemory can be safely cached in registers, instead
of being written to memory before a calland reloaded afterwards.

**What are inline functions?**

The ARM compilers support inline functions with the keyword

    __inline

This results in each call to an inline function being substituted by
its body, instead of a normal call. This results in faster code, but
it adversely affects code size, particularly if the inline function is
large and used often.

## JavaScript

**Do you know any of the following libraries? What do they do?**

- React
- Node.js
- Bootstrap
-...

## Databases

**What is database normalization/denormalization?**

## Interview @ Cdmt :: 31.10.2016 :: Brief technical "teaser" test

**1. What does following JavaScript produce?**

    i = 1; i *= ++i; i = i << 1;

**Answer**

    i = 1;
    => 1
    i *= ++i;
    => 2
    i = i << 1;
    => 4

**2. Write line below using only '&&' and '!'**

    A || !B

    // Use De Morgan's rules to solve this
    // A && B = !(!A || !B) = !(!A ∪ !B)
    // A || B = !(!A && B) = !(!A ∩ !B), where
    // A and B are sets,
    // !A is the complement of A
    // ∩ is the intersection, and
    // ∪ is the union.
    
    // Now, 'A || !B' becomes
    => !(!A && !!B)
    => !(!A && B)

**3. What is a deadlock?**

A deadlock is a state in which each member of a group of actions, is
waiting for some other member to release a lock. Deadlock is a common
problem in multiprocessing systems, parallel computing, and distributed
systems, where software and hardware locks are used to handle shared
resources and implement process synchronization.

In an operating system, a deadlock occurs when a process or thread
enters a waiting state because a requested system resource is held by
another waiting process, which in turn is waiting for another resource
held by another waiting process. If a process is unable to change its
state indefinitely because the resources requested by it are being used
by another waiting process, then the system is said to be in a deadlock.

**4. What is cross-site request forgery (and how to prevent it)?**

XSRF, is a type of malicious exploit of a website where unauthorized
commands are transmitted from a user that the website trusts. Unlike
cross-site scripting (XSS), which exploits the trust a user has for
a particular site, CSRF exploits the trust that a site has in a
user's browser.

Example:

The Netflix website in 2006 had numerous vulnerabilities to CSRF,
which could have allowed an attacker to perform actions such as adding
a DVD to the victim's rental queue, changing the shipping address on
the account, or altering the victim's login credentials to fully
compromise the account.

**5. What is the difference between following operations in JavaScript and which one should you use?**

    '==' vs '==='
    
**Answer**

The identity 

    ===

operator behaves identically to the equality 

    ==
operator except no type conversion is done, and the types must be the same to be
considered equal.

**Reference: Javascript Tutorial: Comparison Operators**

    == 

operator will compare for equality after doing any necessary type conversions.
    
    ===

operator will not do the conversion, so if two values are not the same type ===
will simply return false. Both are equally quick.

**To quote Douglas Crockford's excellent JavaScript: The Good Parts,**

JavaScript has two sets of equality operators:

    === and !==, and their evil twins == and !=.

The good ones work the way you would expect. If the two operands are of the same type
and have the same value, then 

    ===

produces true and 

    !==

produces false. The evil twins do the right thing when the operands are of
the same type, but if they are of different types, they attempt to coerce the
values. the rules by which they do that are complicated and unmemorable.
These are some of the interesting cases:

    '' == '0'           // false
    0 == ''             // true
    0 == '0'            // true

    false == 'false'    // false
    false == '0'        // true

    false == undefined  // false
    false == null       // false
    null == undefined   // true

    ' \t\r\n ' == 0     // true

The lack of transitivity is alarming. My advice is to never use the evil twins.
Instead, always use

    === and !==.

All of the comparisons just shown produce false with the === operator.

**6. Minimize SQL:  SELECT user.id FROM users ... WHERE ...**

**7. What does browsers side caching option "no-cache" do?**

**8. Which HTML5+JS tech. would you use to implement offline client app. with good UX?**

**9. Explain HMAC?**

A message authentication code (MAC) is produced from a message and
a secret key by a MAC algorithm. An important property of a MAC is that
it is impossible¹ to produce the MAC of a message and a secret key
without knowing the secret key. A MAC of the same message produced by
a different key looks unrelated. Even knowing the MAC of other messages
does not help in computing the MAC of a new message.

An HMAC is a MAC which is based on a hash function. The basic idea is
to concatenate the key and the message, and hash them together. Since
it is impossible, given a cryptographic hash, to find out what it is
the hash of, knowing the hash (or even a collection of such hashes)
does not make it possible to find the key. The basic idea doesn't quite
work out, in part because of length extension attacks, so the actual
HMAC construction is a little more complicated. For more information,
browse the hmac tag on Cryptography Stack Exchange, especially Why is
H(k||x) not a secure MAC construction?, Is H(k||length||x) a secure MAC
construction? and HMAC vs MAC functions. There are other ways to define
a MAC, for example MAC algorithms based on block ciphers such as CMAC.

A MAC authenticates a message. If Alice sees a message and a MAC and
knows the associated secret key, she can verify that the MAC was produced
by a principal that knows the key by doing the MAC computation herself.
Therefore, if a message comes with a correct MAC attached, it means this
message was seen by a holder of the secret key at some point. A MAC is
a signature based on a secret key, providing similar assurances to a
signature scheme based on public-key cryptography such as RSA-based
schemes where the signature must have been produced by a principal in
possession of the private key.

For example, suppose Alice keeps her secret key to herself and only ever
uses it to compute MACs of messages that she stores on a cloud server
or other unreliable storage media. If she later reads back a message
and sees a correct MAC attached to it, she knows that this is one of
the messages that she stored in the past.

An HMAC by itself does not provide message integrity. It can be one of
the components in a protocol that provides integrity. For example,
suppose that Alice stores successive versions of multiple files on an
unreliable media, together with their MACs. (Again we assume that only
Alice knows the secret key.) If she reads back a file with a correct MAC,
she knows that what she read back is some previous version of some file
she stored. An attacker in control of the storage media could still
return older versions of the file, or a different file. One possible
way to provide storage integrity in this scenario would be to include
the file name and a version number as part of the data whose MAC is
computed; Alice would need to remember the latest version number of each
file so as to verify that she is not given stale data. Another way to
ensure integrity would be for Alice to remember the MAC of each file
(but then a hash would do just as well in this particular scenario).

¹ “Impossible” as in requiring far more computing power than
realistically possible.

**10. Explain dependency injection?**

**11. What is cross-site scripting (in JavaScript)?**

Cross-site scripting (XSS) is a type of computer security vulnerability
typically found in web applications. XSS enables attackers to inject
client-side scripts into web pages viewed by other users.

**12. What is a pure function?**

**13.  AWS?**

Amazon web services...

**14. Calculate sum of [1,2,3,4,5,6] using some of the following methods: #inject, #reduce, #map**

    2.3.0 :002 > arr.reduce(&:+)
    => 15

**15. How would you implement photo upload form using HTML+JS?**

**16. What is the best way to generate and store sessions keys?**

**17. Which is suitable HTTP response header to a HTTP request that
posts username and the username is taken?**

### 8 JavaScript Interview Questions You Need to Know

from http://insights.dice.com/2012/09/26/javascript-interview-questions/

JavaScript is a language that almost every developer can use to
accomplish little tasks, but very few developers really understand the
scope of its power, or how to take advantage of everything it can do.

**Q: How do you implement an extend function that takes an object and extends it with new properties and makes it work on n levels of recursion? Basically, duplicating a jQuery extend.**

    Motive: understanding of basic programming concepts such as recursion.

**Q: Can you write a function that takes an object and appends it to the DOM, making it so that events are buffered until the next tick? Explain why this is useful?**

This last part only applies in browser-side settings where it can dramatically increase performance.

**Q: How do you write an event emitter base class that allows you to add event listeners?**

This question can nicely lead into architectural questions, Huckestein says, such as: “How would you make an event emitter that’s distributed?”

**Q: What is the concept of “functions as objects” and how does this affect variable scope?**

New hires at Vector Media Group are asked this mid-level question, says Matt Weinberg,
president of development and technology at Vector, a web development and Internet
marketing agency in Manhattan.

“What it can suggest is that the person really ‘gets’ JavaScript and the way it works
as opposed to just having copied syntax and code from the web without understanding
it,” Weinberg says. “It can also show that the person has at least some understanding of
basic programming concepts, which in my experience means they will be better equipped
to come up with good solutions to hard problems.”

**Q: What modern JavaScript frameworks and utilities excite you right now from an approach and code point of view, even if they’re not yet stable enough for client work?**

“I’m less concerned with the actual answers, though there are some frameworks I’m very interested in,”
Weinberg says. “[I’m] more concerned with knowing that they keep up to date on the latest thinking around JavaScript.”

Weinberg added: “When they explain what excites them about these frameworks or utilities,
I can get a good sense of the kind of work and style they prefer.”

Kubasik is also concerned about the flood of “copy-and-paste” JavaScript solutions.

“jQuery and its plugin system are so popular that many developers only know JavaScript in that context,
and have trouble understanding how to create new functionality,” Kubasik says. “While this is fine for many
websites, which only need a dynamic menu or homepage carousel, as the emerging web becomes more “stateful”
– (he points to USA Today’s redesign as an example of pages that users navigate without loading a new page)
– this knowledge becomes crucial to developing robust and maintainable applications.”

**Q: What is the difference between .call() and .apply()?**

The JavaScript Function prototype has two very powerful functions that are at the core of Javascript’s “everything is an object” mentality, including functions, Kubasik says.

“The really important part of this discussion is not that they remember which is which, but more that the
interviewee understands that the “this” keyword is not as predictable as in other languages, and that
functions can be applied to other objects, and generally be treated as data,” he says.

**Q: Can you explain how inheritance works in JavaScript?**

JavaScript has a somewhat unique inheritance model and a good understanding of it is crucial to using JavasScript
in larger applications, Kubasik says.  “We are looking for the applicant to discuss not only prototypes, and how that
affects inheritance, but in what ways this can be more flexible than classical inheritance models seen in Java and C#.”

**Q: What is event bubbling in the DOM?**

The main goal of this question is to establish that the applicant knows what order events will be propagated
in the DOM – most specific to least specific.

“Not everyone may know this by the name ‘event bubbling,’ so asking about event propagation in general is
sometimes needed. Ideally, this is an opportunity to discuss event models outside of the DOM, and ask follow-up
questions about routing based on user actions, looking for techniques popularized with frameworks like backbone.js,
or AngularJS,” Kubasik says.

Blake Haggerty, Rackspace’s lead recruiter in San Francisco, says that beyond specific questions, recruiters have other resources for assessing candidates’ skills with JavaScript.

“I can go onto GitHub or BitBucket. I can actually look at what they’ve done with their code. I can see the projects
they’ve worked on and I can see how much they’ve contributed to projects. I can go onto sites like Stack Overflow
and see who are the influential people in the community, see who’s answering questions specifically about JavaScript,”
he says. “… from that I already know they’re technically savvy, so from there, my role is just to convince them to
leave where they currently are and come work for us.”

# RESOURCES

**Theory**

    Algorithm Design Manual

**What are the best websites a programmer should visit?**

**Blogs**

    Coding Horror
    The Codist
    Martin Fowler
    Matt Might
    Me, Myself and Mathematics
    On Coding
    Peter Norvig
    Project Nayuki
    Stuff you need to Code Better!

**Coding Style Guides**

    CS 106B: Programming Abstractions
    Good C programming habits
    Google C++ Style Guide
    How to Report Bugs Effectively
    How do I debug my program?

**General Advice and Tips**

    Code Review Best Practices
    Dieter Rams | Ten Principles for Good Design
    How to become a programmer, or the art of Googling well
    Lessons From A Lifetime Of Being A Programmer
    Programming Isn't Manual Labor, But It Still Sucks
    Teach Yourself Programming in Ten Years
    Things I Wish Someone Had Told Me When I Was Learning How to Code
    What are some bad coding habits you would recommend a beginner avoid getting into?
    What every computer science major should know

**Which is the best book to prepare for coding/programming interview?**

- Cracking the Coding Interview
- Coding Interview Questions
- Cracking the C, C++ and Java Interview
- Peeling Design Patterns: For Beginners and Interviews
- Cracking the IT Interview Book
- Programming Interviews Exposed: Secrets to Landing Your Next Job (WROX)
- Elements of Programming Interviews Book
- IT Interview Questions: A Primer for the It Job Interviews (Concepts, Problems and Interview Questions)
- Java Programming Interviews Exposed (WROX)

**Training and improving**

- https://projecteuler.net/. Project Euler is a series of challenging mathematical/computer
programming problems that will require more than just mathematical insights to solve.
