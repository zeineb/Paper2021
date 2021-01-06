This paper is to be submitted to REFSQ.
I have taken an example of guideline "It is good practice to be responsible for freeing all resources you allocate and to be consistent with how and where you free memory in a function. If you allocate memory that you intend to free upon completion of the function, you must be sure to free the memory at all exit points for that function including error conditions."
I found it interesting as it points to the resource release issue, and I have seen a lot of reported issues by different tools such as Fortify.
