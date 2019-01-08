---
title: Func(T1, T2, T3, T4, T5, TResult) Delegate
page_title: Func(T1, T2, T3, T4, T5, TResult) Delegate | JustMock Documentation
description: Documentation page about Func(T1, T2, T3, T4, T5, TResult) Delegate.
previous_url: /t_telerik_justmock_func_6.html
slug: t_telerik_justmock_func_6
published: True
fullPath: api/n_telerik_justmock/t_telerik_justmock_func_6
category: "api"
---

# Func&lt;T1,T2,T3,T4,T5,TResult&gt;Delegate



Encapsulates a method that has 5 parameters and returns a value of the type specified byTResultparameter.


 **Namespace:**  [Telerik.JustMock](n_telerik_justmock) <br> **Assembly:** Telerik.JustMock(in Telerik.JustMock.dll)
## Syntax


<div id="syntaxCodeBlocks" class="code"><span codeLanguage="CSharp"><table><tr><th>C#</th></tr><tr><td><pre xml:space="preserve">[<a href="https://msdn2.microsoft.com/en-us/library/8a045wyx" target="_blank">EditorBrowsableAttribute</a>(<a href="https://msdn2.microsoft.com/en-us/library/3adcxf3z" target="_blank">EditorBrowsableState</a>.Never)]
<span class="keyword">public</span> <span class="keyword">delegate</span> TResult <span class="identifier">Func</span>&lt;T1, T2, T3, T4, T5, TResult&gt;(
	T1 <span class="parameter">arg1</span>,
	T2 <span class="parameter">arg2</span>,
	T3 <span class="parameter">arg3</span>,
	T4 <span class="parameter">arg4</span>,
	T5 <span class="parameter">arg5</span>
)
</pre></td></tr></table></span><span codeLanguage="VisualBasicDeclaration"><table><tr><th>Visual Basic</th></tr><tr><td><pre xml:space="preserve">&lt;<a href="https://msdn2.microsoft.com/en-us/library/8a045wyx" target="_blank">EditorBrowsableAttribute</a>(<a href="https://msdn2.microsoft.com/en-us/library/3adcxf3z" target="_blank">EditorBrowsableState</a>.Never)&gt; _
<span class="keyword">Public</span> <span class="keyword">Delegate</span> <span class="keyword">Function</span> <span class="identifier">Func</span>(<span class="keyword">Of</span> T1, T2, T3, T4, T5, TResult) ( _
	<span class="parameter">arg1</span> <span class="keyword">As</span> T1, _
	<span class="parameter">arg2</span> <span class="keyword">As</span> T2, _
	<span class="parameter">arg3</span> <span class="keyword">As</span> T3, _
	<span class="parameter">arg4</span> <span class="keyword">As</span> T4, _
	<span class="parameter">arg5</span> <span class="keyword">As</span> T5 _
) <span class="keyword">As</span> TResult</pre></td></tr></table></span></div>



arg1<br>


Type:T1<br>



arg2<br>


Type:T2<br>



arg3<br>


Type:T3<br>



arg4<br>


Type:T4<br>



arg5<br>


Type:T5<br>



## Type Parameters




T1<br>


The type of the first parameter of the method that this delegate encapsulates

T2<br>


The type of the second parameter of the method that this delegate encapsulates

T3<br>


The type of the third parameter of the method that this delegate encapsulates

T4<br>


The type of the fourth parameter of the method that this delegate encapsulates

T5<br>


The type of the fifth parameter of the method that this delegate encapsulates

TResult<br>


Type of the return value of the method that this delegate encapsulates.




## See Also



 [Telerik.JustMock Namespace](n_telerik_justmock) 


