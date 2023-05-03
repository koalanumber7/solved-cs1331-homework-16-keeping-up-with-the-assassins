Download Link: https://assignmentchef.com/product/solved-cs1331-homework-16-keeping-up-with-the-assassins
<br>
<h1>Problem Description</h1>

Assassins is a live-action game in which players try to eliminate each other using mock weapons in an effort to become the last surviving player.

This game is popular on college campuses and is played by thousands of students all over the world. Game hosts start a round by assigning each player a unique target. Every player has target and are themselves a target for someone else. When a player eliminates a target, usually by marking them with a pen or some tape, they get their victim’s target. The game ends when there is only one player remaining.

This sort of behavior can be modeled with a linked list! To be exact, this scenario requires a circularly linked list (as every player has a target and is a target), but for the sake of this homework we will <strong>ONLY be asking you to implement a regular doubly linked list</strong>.

<h1>Solution Description</h1>

Fill out the class called MyLinkedList.java that contains your doubly linked list implementation. We have provided an interface, SimpleList.java, that MyLinkedList.java must implement. <strong>Look at the descriptions in </strong><strong>SimpleList.java to understand what each method requires. </strong>You may create additional methods and fields for your linked list as needed.

Your linked list must use the provided Node inner class to implement the list, and must update both the head and tail fields when appropriate.

<h1>Testing</h1>

For this assignment you will be expected to rigorously test your linked list implementation. We encourage you to write your own tester class and test various edge cases. Here is an example tester class:

<table width="632">

 <tbody>

  <tr>

   <td width="632"><strong>public class </strong>Test { <strong>public </strong>static void main(String[] args){MyLinkedList&lt;Integer&gt; mll = <strong>new </strong>MyLinkedList&lt;&gt;(); <strong>for </strong>(int i = 0; i &lt; 10; i++) { mll.add(i);}<strong>for </strong>(int i = 0; i &lt; 10; i++) {System.out.println(mll.get(i)); }}}</td>

  </tr>

 </tbody>

</table>

You have also been provided with a tester file called Tester.java which contains more simple tests of every method.

<h1>Rubric</h1>

<ul>

 <li>[20] add(int index, E element)

  <ul>

   <li>[3] Correctly throws exceptions</li>

   <li>[17] Functionality</li>

  </ul></li>

 <li>[12] add(E element)

  <ul>

   <li>[2] Correctly throws exceptions</li>

   <li>[10] Functionality</li>

  </ul></li>

 <li>[12] get(int index)

  <ul>

   <li>[2] Correctly throws exceptions</li>

   <li>[10] Functionality</li>

  </ul></li>

 <li>[12] remove(int index)

  <ul>

   <li>[2] Correctly throws exceptions</li>

   <li>[10] Functionality</li>

  </ul></li>

 <li>[12] removeElement(E element)

  <ul>

   <li>[2] Correctly throws exceptions</li>

   <li>[10] Functionality</li>

  </ul></li>

 <li>[12] contains(E element)

  <ul>

   <li>[2] Correctly throws exceptions</li>

   <li>[10] Functionality</li>

  </ul></li>

 <li>[5] isEmpty()</li>

 <li>[5] clear()</li>

 <li>[5] size()</li>

 <li>[5] toArray()</li>

</ul>

<strong>Import Restrictions</strong>

You may not import anything for this homework assignment.

<h1>Feature Restrictions</h1>

There are a few features and methods in Java that overly simplify the concepts we are trying to teach or break our auto grader. For that reason, do not use any of the following in your final submission:

<ul>

 <li>var (the reserved keyword)</li>

 <li>exit</li>

</ul>

<ul>

 <li></li>

</ul>