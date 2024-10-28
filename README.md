# PLC-languages
Języki programowania sterowników PLC na podstawie normy IEC 61131-3. Dodatkowo znajduje się GRAFCET. Natomiast w przypadku języka ST jest przedstawiony wariant SCL (dla sterowników firmy Siemens).

Kod (programy w języku LD, SCL, FBD) są napisane w programie TIA Portal w wersji V16 i V15, na urządzeniu CPU 1215 DC/DC/DC 6ES7 215-1AG40-0XB0 4.2.
Programy w języku IL są jako plik tekstowy, GRAFCET w programie FluidSIM 4.2 Pneumatic. Natomiast SFC jest tylko jako plik graficzny.

SFC oraz GRAFCET zostały wykonane w programie FluidSIM, w wyniku czego oznaczenia przy tranzycjach mogą różnić się od tych stosowanych na co dzień:
* suma logiczna jest oznaczona jako **+**, a powinna być **∪**,
* iloczyn logiczny jest oznaczony jako *, a powinno być **∩**.

Obecnie nie jest planowana poprawa oznaczeń (ale nie jest kompletnie wykluczona), ponieważ ma to charakter czysto wizualny.

## LD
ladder diagram - schemat drabinkowy (język drabinkowy)
* podstawowe funkcje
* przykłady
* RS & SR
* czasówki
* liczniki
* dwa układy sekwencyjne

## SCL
structured control language - strukturalny język sterowania
* podstawowe funkcje
* przykłady
* czasówki
* liczniki

## FBD
function block diagram - schemat bloków funkcyjnych
* podstawowe funkcje
* przykłady
* RS & SR
* czasówki
* liczniki

## IL
instruction list - lista instrukcji
* podstawowe funkcje
* przykłady
* liczniki
* czasówki

## SFC
sequential function chart - sekwencyjny wykres funkcjonalny (język sekwencyjny)
* podstawowe funkcje
* elementy sterowań

## GRAFCET
język graficzny (algorytm)
* podstawowe funkcje
* przykłady
* elementy sterowań
