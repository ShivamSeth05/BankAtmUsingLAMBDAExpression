# Assignment:(BankTransaction Process)
## BankAtmUsingLAMBDAExpression
### Real Time Example of Lambda Expressions 
(a)read pinNo
 pinNo must be 4 digits,else &quot;Invalid pinNo&quot;
If pinNo is validated then the PinNo must be in 1111 or 2222 or 3333,else
Incorrect PinNo...;
If pinNo entered Wrongly for three times,display the msg as &quot;Transaction
blocked temporarly;.
(b)If the PinNo is Validated and verified Successfully,select the from the choice
1.WithDraw
2.Deposit

1.WithDraw:
Enter the amt
The amt must be greater than Zero and multiples of 100,else &quot;Invalid amt&quot;
If amt Validated Successfully then create object for &quot;WithDraw&quot; class and

pass amt as parameter to process() method
part of process() method check the amt is less than bal or not.
If amt is less than bal then perform transaction,else &quot;Insufficient fund&quot;
o/p:
Amt WithDrawn :
Balance Amt :
Transaction Successful...

2.Deposit:
Enter the amt
The amt must be greater than Zero and multiples of 100,else &quot;Invalid amt&quot;
If amt Validated Successfully then create object for &quot;Deposit&quot; class and
pass amt as parameter to process() method
o/p:
Amt Deposited:
Balance Amt :
Transaction Successful...
