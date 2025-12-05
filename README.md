# PwrSimLang
PwrSimLang is used by psCARA, a Desktop ISE (Integrated Simulation Environment)

## Ownership
PwrSimLang is Copyright 2025 & Intellectual Property of Ribbon Grid an Australian Company. Ribbon Grid and psCARA are protected under Australian Trademarks.

## Description

The PwrSimLang is used to describe power system modeling Jobs, which are contained in *.pwrsim files. Each Job can contain multiple tasks. 
The language is a proprietary plain text language with a proprietary natural language interpreter and linter.

## Use with LLMs

The psCARA software includes a help file that describes the usage of the language. You must purchase the software and sign the Terms to gain access to this information.
For a single user install the description is found in:
C:\Users\Username\AppData\Local\psCARA\help\psCARA_PwrSimLang.md
For a server or multi-user install, it is found in: 
C:\Program Files\psCARA\help\psCARA_PwrSimLang.md

If you are using LLMs to create .pwrsim files for multi-task psCARA Jobs, feed `psCARA_PwrSimLang.md` into the LLM or include it in a project. 

Note that, the PwrSimLang is designed to be very simple, such that anyone can understand it. Also if you press the `Check` button next to `Run` on psCARA header bar this will correct any errors in your *.pwrsim file and describe any conflicts with suggestions. 

## Users

The PwrSimLang is the first custom application layer language designed specifically for power systems modeling. It has been created to bridge the gap between Python Wizards (PSM Python automation experts) and electrical engineers.

- Electrical Engineers are expected to use the simple plain text implementations created by Python Wizards.
- Python Wizards develop the examples and inputs in the psCARA framework. This allows for automations that run on your laptop or a supercomputer, based on simple switch of a send-to input. 
