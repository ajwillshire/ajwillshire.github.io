# Why the F# community should show VB a bit more love

## Part one - Politics
It’s a common cry in the F# community that “.NET is not C#”, by which they usually mean “it works with F# too”. But how many of those people ever supported the VB community when they made the same plea? 
It’s a pattern that should be familiar to software developers; a procedure is usually configured to work for a single item or multiple items. As soon as you have a procedure that works for a list of two things, making it work for three is almost trivial.
So back when .NET was just C# and VB, Microsoft seemingly made the decision to concentrate on C#, with VB as an afterthought at best. This process culminated recently with the announcement that Microsoft would no longer keep VB at anything like parity to C# in terms of functionality. In a sense, this is now just managed decline. The clear message is they hope that enterprise users of VB will gradually migrate to C#.
This should be resisted just as vigorously by F# developers as by VB developers for one simple reason – we want Microsoft to be a multi-language company. Do people really think that once VB falls by the wayside that will mean more internal focus for F#? More likely, it will be seen as the final obstacle to making MS support just a single language.


Anthony D. Green's [blog][ADG-blog] in response to the announcement (worth reading in full) pays tribute to how the F# community has shepherded their language through some troubled times.



## Part 2 - Adoption
It's worth considering that the World's number one programming language is a functional language; Microsoft Excel. (Not VBA, Excel itself). It has a poweful, unique IDE, it's quite opinionated and it's used by millions of people every day to convert data and user actions into a useful output.

And a large minority of those users are also familiar with VBA.

There is a mindset to building up applications in Excel, even simple spreadsheets.

So while there may be a lot of C# developers to potentially harvest, there are even more Excel users and "power-users".




## Part 3 - Code style

```lang-VB
Option Explicit On
Option Strict On
Option Infer On
```



```lang-FSharp

module FSharpFunctions =

    let ex1(a:int):int = 
        let b = a + 1
        b

```



```lang-VB
Public Module VBFunctions

    Function Ex1(a as Integer) as Integer

        Dim b = a + 1
        Return b

    End Function

End Module

```
The VB compiler is smart enough to know that `b` is an integer (thanks to `Option Infer On`). 


```lang-CSharp

public static class CSharpFunctions
{
    public static int Ex1(int a)
    {
        var b = a + 1;
        return b;
    }
}
```

A "static class"? Why do we have to repeat "public"? What's with the semicolons? 

Sure, I can see that VB is a bit more verbose, but it's not the first time I've wished for an "End Function" in F# to restrict the scope of whatever I'm working on rather than have the whole page light up with red underlining as I type. 

The most pertinent question is, though, if you had to switch between F# and either C# or VB in a project, why would you choose C#?




## Part 4 Reasons why VB is cool anyway

XML Literals





[ADG-blog]:https://anthonydgreen.net/2020/03/19/part-i-a-fundamental-right-to-self-determination/