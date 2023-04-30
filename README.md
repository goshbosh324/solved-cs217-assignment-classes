Download Link: https://assignmentchef.com/product/solved-cs217-assignment-classes
<br>
<h1 style="margin-left: 21.75pt;text-indent: 0in">Question: 1</h1>

<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 37.0pt"><b><span style="font-size: 10.0pt;line-height: 107%;font-family: 'Arial',sans-serif">1)</span></b> <b><span style="font-size: 9.5pt;line-height: 107%;font-family: 'Arial',sans-serif">Implementation of </span></b><b><span style="font-size: 11.5pt;line-height: 107%">Quadratic</span></b><b><span style="font-size: 9.5pt;line-height: 107%;font-family: 'Arial',sans-serif"> Polynomial Class </span></b>

<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span>

<p class="MsoNormal" style="margin: 0in 7.4pt .65pt 21.75pt">Write a class Polynomial. This class has three private data members

<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span>

<p class="MsoNormal" style="text-indent: -.25in;margin: 0in 7.4pt .65pt .25in"><!-- [if !supportLists]--><sub><span style="font-size: 18.5pt;line-height: 103%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">            </span></span></span></sub><!--[endif]-->a: Int that holds the coefficient of X^2<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="text-indent: -.25in;margin: 0in 7.4pt .65pt .25in"><!-- [if !supportLists]--><sub><span style="font-size: 18.5pt;line-height: 103%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">            </span></span></span></sub><!--[endif]-->b: Int that holds the coefficient of X<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="text-indent: -.25in;margin: 0in 7.4pt .65pt .25in"><!-- [if !supportLists]--><sub><span style="font-size: 18.5pt;line-height: 103%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">            </span></span></span></sub><!--[endif]-->c: A double that holds the coefficient of X^0 (Constant term)<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span>

<p class="MsoNormal" style="margin: 0in 7.4pt .65pt 21.75pt">The class has the following member functions.

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in .7pt 0in"><span> </span>

<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span>

<table class="TableGrid" style="width: 501.1pt;border-collapse: collapse" border="0" width="668" cellspacing="0" cellpadding="0">

 <tbody>

  <tr style="height: 14.15pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-bottom: none;padding: 0in 3.85pt 0in 0in;height: 14.15pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 11.5pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border-top: solid black 1.0pt;border-left: none;border-bottom: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 14.15pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Constructs a new Polynomial object to represent the</td>

  </tr>

  <tr style="height: 28.7pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.7pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Polynomial<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.7pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">quadratic Polynomial with all coefficients =0<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span> </span></td>

  </tr>

  <tr style="height: 13.4pt">

   <td style="width: 239.1pt;border-top: none;border-left: solid black 1.0pt;border-bottom: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.4pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 11.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.4pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Constructs a new Polynomial object to represent the</td>

  </tr>

  <tr style="height: 28.6pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.6pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Polynomial (a,b,c)<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.6pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">quadratic Polynomial<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span> </span></td>

  </tr>

  <tr style="height: 28.2pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.2pt" valign="bottom" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 9.5pt">getters/setters<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 6.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.2pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Write getter/setters for all members e.g. a,b,c<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in .4pt -.15pt"><span style="font-size: 5.5pt;line-height: 107%"><span> </span></span><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span style="font-size: 6.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.1pt" valign="bottom" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Polynomial(const<span>  </span>&amp; Copy)<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 6.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.1pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Copy Constructor<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in .55pt -.15pt"><span style="font-size: 5.5pt;line-height: 107%"><span> </span></span><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span style="font-size: 6.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.1pt" valign="bottom" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">operator =<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 6.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.1pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Overload = operator to assign values<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in .55pt -.15pt"><span style="font-size: 5.5pt;line-height: 107%"><span> </span></span><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span style="font-size: 6.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 20.05pt">

   <td style="width: 239.1pt;border: none;border-bottom: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 20.05pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">operator ==<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 2.5pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 20.05pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Overload == comparison operator<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><s><span style="font-size: 2.5pt;line-height: 107%"><span> </span></span></s></td>

  </tr>

  <tr style="height: 13.65pt">

   <td style="width: 239.1pt;border-top: none;border-left: solid black 1.0pt;border-bottom: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.65pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 11.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.65pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Overload + operator which takes two Polynomial</td>

  </tr>

  <tr style="height: 28.0pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.0pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Polynomial p3=p1+p2<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.0pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">object as argument. It preforms the addition and returns the result.</td>

  </tr>

  <tr style="height: 13.7pt">

   <td style="width: 239.1pt;border-top: none;border-left: solid black 1.0pt;border-bottom: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.7pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 11.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.7pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Overload – operator which takes two Polynomial</td>

  </tr>

  <tr style="height: 28.4pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.4pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Polynomial p3=p1-p2<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.4pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">object as argument. It preforms the subtraction and returns the result.</td>

  </tr>

  <tr style="height: 14.15pt">

   <td style="width: 239.1pt;border-top: none;border-left: solid black 1.0pt;border-bottom: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 14.15pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 262.0pt;border: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 14.15pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Overload * operator which takes an int as</td>

  </tr>

  <tr style="height: 28.5pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 28.5pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Polynomial<span>  </span>p2= p1*d<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 28.5pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">argument. It preforms the scaler multiplication and returns the result.</td>

  </tr>

  <tr style="height: 13.65pt">

   <td style="width: 239.1pt;border-top: none;border-left: solid black 1.0pt;border-bottom: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.65pt" valign="top" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 11.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border: none;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 13.65pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Returns a String representation of Quadratic</td>

  </tr>

  <tr style="height: 42.25pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 42.25pt" valign="bottom" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">operator string()<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 5.8pt .5pt"><span style="font-size: 5.5pt;line-height: 107%"><span> </span></span><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 42.25pt" valign="top" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Polynomial. Example<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 7.95pt">4X^2 + 3X + 2<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span> </span></td>

  </tr>

  <tr style="height: 36.25pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 36.25pt" valign="bottom" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">operator&lt;&lt;<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 9.5pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 36.25pt" valign="bottom" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Outputs the Polynomial<span>  </span>(Nonmember Function)<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span style="font-size: 9.5pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 36.35pt">

   <td style="width: 239.1pt;border: solid black 1.0pt;border-top: none;padding: 0in 3.85pt 0in 0in;height: 36.35pt" valign="bottom" width="319"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">operator&gt;&gt;<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 262.0pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 3.85pt 0in 0in;height: 36.35pt" valign="bottom" width="349"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.95pt">Input the Polynomial<span>  </span>(Nonmember Function)<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in -.15pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

 </tbody>

</table>

<p class="MsoNormal" style="text-indent: 0in;line-height: 90%;margin: 0in 482.15pt 3.9pt 0in"><span style="font-size: 10.0pt;line-height: 90%"><span>   </span></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 1.7pt 0in"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<h1 style="text-indent: -13.0pt;margin: 0in 0in 2.85pt 34.25pt"><!-- [if !supportLists]--><span style="line-height: 107%"><span>2)<span style="font: 7.0pt 'Times New Roman'">  </span></span></span><!--[endif]-->More Polynomial Methods</h1>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 2.05pt 0in"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="margin: 0in 7.4pt .65pt 21.75pt">Extend the Polynomial class to support the <i>evaluation</i> of quadratic polynomials as follows:

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in .8pt 0in"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="text-indent: -12.0pt;margin: 0in 7.4pt .65pt 52.0pt"><!-- [if !supportLists]--><span style="line-height: 103%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">     </span></span></span><!--[endif]-->Add a member function named <i>evaluate</i> that takes a single int argument representing the ‘<i>x</i>‘ value and returns the result (type double) of evaluating the polynomial at <i>x</i>.<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="text-indent: -12.0pt;margin: 0in 7.4pt .65pt 52.0pt"><!-- [if !supportLists]--><span style="line-height: 103%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">     </span></span></span><!--[endif]-->Add a void member function named roots that will take two <i>reference</i> arguments of type Complex (use your Complex class), then compute and provide <i>both</i> roots of a

<p class="MsoNormal" style="margin-left: 0in;text-indent: 0in"><sub><span style="font-size: 15.5pt;line-height: 103%"><span> </span><span>                    </span></span></sub>quadratic polynomial object. Recall that the roots are given by the quadratic equation:<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 150.8pt 0in 0in"><!-- [if gte vml 1]&gt;-->

<!-- [if !vml]--><img decoding="async" width="230" height="84" align="left" hspace="12" data-src="/Users/X1CARB~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="/Users/X1CARB~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg" width="230" height="84" align="left" hspace="12">

 </noscript><!--[endif]--><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 150.8pt 1.2pt 0in"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="margin: 0in 7.4pt .65pt 58.5pt">The expression under the radical is referred to as the <i>discriminant</i>. If the <i>discriminant</i> is negative, the roots must be expressed as imaginary values using Complex numbers as follows:

<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 129.1pt 0in 0in"><!-- [if gte vml 1]&gt;-->

<!-- [if !vml]--><img decoding="async" width="262" height="77" align="left" hspace="12" data-src="/Users/X1CARB~1/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="/Users/X1CARB~1/AppData/Local/Temp/msohtmlclip1/01/clip_image004.jpg" width="262" height="77" align="left" hspace="12">

 </noscript><!--[endif]--><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 129.1pt 0in 0in"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 1.0pt 0in"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="margin: 0in 25.25pt .65pt 58.5pt">The roots method should first determine if the roots are real or imaginary based on the value of the <i>discriminant</i>. If the roots are <i>real</i>, return them as complex values with the imaginary component set to zero, if the roots are <i>imaginary</i>, return them in complex form using the absolute value of the <i>discriminant</i>.

<h1 style="margin-left: 0in;text-indent: 0in"><span style="font-size: 11.0pt;line-height: 107%;font-family: 'Calibri',sans-serif;font-weight: normal"><span>         </span></span>Question: 2<sub><span style="font-size: 15.5pt;line-height: 107%;font-weight: normal"> <span>          </span></span></sub><span> </span></h1>

<p class="MsoNormal" style="margin: 0in 7.4pt .65pt 21.75pt">Write a class Matrix. This class has three private data members

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 2.65pt 22.0pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="text-indent: -.25in;margin: 0in 7.4pt .65pt 39.25pt"><!-- [if !supportLists]--><sub><span style="font-size: 18.5pt;line-height: 103%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">            </span></span></span></sub><!--[endif]-->rows: An integer that holds the numbers of rows for matrix.<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="text-indent: -.25in;margin: 0in 7.4pt .65pt 39.25pt"><!-- [if !supportLists]--><sub><span style="font-size: 18.5pt;line-height: 103%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">            </span></span></span></sub><!--[endif]-->columns: An integer that holds the numbers of columns for matrix.<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="text-indent: -.25in;line-height: 107%;margin: 0in 7.4pt 0in 39.25pt"><!-- [if !supportLists]--><sub><span style="font-size: 18.5pt;line-height: 107%;font-family: 'Arial',sans-serif"><span>•<span style="font: 7.0pt 'Times New Roman'">            </span></span></span></sub><!--[endif]-->matrix: An integer pointer to pointer that points to 2D array (rows x columns).<span style="font-family: 'Segoe UI Symbol',sans-serif"></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in .75pt 22.0pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="margin: 0in 7.4pt .65pt 21.75pt">The class has the following member functions.

<p class="MsoNormal" style="text-indent: 0in;line-height: 90%;margin: 0in 460.2pt .55pt 22.0pt"><span style="font-size: 10.0pt;line-height: 90%"><span>  </span></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 22.0pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<table class="TableGrid" style="width: 462.1pt;margin-left: 22.0pt;border-collapse: collapse" border="0" width="616" cellspacing="0" cellpadding="0">

 <tbody>

  <tr style="height: 26.75pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 26.75pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Matrix (int r, int c)<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 306.05pt;border: solid black 1.0pt;border-left: none;padding: 0in 5.15pt 0in 0in;height: 26.75pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Constructs a new Matrix object to represent the given matrix<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 14.05pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 14.05pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">operator =</td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 14.05pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload = operator to assign values</td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">operator ==<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="408"><p class="MsoNormal" style="text-align: justify;text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload == operator to compare whether matrices are equal or not</td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">d2=d1+1<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload + operator which takes integer as argument. It preforms scalar addition.</td>

  </tr>

  <tr style="height: 28.2pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">d2=d1-4<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload – operator which takes integer as argument. It preforms scalar subtraction.</td>

  </tr>

  <tr style="height: 28.2pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">d3=d1+d2<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload + operator which takes matrix object as argument. It adds two matrixes and returns the result.</td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">d3=d1-d2<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in .05pt 0in 5.05pt">Overload – operator which takes matrix object as argument. It subtracts two matrixes and returns the result.</td>

  </tr>

  <tr style="height: 25.8pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 25.8pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">d++<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 25.8pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload Post-increment Operator<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 25.7pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 25.7pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">++d<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 25.7pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload Pre-increment Operator<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 25.7pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 25.7pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">d–<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 25.7pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload Post-decrement Operator<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 25.8pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 25.8pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">–d<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 25.8pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload Pre-decrement Operator<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span></td>

  </tr>

  <tr style="height: 27.85pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 27.85pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Matrix d3=d1*d2;<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 27.85pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload * operator which takes matrix object as argument. It multiplies two matrixes and returns the result.</td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Matrix d3=d1*2;<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload * operator which takes matrix object as argument. It preforms scalar multiplication.</td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">Matrix d3=d1/2;<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in .75pt 0in 5.05pt">Overload / operator which takes matrix object as argument. It preforms scalar division.</td>

  </tr>

  <tr style="height: 28.2pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">double value= ~d2;<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Overload ~ operator which takes matrix object as argument. It gives determinant of matrix. (unary operator)</td>

  </tr>

  <tr style="height: 28.35pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.35pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">void setRows(int r)<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.35pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">It sets row of a matrix.<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span></td>

  </tr>

  <tr style="height: 28.2pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">int getRows()const<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Returns row of matrix.<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span></td>

  </tr>

  <tr style="height: 28.1pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">void setCol(int c)<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.1pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">It sets column of a matrix.<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span></td>

  </tr>

  <tr style="height: 28.2pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.5pt">int getCol()const<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in .5pt"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 28.2pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 5.05pt">Returns column of matrix.<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span></td>

  </tr>

  <tr style="height: 70.2pt">

   <td style="width: 156.05pt;border: solid black 1.0pt;border-top: none;padding: 0in 5.15pt 0in 0in;height: 70.2pt" valign="top" width="208"><p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 6.0pt">operator string()<p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span><p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span><p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span><p class="MsoNormal" style="margin: 0in;text-indent: 0in;line-height: 107%"><span> </span></td>

   <td style="width: 306.05pt;border-top: none;border-left: none;border-bottom: solid black 1.0pt;border-right: solid black 1.0pt;padding: 0in 5.15pt 0in 0in;height: 70.2pt" valign="top" width="408"><p class="MsoNormal" style="text-indent: 0in;line-height: 99%;margin: 0in 0in 2.1pt 4.55pt">Returns a String representation of matrix. Example 2X2 matrix<p class="MsoNormal" style="text-indent: 0in;line-height: 99%;margin: 0in 250.25pt .75pt 4.55pt">“2X2 1-2<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 4.55pt">3-4”</td>

  </tr>

 </tbody>

</table>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in 0in 22.0pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="text-indent: 0in;line-height: 107%;margin: 0in 0in .75pt 22.0pt"><span style="font-size: 10.0pt;line-height: 107%"><span> </span></span>

<p class="MsoNormal" style="margin: 0in 7.4pt .65pt 21.75pt">Write main function to test all the implemented functionality. (<i>Do not submit main function</i>)