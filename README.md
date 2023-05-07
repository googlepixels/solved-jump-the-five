Download Link: https://assignmentchef.com/product/solved-jump-the-five
<br>
<a href="https://www.youtube.com/playlist?list=PLhOuww6rJJNNd1Mbu3h6SGfhD-8rRxLTp" rel="nofollow">https://www.youtube.com/playlist?list=PLhOuww6rJJNNd1Mbu3h6SGfhD-8rRxLTp</a>

Write a program that will encode any number in a given string using an algorightm to “jump the five” on a standard US telephone keypad such that “1” becomes “9,” “4” becomes “6,” etc. The “5” and the “0” will swap with each other. Here is the entire substitution table:

<pre><code>1 =&gt; 92 =&gt; 83 =&gt; 74 =&gt; 65 =&gt; 06 =&gt; 47 =&gt; 38 =&gt; 29 =&gt; 10 =&gt; 5</code></pre>

Encode only the numbers and leave all other text alone:

<pre><code>$ ./jump.py 867-5309243-0751</code></pre>

If given no arguments, present a brief usage:

<pre><code>$ ./jump.pyusage: jump.py [-h] strjump.py: error: the following arguments are required: str</code></pre>

Respond to <code>-h</code> or <code>--help</code> with a longer usage:

<pre><code>$ ./jump.py -husage: jump.py [-h] strJump the Fivepositional arguments:  str         Input textoptional arguments:  -h, --help  show this help message and exit</code></pre>

Run the test suite to ensure your program is working correctly:

<pre><code>$ make testpytest -xv test.py============================= test session starts ==============================...collected 4 itemstest.py::test_exists PASSED                                              [ 25%]test.py::test_usage PASSED                                               [ 50%]test.py::test_01 PASSED                                                  [ 75%]test.py::test_02 PASSED                                                  [100%]============================== 4 passed in 0.53s ===============================</code></pre>