# Code of Code

Want to be part of a team project? Learn and apply these first:

---

## Abstraction

In software engineering and programming language theory, the abstraction
principle (or the principle of abstraction) is a basic dictum that aims to
reduce duplication of information in a program (usually with emphasis on code
duplication) whenever practical by making use of abstractions provided by the
programming language or software libraries. The principle is sometimes stated
as a recommendation to the programmer, but sometimes stated as requirement of
the programming language, assuming it is self-understood why abstractions are
desirable to use. The origins of the principle are uncertain; it has been
reinvented a number of times, sometimes under a different name, with slight
variations.

---

## Adaptive Web Design (AWD)

Using progressive enhancement, adaptive design (often rendered on server side)
scales content to the devices and provides graceful degradation for legacy
systems. The down side is the extensive use and preparation of the server for
the many possible technological edge cases.

---

## AngularJS

AngularJS is an open-source web application framework mainly maintained by
Google and by a community of individuals and corporations to address many of the
challenges encountered in developing single-page applications. It aims to
simplify both the development and the testing of such applications by providing
a framework for client-side model–view–controller (MVC) and model–view–viewmodel
(MVVM) architectures, along with components commonly used in rich Internet
applications.

---

## AngularJS modules

Significant modules: **ng** (core), **ngRoute**, ngAnimate, ngAria,
**ngResource**, ngCookies, ngTouch, **ngSanitize**, **ngMock** (unit testing
mockups) – 3rd party modules: **ui.router**, **ui.bootstrap**, ui.tinymce

---

## Behavioral Design Patterns

**Chain of Responsibility:** It avoids attaching the sender of a request to its
receiver, giving this way other objects the possibility of handling the request
too. The objects become parts of a chain and the request is sent from one object
to another across the chain until one of the objects will handle it. –
**Command:** Encapsulate a request in an object, Allows the parameterization of
clients with different requests and Allows saving the requests in a queue. –
**Interpreter:** Given a language, define a representation for its grammar along
with an interpreter that uses the representation to interpret sentences in the
language Map a domain to a language, the language to a grammar, and the grammar
to a hierarchical object-oriented design. – **Iterator:** Provide a way to
access the elements of an aggregate object sequentially without exposing its
underlying representation. – **Mediator:** Define an object that encapsulates
how a set of objects interact. Mediator promotes loose coupling by keeping
objects from referring to each other explicitly, and it lets you vary their
interaction independently. – **Observer:** Define a one-to-many dependency
between objects so that when one object changes state, all its dependents are
notified and updated automatically. – **Strategy:** Define a family of
algorithms, encapsulate each one, and make them interchangeable. Strategy lets
the algorithm vary independently from clients that use it. – **Template
Method:** Define the skeleton of an algorithm in an operation, deferring some
steps to subclasses Template Method lets subclasses redefine certain steps of
an algorithm without letting them to change the algorithm's structure. –
**Visitor:** Represents an operation to be performed on the elements of an
object structure Visitor lets you define a new operation without changing the
classes of the elements on which it operates. – **Null Object:** Provide an
object as a surrogate for the lack of an object of a given type. The Null Object
Pattern provides intelligent do nothing behavior, hiding the details from
its collaborators.

---

## Build Metadata (SemVer)

Build metadata MAY be denoted by appending a plus sign and a series of dot
separated identifiers immediately following the patch or pre-release version.
Identifiers MUST comprise only ASCII alphanumerics and hyphen [0-9A-Za-z-].
Identifiers MUST NOT be empty. Build metadata SHOULD be ignored when determining
version precedence. Thus two versions that differ only in the build metadata,
have the same precedence. Examples: 1.0.0-alpha+001, 1.0.0+20130313144700,
1.0.0-beta+exp.sha.5114f85.

---

## Clean code

SRP (Single responsibility principle), avoid workarounds, DRY (Don't repeat
youself), KISS (Keep it simple, short), YAGNI (You aren't gonna need it),
self-explaining, independent, tested and expressive code.

---

## Code Review

A code review can be done as a special kind of inspection in which the team
examines a sample of code and fixes any defects in it. In a code review, a
defect is a block of code which does not properly implement its requirements,
which does not function as the programmer intended, or which is not incorrect
but could be improved (for example, it could be made more readable or its
performance could be improved). In addition to helping teams find and fix bugs,
code reviews are useful for both cross-training programmers on the code being
reviewed and for helping junior developers learn new programming techniques.

---

## Commit (Git)

Move files from the stage to the local repository.

---

## Continuous Integration (CI)

Continuous integration (CI) is the practice, in software engineering, of merging
all developer working copies to a shared mainline several times a day. It was
adopted as part of extreme programming (XP), which did advocate integrating more
than once per day, perhaps as many as tens of times per day. Steps of CI (in
order): **Trigger**, **Upgdate**, Static Analysis, **Build**, Unit Testing,
**Deployment**, Testing, Archiving, **Reporting**. When a unit test fails, it
stops and dumps a report.

---

## Creational Design Patterns

**Singleton:** Ensure that only one instance of a class is created and provide
a global access point to the object. – **Factory:** Creates objects without
exposing the instantiation logic to the client and refers to the newly created
object through a common interface. – **Factory Method:** Defines an interface
for creating objects, but lets subclasses decide which class to instantiate
and refers to the newly created object through a common interface. – **Abstract
Factory:** Offers the interface for creating a family of related objects,
without explicitly specifying their classes. – **Builder:** Defines an instance
for creating an object but letting subclasses decide which class to instantiate
and Allows a finer control over the construction process. – **Prototype:**
Specify the kinds of objects to create using a prototypical instance, and create
new objects by copying this prototype. – **Object Pool:** reuses and shares
objects that are expensive to create.

---

## Design Patterns

In software engineering, a software design pattern is a general reusable
solution to a commonly occurring problem within a given context in software
design. It is a description or template for how to solve a problem that can be
used in many different situations. Design patterns are formalized best
practices that the programmer can use to solve common problems when designing an
application or system. Object-oriented design patterns typically show
relationships and interactions between classes or objects, without specifying
the final application classes or objects that are involved. Design patterns may
be viewed as a structured approach to computer programming intermediate between
the levels of a programming paradigm and a concrete algorithm. Types:
creational, structural, behavioral.

---

## DRY (Don't Repeat Yourself)

Don't repeat yourself (DRY) is a principle of software development, aimed at
reducing repetition of information of all kinds, especially useful in multi-tier
architectures. The DRY principle is stated as "Every piece of knowledge must
have a single, unambiguous, authoritative representation within a system." It is
applied quite broadly to include "database schemas, test plans, the build
system, even documentation." When the DRY principle is applied successfully, a
modification of any single element of a system does not require a change in
other logically unrelated elements. Additionally, elements that are logically
related all change predictably and uniformly, and are thus kept in sync. Besides
using methods and subroutines in the code, one may rely on code generators,
automatic build systems, and scripting languages to observe the DRY principle
across layers.

---

## Dummy (Unit Testing)

A Dummy is an object that simply implements an Interface, and does nothing else.
It's not intended to be used in your tests and will have no effect on the
behaviour. An example would be passing an object into a constructor that isn't
used in the path you're taking, or a simple object to add to a collection.

---

## Encapsulation

Grouping object state (properties) and behavior (functions) in a class, so that
the state of the object may change only through its behaviors.

---

## Fake (Unit Testing)

Similar to a Stub being a step up from a Dummy, the simplest way to think of a
Fake is as a step up from a Stub. This means not only does it return values, but
it also works just as a real Collaborator would. Usually a Fake has some sort of
shortcut that means that they are unsuitable for production.

---

## Framework

A software framework is an abstraction in which software providing generic
functionality can be selectively changed by additional user-written code, thus
providing application-specific software. A software framework is a universal,
reusable software environment that provides particular functionality as part of
a larger software platform to facilitate development of software applications,
products and solutions. Software frameworks may include support programs,
compilers, code libraries, tool sets, and application programming interfaces
(APIs) that bring together all the different components to enable development of
a project or solution. Frameworks contain key distinguishing features that
separate them from normal libraries: Inversion of control, default behavior,
extensibility, non-modifiable framework code. Software frameworks typically
contain considerable housekeeping and utility code in order to help bootstrap
user applications, but generally focus on specific problem domains.

---

## Git SCM

Git is a free and open source distributed version control system designed to
handle everything from small to very large projects with speed and efficiency.
Git is easy to learn and has a tiny footprint with lightning fast performance.
It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with
features like cheap local branching, convenient staging areas, and multiple
workflows.

---

## Index (Git)

The index is the staging area.

---

## KISS (Keep it Simple, Stupid)

The KISS principle states that most systems work best if they are kept simple
rather than made complicated; therefore simplicity should be a key goal in
design and unnecessary complexity should be avoided.

---

## Major Version (SemVer)

MUST be incremented if any backwards incompatible changes are introduced to the
public API. It MAY include minor and patch level changes. Patch and minor
version MUST be reset to 0 when major version is incremented.

---

## Major Version Zero (SemVer)

Major version zero (0.y.z) is for initial development. Anything may change at
any time. The public API should not be considered stable.

---

## Major Version One (SemVer)

Version 1.0.0 defines the public API. The way in which the version number is
incremented after this release is dependent on this public API and how it
changes.

---

## Minor Version (SemVer)

MUST be incremented if new, backwards compatible functionality is introduced to
the public API. It MUST be incremented if any public API functionality is marked
as deprecated. It MAY be incremented if substantial new functionality or
improvements are introduced within the private code. It MAY include patch level
changes. Patch version MUST be reset to 0 when minor version is incremented.

---

## Mock (Unit Testing)

Whilst all of the other types of Test Double build on each other, gradually
adding more functionality, Mocks are something totally different. Until now, all
of our test doubles have made assertions on state. Mocks are test doubles that
make assertions on behaviour.

---

## Modular Programming

Modular programming is a software design technique that emphasizes separating
the functionality of a program into independent, interchangeable modules, such
that each contains everything necessary to execute only one aspect of the
desired functionality. A module interface expresses the elements that are
provided and required by the module. The elements defined in the interface are
detectable by other modules. The implementation contains the working code that corresponds to the elements declared in the interface. With modular programming,
concerns are separated such that modules perform logically discrete functions,
interacting through well-defined interfaces.

---

## MVC (Model-View-Presenter)

The input is directed at the Controller first, not the view. That input might be
coming from a user interacting with a page, but it could also be from simply
entering a specific url into a browser. In either case, it's a Controller that
is interfaced with to kick off some functionality. There is a many-to-one
relationship between the Controller and the View. That’s because a single
controller may select different views to be rendered based on the operation
being executed. The View doesn’t have any knowledge of or reference to the
controller. The Controller does pass back the Model, so there is knowledge
between the View and the expected Model being passed into it, but not the
Controller serving it up.

## MVP (Model-View-Presenter)

The input is directed at the View first, not the Presenter. There is a
one-to-one mapping between the View and the associated Presenter. The View holds
a reference to the Presenter. The Presenter is also reacting to events being
triggered from the View, so it's aware of the View it's associated with. The
Presenter updates the View based on the requested actions it performs on the
Model, but the View is not Model aware.

---

## MVVM (Model-View-View Model)

The input begins with the View, not the View Model. While the View holds a
reference to the View Model, the View Model has no information about the View.
This is why it's technically possible to have a one-to-many mapping between
various Views and one View Model, even across technologies. The View has no idea
about the Model in the MVVM pattern. This is because, as far as the View knows,
its “Model” IS the View Model (hence its name). Because of how data-binding and
other features like commanding work, there is rich communication between the
View and View Model, isolating the View from having to know anything about
what’s really happening behind the scenes.

---

## Node.js

Node.js is an open-source, cross-platform runtime environment for developing
server-side Web applications. Although Node.js is not a JavaScript framework,
many of its basic modules are written in JavaScript, and developers can write
new modules in JavaScript. The runtime environment interprets JavaScript using
Google's V8 JavaScript engine. Node.js has an event-driven architecture capable
of asynchronous I/O. These design choices aim to optimize throughput and
scalability in Web applications with many input/output operations, as well as
for real-time Web applications (e.g., real-time communication programs and
browser games).

---

## Paradigm

The structure of the programming toolkit. Examples: Procedural (C),
Object-oriented (Java), Functional (J), Multi-paradigm (JavaScript).

---

## Patch Version (SemVer)

MUST be incremented if only backwards compatible bug fixes are introduced. A bug
fix is defined as an internal change that fixes incorrect behavior.

---

## Pre-Release Version (SemVer)

A pre-release version MAY be denoted by appending a hyphen and a series of dot
separated identifiers immediately following the patch version. Identifiers MUST
comprise only ASCII alphanumerics and hyphen [0-9A-Za-z-]. Identifiers MUST NOT
be empty. Numeric identifiers MUST NOT include leading zeroes. Pre-release
versions have a lower precedence than the associated normal version. A
pre-release version indicates that the version is unstable and might not satisfy
the intended compatibility requirements as denoted by its associated normal
version. Examples: 1.0.0-alpha, 1.0.0-alpha.1, 1.0.0-0.3.7, 1.0.0-x.7.z.92.

---

## Pull (Git)

Combines local repository with remote server repository in local repository.

---

## Push (Git)

Uploads local repository to remote server repository if local repository is
strictly ahead of the remote server repository.

---

## Responsive Web Design (RWD)

Responsive design operates with arbitrary values, flexible grids and media query
selectors, providing dynamic content arrangement for any screen size, both orientations, at any resolution. It cannot scale down to device bottlenecks.

---

## SCM (Git)

Source Code Management. Example: Git SCM.

---

## Semantic Versioning (SemVer)

Software using Semantic Versioning MUST declare a public API. This API could be
declared in the code itself or exist strictly in documentation. However it is
done, it should be precise and comprehensive. A normal version number MUST take
the form X.Y.Z where X, Y, and Z are non-negative integers, and MUST NOT contain
leading zeroes. X is the major version, Y is the minor version, and Z is the
patch version. Each element MUST increase numerically. For instance: 1.9.0 ->
1.10.0 -> 1.11.0. Once a versioned package has been released, the contents of
that version MUST NOT be modified. Any modifications MUST be released as a new
version.

---

## Separation of concerns (SoC)

In computer science, separation of concerns (SoC) is a design principle for
separating a computer program into distinct sections, such that each section
addresses a separate concern. A concern is a set of information that affects the
code of a computer program. A concern can be as general as the details of the
hardware the code is being optimized for, or as specific as the name of a class
to instantiate. A program that embodies SoC well is called a modular program.
Modularity, and hence separation of concerns, is achieved by encapsulating
information inside a section of code that has a well-defined interface.
Encapsulation is a means of information hiding. Layered designs in information
systems are another embodiment of separation of concerns (e.g., presentation
layer, business logic layer, data access layer, persistence layer). When
concerns are well-separated, individual sections can be reused, as well as
developed and updated independently. It allows us to later improve or modify one
section of code without having to know the details of other sections, and
without having to make corresponding changes to those sections.

---

## Spy (Unit Testing)

A Stub could also be used to maintain state, and make assertions, when a Stub
does this it is also known as a Test Spy. For example, checking the contents of
a parameter, or the total number of times a method is called.

---

## Staging area (Git)

The staging area is an index of files to add to the repository with the next
commit. This helps keeping commit topics separate.

---

## Stash (Git)

In Git, the stash operation takes your modified tracked files, stages changes,
and saves them on a stack of unfinished changes that you can reapply at any
time. Use it in case something urgent interrupts your code.

---

## Static program analysis

Static program analysis is the analysis of computer software that is performed
without actually executing programs (analysis performed on executing programs is
known as dynamic analysis).[1] In most cases the analysis is performed on some
version of the source code, and in the other cases, some form of the object
code. The term is usually applied to the analysis performed by an automated
tool, with human analysis being called program understanding, program
comprehension, or code review. Software inspections and Software walkthroughs
are also used in the latter case.

---

## Structural Design Patterns

**Adapter:** Convert the interface of a class into another interface clients
expect. Adapter lets classes work together, that could not otherwise because
of incompatible interfaces. – **Bridge:** Decouple abstraction from
implementation so that the two can vary independently. – **Composite:** Compose
objects into tree structures to represent part-whole hierarchies. Composite lets
clients treat individual objects and compositions of objects uniformly. –
**Decorator:** Add additional responsibilities dynamically to an object. –
**Flyweight:** use sharing to support a large number of objects that have part
of their internal state in common where the other part of state can vary. –
**Memento:** Capture the internal state of an object without violating
encapsulation and thus providing a mean for restoring the object into initial
state when needed. – **Proxy:** Provide a “Placeholder” for an object to control
references to it.

---

## Stub (Unit Testing)

Think of a Stub as a step up from a Dummy. It implements a required Interface,
but instead of missing method bodies, it usually returns canned responses in
order for you to make assertions on the output.

---

## Test Double (Unit Testing)

A Test Double is simply another object that conforms to the interface of the
required Collaborator, and can be passed in in its place. There are several
different types of Test Double.

---

## Unit Testing

In computer programming, unit testing is a software testing method by which
individual units of source code, sets of one or more computer program modules
together with associated control data, usage procedures, and operating
procedures, are tested to determine whether they are fit for use. Intuitively,
one can view a unit as the smallest testable part of an application. In
object-oriented programming, a unit is often an entire interface, such as a
class, but could be an individual method. **Benefits:** Finds problems early
(defects), Facilitates change (refactor), Simplifies integration (bottom-up),
Documentation (describes actual code), Design (tests assume concept)

---

## View (MVC)

The view manages the display of information.

---

## YAGNI (You Aren't Gonna Need It)

"You aren't gonna need it" (acronym: YAGNI) is a principle of extreme
programming (XP) that states a programmer should not add functionality until
deemed necessary. XP co-founder Ron Jeffries has written: "Always implement
things when you actually need them, never when you just foresee that you need
them." Other forms of the phrase include "You aren't going to need it" and
"You ain't gonna need it".
