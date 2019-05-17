# NDE03

<table>
<tr>
<th align="left">For Session</th>
<td>2019/20</td>
</tr>
<tr>
<th align="left">Theme of Projects</th>
<td>Automated Discovery of Vulnerabilities</td>
</tr>
<tr>
<th align="left">Supervisor</th>
<td>Nick Efford</td>
</tr>
<tr>
<th align="left">Project Type</th>
<td>Exploratory Software</td>
</tr>
<tr>
<th align="left">Areas of Interest</th>
<td>Computer security, software development, programming languages,
web applications</td>
</tr>
<tr>
<th align="left">Appropriate For</th>
<td>All programmes</td>
</tr>
<tr>
<th align="left">Multiple Projects?</th>
<td>Yes</td>
</tr>
<tr>
<th align="left">Prerequisites</th>
<td>COMP2911 or COMP2931, COMP3911</td>
</tr>
</table>

## Problem Domain

Modern software is plagued with vulnerabilities of various kinds, some
of which could undoubtedly have been detected at an early stage through
appropriate use of security testing techniques and tools.

Different approaches to uncovering vulnerabilities are possible. One approach
is **static analysis**, which relies on finding dangerous patterns of use
(e.g., use of deprecated and insecure library functions) in source code.
Another approach is **fuzzing**, whereby the software under test is fed with
a wide range of automatically-generated random inputs in order to identify
cases that aren't handled properly and that might lead to security problems.

Many tools already exist, but some are very old and most have been developed
in isolation from each other, without consideration of how they might work
as part of suite of tools.  Hence there is generally little or no
standardisation in how results of testing are reported.

## Possible Projects

There is scope for more than one project in this area.  Projects might
include one or more of the following elements:

* Critical evaluation of existing tools (accuracy, reliability, ease of use, etc)

* Development of a framework for vulnerability analysis, allowing new
  techniques to be added, new programming languages to be supported, etc

* Integration of vulnerability scanning into software development workflow -
  e.g., by defining custom tasks for build systems such as Gradle

* Detailed investigation of one particular class of vulnerability and
  development of prototype software to detect it
