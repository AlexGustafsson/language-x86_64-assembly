## 2.2.12
Further support for 64-bit AT&T syntax
* q and w postfix for mov, cmp, push, pop etc.
* support for the datatypes quad and space
* support global labels
* support for integer counterparts of div and mul

## 2.2.11
Better support for datatypes
* signed types (non-nasm)
* better support for various number notations (bin, oct, dec, hex, and packed bcd)
* better support for strings
* more built-in nasm functions for type convertion and constants

## 2.2.8
Fixed highlighting conflict for ah-dh registers with hex numbers

## 2.2.4
Expanded NASM macro support
Partial support for GAS comment style

## 2.2.3
Fixed missing AMD instructions, including support for Zen

## 2.2.2
Overhauled highlighting for sections, labels, prefixes, and numbers

## 2.1.16
Fix for single-line comment settings

## 2.1.15
Intel CFE extensions

## 2.1.11
Removed leftover dedicated comments grammar

## 2.1.10
Updated with PKRU instructions

## 2.1.5
Small highlighting fix for some string manipulation instructions

## 2.1.2 - First Release for Atom
As of right now, this bundle have:
* Basic support for nasm/yasm/tasm/gas syntaxes
* Most of the modern instruction sets (including Intel SHA/MPX/SGX)
