---
title: Internships | Open Source Program Office
layout: job-listing
permalink: /activities/internships/taskflow
job-title: Taskflow
job-link: https://studentjobs.hr.wisc.edu/cw/en-us/job/509729
---
### Project leader:
Tsung-Wei (TW) Huang; (tsung-wei.huang@wisc.edu)

### Project description:
This project will enhance the unit testing facility of Taskflow, a
general-purpose task-parallel programming system in modern C++. You will
work with the Taskflow team (led by Dr. Tsung-Wei Huang in ECE) to design
and implement comprehensive testing frameworks for verifying correctness,
performance, and scalability of Taskflow’s core components. The project will
involve creating automated test suites, integrating continuous integration
(CI) tools, and improving test coverage for advanced features such as condition
tasks, dynamic tasking, and GPU offloading.

To sustain the growth and reliability of Taskflow, this proposal aims to
strengthen its continuous integration (CI) and testing infrastructure. Taskflow
is a general-purpose task-parallel programming system using modern C++. Started
in 2018 as a DARPA-sponsored research project, it has been evolving to a popular
programming system in the C++ community. As Taskflow continues to attract
users and contributors from academia and industry, ensuring robust, scalable,
and comprehensive testing becomes essential. The proposed effort will focus on
expanding the test coverage across heterogeneous environments, incorporating
performance regression tracking, and automating validation workflows to detect
subtle concurrency and portability issues. By advancing Taskflow’s CI ecosystem,
this project will not only improve code quality and developer productivity but
also ensure that Taskflow remains a dependable foundation for high-performance
parallel programming in modern C++. Focused CI tasks are outlined below:

1. Performance Regression Tracking:
Integrate automated benchmarking into CI to detect and report performance
regressions on representative workloads, ensuring each commit maintains or
improves execution efficiency.

2. Thread-Safety and Concurrency Stress Testing:
Develop CI modules that run randomized stress tests to detect data races,
deadlocks, or nondeterministic failures, using tools such as ThreadSanitizer and
Valgrind’s Helgrind.

3. Static and Dynamic Analysis Integration:
Incorporate static analyzers (e.g., clang-tidy, cppcheck) and dynamic tools
(e.g., AddressSanitizer, UndefinedBehaviorSanitizer) into the CI workflow to
proactively identify subtle bugs and undefined behavior.

4. Documentation and Example Validation:
Automate the compilation and execution of Taskflow tutorials, examples, and
documentation snippets to guarantee correctness and prevent divergence between
code and documentation.

### Intern needs:
C++, GitHub

