# Patterns.IfThenElse Active Pattern (F#)

Recognizes expressions that represent conditionals.

**Namespace/Module Path**: Microsoft.FSharp.Quotations.Patterns

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## Syntax


```


// Signature:
( |IfThenElse|_| ) : (input:Expr) -> (Expr * Expr * Expr) option

```



#### Parameters
*input*
Type: [Expr](http://msdn.microsoft.com/en-us/library/ed6a2caf-69d4-45c2-ab97-e9b3be9bce65)


The input expression to match against.



**The formal return type is (Expr &#42; Expr &#42; Expr) option. The option determines whether there is a match. In a pattern matching expression, the input is decomposed upon a match into a tuple of three expressions. The first element is the test condition. The second element is the expression after the then keyword that is executed if the test condition is true. The third element is the expression after the else keyword.**
## Remarks
This function is named **IfThenElsePattern** in the .NET Framework assembly. If you are accessing the member from a .NET Framework language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Quotations.Patterns Module &#40;F&#35;&#41;](Quotations.Patterns+Module+%28FSharp%29.md)

[Microsoft.FSharp.Quotations Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Quotations+Namespace+%28FSharp%29.md)
