# bonezegei-Protocol
The Bonezegei Protocol is a simple protocol created by Bonezegei (Jofel Batutay) for data transmission. It is a series of string separated by a character separator. 


 | No    |Value | Size  |  Command    |        Description           |
 |-------|------|-------|-------------|------------------------------|
 |1      | '\1' |1 Byte |  START      | Start of Data                |
 |2      | '\2' |1 Byte |  END        | End of Data                  |
 |3      | "\3 "|2 Bytes|  SEP        | Separator                    |
 |4      | "\4 "|2 Bytes|  NODATA     | returns this value if no data|


### Data Format
 | START |  SEP  |        DATA1        |  SEP  |        DATA2        |  SEP  |  END  | 
 |-------|-------|---------------------|-------|---------------------|-------|-------|


