:orphan:

.. title:: SSE_FP_MATH

.. option:: CONFIG_SSE_FP_MATH:
.. _CONFIG_SSE_FP_MATH:

This option allows the compiler to generate SSEx instructions for
performing floating point math. This can greatly improve performance
when exactly the same operations are to be performed on multiple
data objects; however, it can also significantly reduce performance
when pre-emptive task switches occur because of the larger register
set that must be saved and restored.

Disabling this option means that the compiler utilizes only the
x87 instruction set for floating point operations.


:Symbol:           SSE_FP_MATH
:Type:             bool
:Value:            "n"
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   false
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Compiler-generated SSEx instructions" if SSE (value: "n")
:Default values:

 *  n (value: "n")
 *   Condition: SSE (value: "n")
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 CPU_HAS_FPU && X86 (value: "n")
:Locations:
 * ../arch/x86/Kconfig:122