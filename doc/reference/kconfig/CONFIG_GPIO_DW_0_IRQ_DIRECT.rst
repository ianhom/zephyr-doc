:orphan:

.. title:: GPIO_DW_0_IRQ_DIRECT

.. option:: CONFIG_GPIO_DW_0_IRQ_DIRECT:
.. _CONFIG_GPIO_DW_0_IRQ_DIRECT:

When interrupts fire, the driver's ISR function is being called directly.



:Symbol:           GPIO_DW_0_IRQ_DIRECT
:Type:             bool
:Value:            "n"
:User value:       (no user value)
:Visibility:       "n"
:Is choice item:   true
:Is defined:       true
:Is from env.:     false
:Is special:       false
:Prompts:

 *  "Direct Hardware Interrupt"
:Default values:
 (no default values)
:Selects:
 (no selects)
:Reverse (select-related) dependencies:
 (no reverse dependencies)
:Additional dependencies from enclosing menus and ifs:
 GPIO_DW && GPIO (value: "n")
:Locations:
 * ../drivers/gpio/Kconfig.dw:74