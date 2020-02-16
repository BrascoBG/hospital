# hospital

За даден период от време, всеки ден в болницата пристигат пациенти за преглед.
Тя разполага първоначално със 7 лекари. Всеки лекар може да преглежда само по
един пациент на ден, но понякога има недостиг на лекари, затова останалите
пациенти се изпращат в други болници. Всеки трети ден болницата прави
изчисления и ако броят на непрегледаните пациенти е по-голям от броя на
прегледаните, се назначава още един лекар. Като назначаването става преди да
започне приемът на пациенти за деня.

Програма, която изчислява за дадения период броя на прегледаните и
непрегледаните пациенти.

Входни данни

На първия ред (аргумент) от входа стои цяло число -
периода, за който трябва да направите изчисления . На следващите редове
(аргумента) стои по едно цяло число – броя пациенти,
които пристигат за преглед за текущия ден.


Изходни данни

Да се отпечатат на конзолата 2 реда:

• На първия ред: "Treated patients: {брой прегледани пациенти}."

• На втория ред: "Untreated patients: {брой непрегледани пациенти}."