---
{"dg-publish":true,"permalink":"/digital-garden-homepage/","tags":["gardenEntry"]}
---

# DIGITAL GARDEN HOMEPAGE


| File                                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------ |
| [[Data Analyst/GROUPBY & PIVOTBY Functions\|GROUPBY & PIVOTBY Functions]]                                                               |
| [[90 Feeding Zone/Videos/Identify Rows with Missing Values using Power Query\|Identify Rows with Missing Values using Power Query]]     |
| [[90 Feeding Zone/Videos/When Should You Use the Hash Sign in Excel Formulas 1\|When Should You Use the Hash Sign in Excel Formulas 1]] |
| [[90 Feeding Zone/Videos/GROUPBY and PIVOTBY Functions\|GROUPBY and PIVOTBY Functions]]                                                 |
| [[90 Feeding Zone/Videos/GROUPER.PAR\|GROUPER.PAR]]                                                                                     |
| [[Digital Garden Homepage\|Digital Garden Homepage]]                                                                                    |
| [[Timestamps/2025/03-March/TAKE & DROP Functions\|TAKE & DROP Functions]]                                                               |

{ .block-language-dataview}



``dataviewjs  
const pdfFiles = app.vault.getFiles().filter(file => file.extension === 'pdf' && file.path.includes('myFolder'))  
dv.list(pdfFiles.map(file => dv.fileLink(file.path)));  
``