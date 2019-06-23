# "Quickly Testing Legacy Code" at CPPP 2019

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Contents**

- [Introduction](#introduction)
- [About the talk](#about-the-talk)
- [ApprovalTests.cpp code samples](#approvaltestscpp-code-samples)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

Code samples and information for my talk "Quickly Testing Legacy Code" at [CPPP 2019](https://cppp.fr/).

The samples here demonstrate use of [ApprovalTests.cpp](https://github.com/approvals/ApprovalTests.cpp), which is a new C++ implementation of Llewellyn Falco's [Approval Tests](http://approvaltests.com/) approach to testing legacy code.

## About the talk

* Abstract: [Quickly Testing Legacy Code](https://cppp.fr/index.php?L=0&id=20#talk.ClareMacrae)
* Video: 
* Slides: [PowerPoint](https://www.slideshare.net/ClareMacrae/quickly-testing-legacy-code-cpppfr-2019-clare-macrae)
* Slides: [PDF](https://github.com/cppp-france/CPPP-19/tree/master/quickly_testing_legacy_code-Clare_Macrae) (including some more detailed slides that were hidden both in the talk and in the Powerpoint version above)
* Code: [Github](https://github.com/claremacrae/cppp2019) (here)

## ApprovalTests.cpp code samples

Purpose of the sub-directories in this repo:

* [demo_approvals_and_catch2/](demo_approvals_and_catch2)
    * Some example uses of [ApprovalTests.cpp](https://github.com/approvals/ApprovalTests.cpp) with the [Catch2 test framework](https://github.com/catchorg/Catch2), with detailed explanatory comments in the code.
* [demo_approvals_and_googletest/](demo_approvals_and_googletest)
    * Some example uses of [ApprovalTests.cpp](https://github.com/approvals/ApprovalTests.cpp) with the [Google Test framework](https://github.com/google/googletest), with detailed explanatory comments in the code.
* [gilded_rose_refactoring_kata/](gilded_rose_refactoring_kata)
    * A worked example of the [cpp version of Emily Bache's GildedRose Refactoring Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata/tree/master/cpp)

