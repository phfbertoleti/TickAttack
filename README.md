# TickAttack - gerenciador de tarefas para ARM Cortex M0  

O TickAttack é um gerenciador de tarefas simples, feito para facilitar o desenvolvimento de sistemas embarcados em microcontroladores ARM Cortex M0. Tal gerenciador conta com Kernel cooperativo (orientado à temporização, sem considerar prioridades nas tarefas), mecanismo de gerenciamento para dados compartilhados entre as tarefas e é um código leve e bastante modularizado.

Até o momento, o projeto está feito "plug and play" para a Eval Board STM32072RBDISCOVERY, da ST Microeletronics. 


O uso é 100% livre.


Adicional: versão para ATTiny85

Dada a popularização do Arduino (sobretudo àqueles com o microcontrolador ATTiny85), foi feito um port do TickAttack (respeitando as devidas restriçes de recurso e hardware do ATTiny85)
