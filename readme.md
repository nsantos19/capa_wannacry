# WannaCry Capa Report

This is a quick report comparing  techincal reports of WannaCry with a generated Capa report.

By analyzing this capa report, it is possible to determine specific techinal features. 

## Overall Calls

![Call Pie Chart](img/pie.png)

As shown by this overall system call pie chart, it is obvious that the primary function of this program
is to navigate a filesystem and encrypt files. 

This tracks with the purpose of *WannaCry*, as this is ransomeware. 

The amount of *Xor* encryption also flags this as malware, as I believe *WannaCry* uses this encryption to obfuscate it's launcher and shell code before execution, as per Blackberry's threat spotlight. [source](https://blogs.blackberry.com/en/2017/06/threat-spotlight-inside-the-wannacry-attack)


## In Depth Calls

For this portion, I will be comparing this [analysis](https://www.secureworks.com/research/wcry-ransomware-analysis) from Secureworks with the capa report.









