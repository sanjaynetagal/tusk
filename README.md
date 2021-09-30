## Test plan for knowing the functionality of Digital Electronic Circuits

| **Test ID** | **Description**                                              | **Explaination**      | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------     |-------------|----------------|------------------|
|  L_01       |  Minterm Functionality| input a=1 and b=1 then output Y=1 because Y=a*b |1|1|Requirement based |
|  L_02       |  Maxterm Functionality| input a=1 and b=1 then output Y=0 because Y=~(a)*(~b) |0|0|Requirement based |
|  L_03       |  Sum Of Product| input a=1 and b=1 then output Y=1 because Y=b+(a*~(b)) |1|1|Requirement based |
|  L_04       |  Product Of Sum| input a=1 and b=1 then output Y=1 because Y=(a*(~b)+b) |1|1|Requirement based |
|  L_05       |  Associative Law| input a=1 and b=1 and c=1 then output Y=1 because Y=1 only when the condition is true associative law for this is (A+(B+C))=((A+B)+C) |1|1|Requirement based |
|  L_06       |  Distributive Law| input a=1 and b=1 and c=1 then output Y=1 because Y=1 only when the condition is true associative law for this is (A+(B+C))=((A+B)+C) |1|1|Requirement based |
|  L_07       |  Commutative Law| input a=1 and b=1 then output Y=1 because Y=1 only when the condition is true Commutative law for this is (A+B)=(B+A) |1|1|Requirement based |
|  L_08       |  Absorption Law| input a=1 and b=1 then output Y=1 because Y=1 only when the condition is true Absorption law for this is (A+(A*B))=A|1|1|Requirement based |
