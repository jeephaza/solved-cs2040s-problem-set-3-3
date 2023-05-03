Download Link: https://assignmentchef.com/product/solved-cs2040s-problem-set-3-3
<br>
<strong>Problem 3.           (The CS2040S Detectives)</strong>

We have six impostors on ours hands. Each <em>claims </em>to be <strong>Mr. QuickSort</strong>, the most popular sorting algorithm around. However, only one of these six is telling the truth. Four of the other five are just harmless imitators, <strong>Mr. BubbleSort</strong>, <strong>Ms. SelectionSort</strong>, <strong>Mr. InsertionSort</strong>, and <strong>Ms. MergeSort</strong>. Beware, however, one of the impostors is <em>not a sorting algorithm</em>! <strong>Dr. Evil </strong>maliciously returns unsorted arrays! And he won’t be easy to catch. He will try to trick you by often returning correctly sorted arrays. Especially on easy instances, he’s not going to slip up.

Your job is to investigate, and identify who is who and what is what. Attached to this problem set, you will find six sorter implementations: (i)SorterA.class, (ii)SorterB.class, (iii)SorterC.class, (iv)SorterD.class, (v)SorterE.class, and (vi)SorterF.class.

These are provided in a single JAR file: Sorters.jar. Each of these class files contains a class that implements the ISort interface which supports the following method:

public void sort(KeyValuePair[] array);

You can find the code for the KeyValuePair class attached as well. it is a simple container that holds two integers: a key and a value. The sort routines will sort the array of objects by key.

You can test these sorting routines in the normal way: create an array, create a sorter object, and sort. See the example file SortTestExample.java.

You can then use the StopWatch to measure how fast each of these sorting routines runs. Each sorting algorithm has some inputs on which it is fast, and some inputs on which it is slow. Some sorting algorithms are stable, and others are not. Using these properties, you can figure out the real identities of the sorters, and also identify Dr. Evil.

Beware, however, that these characters can be deceptive. While they cannot hide their <em>asymptotic running time</em>, they may well choose to run consistently slower than you expect. (For example, you should not assume that QuickSort is always the fastest.) Evidence based on comparison of runtime across different sorters will not be accepted. Only evidence based on <em>asymptotic running time </em>are valid.

<strong>IntelliJ tips:           </strong>Refer to <em>setup.mp4 </em>on Coursemology for instructions on setting up PS3 in IntelliJ.

<strong>Problem 3.a. </strong>Write a routine boolean checkSort(ISort sorter, int size) that runs a test on an array of the specified size to determine if the specified sorting algorithm sorts correctly.

<strong>Problem 3.b. </strong>Write a routine boolean isStable(ISort sorter, int size) that runs a test on an array of the specified size to determine if the specified sorting algorithm is stable.

<strong>Problem 3.c. </strong>Write whatever additional code you need in order to test the sorters to determine which is which. All evidence you give below you rely on properties of the sorting algorithms, along with data from your tests that supports your claim.

<table width="624">

 <tbody>

  <tr>

   <td width="109"><strong>Problem 3.d.</strong></td>

   <td width="515">What is the true identity of SorterA? Give the evidence that proves your claim.</td>

  </tr>

  <tr>

   <td width="109"><strong>Problem 3.e.</strong></td>

   <td width="515">What is the true identity of SorterB? Give the evidence that proves your claim.</td>

  </tr>

  <tr>

   <td width="109"><strong>Problem 3.f.</strong></td>

   <td width="515">What is the true identity of SorterC? Give the evidence that proves your claim.</td>

  </tr>

  <tr>

   <td width="109"><strong>Problem 3.g.</strong></td>

   <td width="515">What is the true identity of SorterD? Give the evidence that proves your claim.</td>

  </tr>

  <tr>

   <td width="109"><strong>Problem 3.h.</strong></td>

   <td width="515">What is the true identity of SorterE? Give the evidence that proves your claim.</td>

  </tr>

  <tr>

   <td width="109"><strong>Problem 3.i.</strong></td>

   <td width="515">What is the true identity of SorterF? Give the evidence that proves your claim.</td>

  </tr>

 </tbody>

</table>


