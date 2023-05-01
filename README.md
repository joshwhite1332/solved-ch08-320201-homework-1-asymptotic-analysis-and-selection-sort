Download Link: https://assignmentchef.com/product/solved-ch08-320201-homework-1-asymptotic-analysis-and-selection-sort
<br>
<strong>Problem 1: Asymptotic Analysis                                                                                                                       </strong>

Considering the following pairs of functions f and g, show for each pair whether <em>f </em>∈ Θ(<em>g</em>), <em>f </em>∈ <em>O</em>(<em>g</em>), <em>f </em>∈<em>o</em>(<em>g</em>), <em>f </em>∈ Ω(<em>g</em>), <em>f </em>∈<em>ω</em>(<em>g</em>), <em>g</em>∈ Θ(<em>f</em>), <em>g</em>∈<em>O</em>(<em>f</em>), <em>g</em>∈<em>o</em>(<em>f</em>), <em>g</em>∈ Ω(<em>f</em>), or <em>g</em>∈<em>ω</em>(<em>f</em>).

<ul>

 <li><em>f</em>(<em>n</em>) = 3<em>n </em>and <em>g</em>(<em>n</em>) = <em>n</em><sup>3</sup>.</li>

</ul>

√

<ul>

 <li><em>f</em>(<em>n</em>) = 7<em>n</em><sup>0<em>.</em>7 </sup>+ 2<em>n</em><sup>0<em>.</em>2 </sup>+ 13log<em>n </em>and <em>g</em>(<em>n</em>) = <em>n</em>.</li>

 <li><em>f</em>(<em>n</em>) = <em>n</em><sup>2</sup><em>/</em>log<em>n </em>and <em>g</em>(<em>n</em>) = <em>n</em>log<em>n</em>.</li>

 <li><em>f</em>(<em>n</em>) = (log(3<em>n</em>))<sup>3 </sup>and <em>g</em>(<em>n</em>) = 9log<em>n</em>.</li>

</ul>

<strong>Problem 2: Selection Sort                                                                                                                                  </strong>

In class, we discussed Insertion Sort. Selection Sort is similar to Insertion Sort and works as follows. Given an array of elements, you always take the current element and exchange it with the smallest element that can be found on the right hand side of the current element. In doing so, you will gradually build up a sorted list on the left side (just as in Insertion Sort), and in each iteration “attach” the smallest element from the remaining unsorted right side to it.

<ul>

 <li><em>Implement </em>Selection Sort.</li>

 <li>Show that Selection Sort is correct (consider the loop invariant).</li>

 <li>Generate random input sequences of length <em>n </em>as well as sequences of length <em>n </em>that represent the worst case and the best case for the Selection Sort algorithm. Briefly describe how you generated the sequences (e.g. programmatically with a random sequence generator).</li>

 <li>Run the algorithm on sequences of (c) with length <em>n </em>for increasing values of <em>n </em>and measure the computation times. Plot curves that show the computation time of the algorithm in the best, average, and worst case for increasing input length <em>n</em>. Note that in order to compute reliable measurements for the average case, you have to run the algorithm multiple times for each entry in your plot. You can use whatever plotting method you like (R, Matlab, Excel, by hand, …).</li>

 <li>Interpret the plots in (d) with respect to asymptotic behavior and constants.</li>

</ul>