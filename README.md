# Spring-JPA-Filter-for-RSQL
Spring JPA Filter for RSQL 


RSQL Supported Operators:

|Logical Operator|Description|Example|
|!=|Not Equal To|?filter=name!=Yonit|
|==|Equal To|?filter=name==Yonit ?filter=name==*nit ?filter=name==Y*|
|>=  =ge= |Greater Or Equal To|?filter=size>=50|
|>  =gt=|Greater Than|?filter=size>50|
|<=  =le=|Less Or Equal To|?filter=size=le=100 ?filter=size<=100|
|<  =lt=|Less Than|?filter=size=lt=100 ?filter=size<100|
|=in=|In|"?filter=id=in=(""f91619bd-9fae-86bb-6c80-ce88f054f24d""| ""c937e60a-1f6e-631e-1a1a-8779bbdbb98e"")"|
|=out=|Not in|"?filter=id=out=(""f91619bd-9fae-86bb-6c80-ce88f054f24d"")"|

|Composite Operator|Description|Example|
|" , "|Logical OR|"?filter=name==Dviry,name==Yonit"|
|;|Logical AND|?filter=size>50;size<100|