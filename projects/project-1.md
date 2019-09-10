---
layout: project
type: project
image: images/sh.jpg
title: Hash Algorithm (SHA-1) 
permalink: projects
# All dates must be YYYY-MM-DD format!
date: 2019-05-01
labels:
  - C++
summary: This project is to implement the Secure Hash Algorithm (SHA-1) in C or C++.
---

<div class="ui small rounded images">
 
</div>

•	This algorithm takes a file, cuts up and mixes the data, and produces a hash value, which is a number in a specific range.
•	The hash value for SHA1 is 160 bits long, so it has a decimal value of 2160, which is roughly the number of atoms on planet Earth.
•	The SHA-1 hash value is often used in data security for such things as storing passwords securely, error detection, comparing files, and digital signatures.
o	Today, many applications still rely on SHA-1, even though theoretical attacks have been known since 2005, and SHA-1 was officially deprecated by NIST in 2011. For more on this see:https://shattered.io/
o	The attack proving SHA-1 vulnerability required over 9,223,372,036,854,775,808 SHA1 computations. This took the equivalent processing power as 6,500 years of single-CPU computations and 110 years of single-GPU computations.
•	For detailed specifications of the algorithm, see the NIST document FIPS180-1-SecureHashStandard.pdf attached below.
o	The specifications are "a bit technical", but you should spend some time reading it before attempting the project!
o	The description of the algorithm begins on page 6.
o	Appendices A-C have very detailed output that you can use to debug your program. Make sure you understand the document well enough to grasp what Appendix A is saying about the output.
o	The 3 input files described in the appendices are attached below.
	Appendix A input file is: abc.txt
	Appendix B input file is: alpha.txt
	Appendix C input file is: a.txt
o	In the document, "word" refers to data type "int", both which are 32 bits.






