My_top utility fun version
===

 Implementation of simple using "execl" without clone main procces.
   -------------------------
   <p><p/>

<p>>Little guide: execl - function of library <unistd.h> <p/>
<p>  <br/>
<p>   first parameter: - path of executant file "/path/to/some/exec";<p/>
 <p> second parameter: - it's 'zero' argument of your exe (path to your exe)<p/>
<p>              	        in other words "argv[0]" of your executant file;<p/>
<p>   third parameter: - it's 'first' argument of your exe (if it's exist)<p/>
<p>		                     "argv[1]", if this arguments does not using in your exe<p/>
<p>		      	              this argument will be ignoring;<p/>
<p>   last parameter: - last parameter should be NULL/0 for order to show, that<p/>
<p>                   	 	previous argument was last;<p/>
<p><p/>
<p><p/>
<p>  ### Example:   execl("/path/to/exec", "exec", "first arg", NULL); ###<p/>




