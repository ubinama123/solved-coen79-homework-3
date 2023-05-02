Download Link: https://assignmentchef.com/product/solved-coen79-homework-3
<br>
<ol>

 <li>The sequence’s insert member function normally puts a new item before the current item. What does insert do if there is no current item?</li>

</ol>






















<ol start="2">

 <li>Modify the following code to generate the given output. Do not modify the main</li>

</ol>










<strong>Output: </strong>

<strong>Number of box objects created so far: 1</strong>

<strong>Number of box objects created so far: 2</strong>








































<ol start="3">

 <li>In the following code, indicate if the selected lines are legal or illegal:</li>

</ol>




#include &lt;iostream&gt;




class small { public:     small( ) {size = 0;};     void k() const;     void h(int i);     friend void f(small z);

private:

int size;

};




void small::k() const

{     small x, y;     x = y; // LEGAL/ILLEGAL?

x.size = y.size; // LEGAL/ILLEGAL?

x.size = 3; // LEGAL/ILLEGAL?

};  void small::h(int i)

{




};  void f(small z)

{     small x, y;     x = y; // LEGAL/ILLEGAL?

x.size = y.size; // LEGAL/ILLEGAL?

x.size = 3; // LEGAL/ILLEGAL?

x.h(42); // LEGAL/ILLEGAL?

};




int main() {          small x, y;     x = y; // LEGAL/ILLEGAL?

x.size = y.size; // LEGAL/ILLEGAL?

x.size = 3; // LEGAL/ILLEGAL?

x.h(42); // LEGAL/ILLEGAL?

return 0;

}

























<ol start="4">

 <li>We create an array of fruit in the main How can we make sure that for all the items in array fruit_ptr the values of weight and color are equal to 1 and 2, respectively? Please show your solution. Do not modify the main function.</li>

</ol>































<ol start="5">

 <li>Explain why<em> heap</em> variables are essentially global in scope. Please present an example as well.</li>

</ol>























































<ol start="6">

 <li>Is it possible to use the keyword “this” inside a friend function? Please explain your answer.</li>

</ol>




























<ol start="7">

 <li>Does the following code compile? Does it run? Is there any problem with the code? If yes, how do you fix it?</li>

</ol>




<table width="653">

 <tbody>

  <tr>

   <td colspan="2" width="653">19.         cout &lt;&lt; “Employee::foo()”;</td>

  </tr>

  <tr>

   <td colspan="2" width="653">20.         c -&gt; process();</td>

  </tr>

  <tr>

   <td colspan="2" width="653">21.     }</td>

  </tr>

  <tr>

   <td colspan="2" width="653">22. };   23.</td>

  </tr>

  <tr>

   <td colspan="2" width="653">24. <strong>int</strong> main() {</td>

  </tr>

  <tr>

   <td colspan="2" width="653">25.     Employee ob;</td>

  </tr>

  <tr>

   <td colspan="2" width="653">26.     ob.foo();</td>

  </tr>

  <tr>

   <td colspan="2" width="653">27.     <strong>return</strong> 0;</td>

  </tr>

  <tr>

   <td colspan="2" width="653">28. }</td>

  </tr>

  <tr>

   <td width="25"> </td>

   <td width="628"> </td>

  </tr>

 </tbody>

</table>


