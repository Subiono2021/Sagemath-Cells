<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">

    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">


<meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.3/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>


<link rel="stylesheet" type="text/css" href="https://sagecell.sagemath.org/static/sagecell_embed.css">

    <title>SageMathCell</title>
	<script src="https://github.com/sagemath/sagecell.git"></script>
    <script src="https://sagecell.sagemath.org/static/embedded_sagecell.js"></script>
	<script type="text/javascript" src="https://sagecell.sagemath.org/static/jquery.max.js"></script>
    <script type="text/javascript" src="https://sagecell.sagemath.org/static/embedded_sagecell.js"></script>
    <script type="text/javascript" src="sagecell.js"></script>
    <script type="text/javascript" src="sage-text.js"></script>
    <script type="text/javascript" src="ganalytics.js"></script>
    <script type="text/javascript" src="https://apis.google.com/js/plusone.js"></script>
	<link rel="stylesheet" type="text/css" href="https://sagecell.sagemath.org/static/sagecell_embed.css">
	
	
	
	
    <script>
    // Make the div with id 'mycell' a Sage cell
    sagecell.makeSagecell({inputLocation:  '#mycell',
                           template:       sagecell.templates.minimal,
                           evalButtonText: 'Enable'});
    // Make *any* div with class 'compute' a Sage cell
    sagecell.makeSagecell({inputLocation: 'div.compute',languages: ["sage","gap","gp","html","maxima","octave","python", "r"], evalButtonText: 'Evaluate'});
    </script>

    <script>
    // Make the div with id 'selsaya' a Sage cell
    sagecell.makeSagecell({inputLocation:  '#selsaya',
                           template:       sagecell.templates.minimal,
                           evalButtonText: 'Enable'});
    // Make *any* div with class 'compute' a Sage cell
    sagecell.makeSagecell({inputLocation: 'div.compute',languages: ["sage","gap","gp","html","maxima","octave","python", "r"], evalButtonText: 'Evaluate'});
    </script>


    <script>
    // Make the div with id 'Sisthom' a Sage cell
    sagecell.makeSagecell({inputLocation:  '#Sisthom',
                           template:       sagecell.templates.minimal,
                           evalButtonText: 'Enable'});
    // Make *any* div with class 'compute' a Sage cell
    sagecell.makeSagecell({inputLocation: 'div.compute',languages: ["sage","gap","gp","html","maxima","octave","python", "r"], evalButtonText: 'Evaluate'});
    </script>


    <script>
    // Make the div with id 'Intent' a Sage cell
    sagecell.makeSagecell({inputLocation:  '#Intent',
                           template:       sagecell.templates.minimal,
                           evalButtonText: 'Enable'});
    // Make *any* div with class 'compute' a Sage cell
    sagecell.makeSagecell({inputLocation: 'div.compute',languages: ["sage","gap","gp","html","maxima","octave","python", "r"], evalButtonText: 'Evaluate'});
    </script>
	
	<script>
    // Make the div with id 'Intent' a Sage cell
    sagecell.makeSagecell({inputLocation:  '#taylor',
                           template:       sagecell.templates.minimal,
                           evalButtonText: 'Enable'});
    // Make *any* div with class 'compute' a Sage cell
    sagecell.makeSagecell({inputLocation: 'div.compute',languages: ["sage","gap","gp","html","maxima","octave","python", "r"], evalButtonText: 'Evaluate'});
    </script>



  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>MathJax example</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
          src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
  <script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  }
};
</script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js">
</script>


<link rel="stylesheet" type="text/css" href="https://tikzjax.com/v1/fonts.css">
<script src="https://tikzjax.com/v1/tikzjax.js"></script>

<!-- Additional CSS customizations --> 
<style type="text/css"></style>


<style>
  /* Basic styling */
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0.0;
  }
  .navbar {
    height: 100vh; /* Full height */
    width: 200px; /* Adjust width as needed */
    background-color: #233; /* Navbar background color */
    position: fixed; /* Fix it on the screen */
    left: 0;
    top: 0;
    overflow-x: hidden; /* Hide horizontal scrollbar */
    padding-top: 50px; /* Space at the top */
  }
  .navbar a {
    padding: 10px; /* Padding for links */
    text-decoration: none; /* Remove underline */
    display: block; /* Make links block level */
    color: white; /* Text color */
  }
  .dropdown-content {
    display: none; /* Hide dropdown content by default */
    background-color: #512; /* Dropdown background color */
  }
  /* Show dropdown content when hovering over dropdown */
  .dropdown:hover .dropdown-content {
    display: block;
  }
</style>

<style>
/* Custom styling for horizontal lines */
.horizontal-line {
  border: none;
  height: 8px; /* Adjust the height of the line */
  background-color: #3b06ad; /* Change the color of the line */
  margin-left:220px; /* Adjust the left margin  as needed */
  margin-right:20px; /* Adjust the right margin  as needed */
}
</style>


<style>
.tooltip {
  position: relative;
  display: inline-block;
  border-bottom: 1px dotted black;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 200px;
  background-color: blue;
  color: #fff;
  text-align: justify;
  border-radius: 6px;
  padding: 5px;

  /* Position the tooltip */
  position: absolute;
  z-index: 5;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
}
</style>

<style>
  .hidden {
    display: none;
  }
</style>


<style>
.tooltip1 {
  position: relative;
  display: inline;
  border-bottom: 1px dotted black;
}

.tooltip1 .tooltiptext {
  visibility: hidden;
  width: 250px;
  background-color: blue;
  color: #fff;
  text-align: justify;
  border-radius: 10px;
  padding: 10px;
  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  top: 100%;
  left: 60%;
  margin-left: -60px;
}

.tooltip1:hover .tooltiptext {
  visibility: visible;
}

p.ex1 {
  margin-left: 200px; margin-right: 50px;
}
</style>


<style>
.tooltip2 {
  position: relative;
  display: inline;
  border-bottom: 1px dotted black;
}

.tooltip2 .tooltiptext {
  visibility: hidden;
  width: 200px;
  background-color: blue;
  color: #fff;
  text-align: justify;
  border-radius: 10px;
  padding: 10px;
  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  top: 100%;
  left: 60%;
  margin-left: -60px;
}

.tooltip2:hover .tooltiptext {
  visibility: visible;
}

p.ex1 {
  margin-left: 200px; margin-right: 50px;
}
</style>


<style>
.tooltip3 {
  position: relative;
  display: inline;
  border-bottom: 1px dotted black;
}

.tooltip3 .tooltiptext {
  visibility: hidden;
  width: 350px;
  background-color: blue;
  color: #fff;
  text-align: justify;
  border-radius: 10px;
  padding: 10px;
  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  top: 100%;
  left: 60%;
  margin-left: -60px;
}

.tooltip3:hover .tooltiptext {
  visibility: visible;
}

p.ex1 {
  margin-left: 200px; margin-right: 50px;
}
</style>

<style>
blockquote {
  margin: 20px;
  padding: 10px;
  border-left: 5px solid #ccc;
  background-color: #0ad36b;
  font-style: italic;
  overflow-y: auto; /* Aktifkan scrollbar vertikal jika konten melebihi tinggi maksimum */
  text-align: justify; /* Ratakan teks */
}
</style>

</head>
<body>
<div style="background-color:powderblue;border-style:solid double;border-width:7px;margin-left:220px;margin-right:20px;">
<center>
<h2><div class="w3-panel w3-red"><center><b><marquee behavior="scroll" direction="left">Embedded SageMath Cell and  Jupyter Notebooks</marquee></b></center></div></h2>
<h4>
Laboratory of <b>A</b>nalysis, <b>A</b>lgebra and <b>M</b>athematical learning
<br>
Department of Mathematics-ITS
</h4>
</center>
</div>
<hr class="horizontal-line">
<br>
<div class="navbar">
  <a href="https://www.its.ac.id/matematika/en/lecturer-and-staff/list-of-lecturers/subiono/" target="blank">Home</a>
  <div class="dropdown">
    <a href="#kembali">Table of contents</a>
    <div class="dropdown-content">
      <a href="#Pend">Introduction</a>
	  <a href="#DatSut">Data Structures</a?>
      <a href="#InInt">Indefinite Integral</a>
      <a href="#Latihan">Exercises!</a>
      <a href="#DefInt">Definite Integral</a>
      <a href="#Non-HSE">Non-Homogeneous System of Equations</a>
      <a href="#Cy-ani">Cycloid Animation</a>
      <a href="#UYPCM">Using Your Personal Computer in Math: Powerful Tools and Applications</a>
      <a href="#CGASagM">Cayley graph of an Abelian group using SageMath</a>
      <a href="#SagMathfP">SageMath cell for practice!</a>
	  <a href="#JupNot">Jupyter Notebook</a>
    </div>
  </div>
</div> 

<section id="Pend">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>
    1. Introduction
  </h2>
  <hr class="horizontal-line"> 
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Cloud computing is the on-demand availability of computer system resources, primarily data 
  storage (cloud storage) and computing power, without direct active management by the user. 
  Large clouds are often distributed across multiple locations, each of which is a data center. 
  Cloud computing relies on resource sharing to achieve coherence and typically uses a pay-per-use 
  model, which can help reduce capital expenditures but can also lead to unexpected operating 
  costs for users.
  <br>
  <br>
  A wide range of free cloud computing resources, such as Colab and Jupyter Notebooks, are 
  available. We should leverage these resources to enhance the learning process, particularly in 
  the field of education. This presents a paradigm shift for educators, allowing them to adapt to 
  the era of artificial intelligence. The development of quantum computing further bolsters this 
  shift. As a result, processing large datasets and information will become significantly easier 
  and faster in the future, leading to more accurate outcomes compared to existing methods.
  </p>
<hr class="horizontal-line">
  <div class="subsection">
    <h3 style='text-align: justify;margin-left:220px;margin-right:25px;'>1.1. OBJECTIFITY</h3>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  These SageMath Cells and Jupyter Notebooks serve as dedicated teaching aids for the mathematics department at the Sepuluh Nopember Institute of Technology (ITS). They provide a platform to showcase how ITS mathematics students can bridge the gap between theoretical knowledge and practical applications. By performing calculations based on mathematical reasoning, students can simultaneously verify their understanding of mathematical concepts.
  <br>
  <br>
  Furthermore, students can validate the mathematical ideas they have studied by utilizing their programming skills in languages like <b>Sage, Gap, GP</b>, and <b>Maxima</b>, all of which are specifically designed for symbolic mathematics. Numerical validation can also be facilitated by languages like <b>R</b> and <b>Python</b>.. All resources and computations are conveniently cloud-based.
 <blockquote style='text-align: justify;margin-left:345px;margin-right:125px;'>
 Whoever follows the road of knowledge-seeking, <b style="font-size:28px"> الله </b> will facilitate his journey to <b style="font-size:26px"> جَنَّة </b>.
 </blockquote>
 </p>
 <div>
 <hr class="horizontal-line">
  <div class="subsection">
    <h3 style='text-align: justify;margin-left:220px;margin-right:25px;'>
      1.2. About SageMath
    </h3>
 <hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  A free and open-source mathematical software package with an emphasis on computer algebra is called SageMath. "Embedded SageMath Cell" refers to SageMath programme cells that can be put into other programmes because SageMath can be embedded in other programmes.
  <br>
  <br>
  Sagemath is useful for a variety of mathematical problems, such as:
  </p>
  <ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
  <li>Symbolic and numerical computation</li>
  <li>Algebra</li>
  <li>Calculus</li>
  <li>Differential equations</li>
  <li>Numerical analysis</li>
  <li>Statistics</li>
  <li>Optimization</li>
  <li>Graphing</li>
  <li>Programming</li>
  <li>SageMath Features</li>
  </ul>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Among the many characteristics of Sagemath are the following:
  </p>
  <ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
  <li>A powerful and flexible syntax</li>
  <li>A large library of mathematical functions</li>
  <li>An extensive documentation</li>
  <li>A vibrant community of users and developers</li>
  <li>SageMath Applications</li>
  </ul>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  SageMath has several uses, some of which are as follows:
  </p>
  <ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
  <li>Mathematical research</li>
  <li>Education</li>
  <li>Engineering</li>
  <li>Science</li>
  <li>Finance</li>
  <li>Business</li>
  </ul>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  A SageMath feature called "Embedded SageMath Cell" enables users to embed SageMath code in other documents, such Jupyter notebooks. This saves users from having to launch Sagemath (an interactive application) and use it as a calculator by enabling them to run SageMath code directly within the text. Furthermore, we can execute <b>python</b> code in SageMath Cell, including <b>sympy</b> (symbolic python), <b>numpy</b> (numerical python), <b>scipy</b> (scientific python), and so on.
  </p>

<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
<b>SageMath</b> is introduced in this section. "System for Algebra and Geometry Experimentation" was the original name of SAGE. Currently using SageMath. Its goal is to be a strong free open source substitute for open source <b>MAPLE</b>, <b>MATHEMATICA</b>, and <b>MATLAB</b>. It is free software, licenced under the <b>GPL</b>. SageMath is constructed upon numerous open source packages that already exist: The URL <a href="https://numpy.org/" target="_blank"><b>NumPy</b></a>, <a href="https://scipy.org/" target="_blank"><b>SciPy</b></a>, <a href="https://matplotlib.org/" target="_blank"><b>matplotlib</b></a>, <a href=" https://www.sympy.org/en/index.html" target="_blank"><b>Sympy</b></a>, <a href="https://maxima.sourceforge.io/" target="_blank"><b> Maxima</b></a>, <a href="https://www.gap-system.org/" target="_blank"><b>GAP</b></a>, <a href="https://www.flintlib.org/" target="_blank"><b>FLINT</b></a>, <a href="https://www.r-project.org/" target="_blank"><b>R</b></a> and <a href="https://www.sagemath.org/links-components.html" target="_blank">many others</a>. Through an interface or wrapper, or directly through a common Python-based language, you can access their combined strength.
<br>
<br>
SageMath includes a large number of excellent open-source mathematical software programmes. Calculus, number theory (beginning to advanced), cryptography, commutative algebra, group theory, graph theory, exact and numerical linear algebra, and many more mathematical topics can all be discussed using the open-source SageMath programme. Furthermore, SageMath features interactive programmes that are simple to comprehend and, consequently, to construct, as well as graphical animations and capabilities. As a result, it will be highly beneficial for learning, particularly for maths. SageMath 10.2 is the most recent version, and it was released on December 3, 2023.
<br>
<br>
Python is the programming language utilised in SageMath. It was initially introduced by mathematician <b>William Stein</b> of the University of Washington, Seattle, who oversaw the development of SageMath.
<br>
<br>
<b><mark>History and Development of SageMath</mark></b><br>
The original intention behind the publication of SageMath's first edition, which was free and open-source software released under the GNU General Public Licence version 3, was to provide a "open source alternative to Magma, Maple, Mathematica, and MATLAB". Mathematical problems in algebra, number theory, geometry, and combinatorics can be resolved with the Magma computer algebra system. The programme, which is called after the algebraic structure magma, is compatible with both Windows and Unix-like operating systems. <a href="https://en.wikipedia.org/wiki/Magma_(computer_algebra_system)" target="_blank">[Magma]</a> is closed source software even if it is not non-commercial software (cost recovery, non-commercial proprietary). University of Washington mathematician William Stein is the creator and director of the SageMath project.
<br>
<br>
When creating SageMath, William Stein discovered that a number of open-source mathematical software packages—written in <b>C, C ++, Common Lisp, Fortran</b>, and <b>Python</b>—had already been developed in other languages.
<br>
<br>
Instead of creating the wheel, SageMath (primarily developed in Python and Cython) unifies a variety of specialised mathematical software products into a single interface that requires no programming knowledge beyond Python. Nevertheless, the hundreds of thousands of lines of original code that make up SageMath bring new functionality and provide the interface between its parts.
<br> 
<br>
Professionals and students alike work on developing <b>SageMath</b>. Grants and volunteer labour are used to fund the development of SageMath. Still, the first full-time SageMath developer wasn't hired until 2016 (thanks to an EU grant). The same year, Stein expressed his dissatisfaction with the dearth of university financing and certification programmes for software development, stating this as the rationale behind his choice to resign from his academic post and devote all of his time to the project at a recently established business, SageMath, Inc. Sagemath's official website, <a href="https://www.sagemath.org/" target="_blank">[SageMath]</a>, and <a href="https://en.wikipedia.org/wiki/SageMath" target="_blank">[WikiSageMath]</a> provide comprehensive material and can be used as a resource.
<br> 
<br>  
SageMath is a powerful software programme for studying a wide range of mathematical topics, including calculus, number theory (from elementary to advanced), cryptography, commutative algebra, group theory, graph theory, and both precise and numerical linear algebra. It can also generate user-friendly visualizations like images, animations, and interactive programs. This makes SageMath a valuable tool for learning mathematics, especially for visual learners. The SageMath Cell Server provides access to the latest version of SageMath. You can check the specific version by typing the command <code>version()</code> within a cell. For more information on SageMath development, please refer to <a href="https://www.sagemath.org/development.html" target="_blank">[SageMath Development]</a>. Based on the knowledge we given here, we took the initiative to construct the <b>SageMath-ITS Cell</b>. Computations can be done using <b>Sage, Gap, GP, HTML, Maxima, Octave, Python</b>, and <b>R</b> programming languages.
<br>
<br>
The Sage command line has a sage prompt in the input cell. If you are using a Sage notebook (the available input box), type, for example, <code>5+21</code> in the input box cell, and click the Evaluate button to calculate the corresponding output.
<br>
<br>
To calculate the power of a number, type the following in the input cell: <code>123**1245</code>, which calculates \(123^{1245}\). Please try it by typing the input on line 2 and then clicking the Evaluate button. To find out the version of SageMath you are currently using, type <code>version()</code> on line \(3\) of the input, and then click the Evaluate button. Then copy and paste the following command on the next input line:
<br>
<code>
%display latex<br>
A=matrix([[1,2], [3,4]])<br>
print("A = ") <br>
A
</code>
<br>
to display a matrix \(A=\left(\begin{array}{rr}
1 & 2 \\
3 & 4
\end{array}\right)\) of size \(2\times 2\). To determine the inverse of \(A\), which is \(B=A^{-1}=\left(\begin{array}{rr}
-2 & 1 \\
\frac{3}{2} & -\frac{1}{2}
\end{array}\right)\) copy and paste the following command:<br>
<code>
print("B =")<br>
A^-1
</code><br>
Copy and paste the following commands one by one:<br>
<code>
print("AB = ")<br>
A*A^-1
</code><br>
and <br>
<code>
print("BA =")<br>
A^-1*A
</code>
<br>
It can be seen that matrix \(A=\left(\begin{array}{rr}
1 & 2 \\
3 & 4
\end{array}\right)\) has invers \(B=\left(\begin{array}{rr}
-2 & 1 \\
\frac{3}{2} & -\frac{1}{2}
\end{array}\right)\).<br>
<br>
The following integral is calculated: $$ \int\sqrt{x+1}\sqrt{x}\;dx $$ using the following command:<br>
<code>
%display latex<br>
<br>
x = var('x') <br>
f=sqrt(x)*sqrt(1+x)<br>
print("f(x) = ")<br>
f
</code><br>
and<br>
<code>
g=integrate(f, x)<br>
print("The integral of f(x) with respect to x is: ", g)<br>
</code>
<br>
Next, we test the anti-derivative of \(f(x)\), which is \(F(x)\). We can verify this by differentiating \(F(x)\) and checking if it equals \(f(x)\). Do this with the following command:
<br>
<code>
%display latex<br>
h=diff(g,x)<br>
h.canonicalize_radical()
</code>
<br>
If you want to know information about the commands you have typed in the input cell box, type the following in the input cell box, for example:<br>
<code>
diff?
</code><br>
or
<br>
<code>
integrate?
</code>
<br>
If you place the command <code>%time</code> at the beginning of an input line, the time it takes to execute the command will be displayed after the output. For example, we can compare the running times for certain exponential operations in a few ways. The timings below will likely be different on your computer, or even between different versions of SageMath. Try typing the following commands in the input cell box:
<br>
<code>
%time a = int(1938)^int(99484); print("a = ",a)
</code>
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
%time a = int(1938)^int(99484); print("a = ",a)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
version()
</script>
</div>
<br>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
</script>
</div>
 </p>
 </div>
 <hr class="horizontal-line">
 <div class="subsection">
    <h3 style='text-align: justify;margin-left:220px;margin-right:25px;'>
      1.3. 2D Graph
    </h3>
  <hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Sage provides extensive 2D plotting functionality. The underlying rendering is done using the <b>matplotlib Python library</b>. To get information on 2D plots, type <code>plot?</code>. From this information, you can try drawing graphs from the existing examples.
  </p>
  <br>
  <div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
plot?
</script>
</div>
<br>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
f(x) = (floor(x)+0.5) / (1-(x-0.5)^2)
plot(f, (x, -3.5, 3.5),gridlines='True', detect_poles='show', exclude=[-3..3],ymin=-5, ymax=5,figsize=4,title='Graphic: $f(x)=\\dfrac{\\lfloor x\\rfloor + 0.5}{(1-(x-0.5)^2)}$') 
</script>
</div>
<br>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
f(x) = x^2*sin(1/x)
g1 = plot(f(x), (x, -2, 2),gridlines='True', axes_labels=['$x$', '$y$'],legend_label=r'$x^2\sin(1/x)$')
g2 = plot(f(x), (x, -0.3, 0.3),gridlines='True', axes_labels=['$x$', '$y$'],color='red',frame=True)
g1.inset(g2,pos=(0.129, 0.58, 0.25, 0.25))  
</script>
</div>

<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
f(x) = sin(x)
g(x) = sin(2 * x)
h(x) = sin(4 * x)
p1 = plot(f, (-2 * pi,2 * pi), color=hue(0.5)) # long time
p2 = plot(g, (-2 * pi,2 * pi), color=hue(0.9)) # long time
p3 = parametric_plot((f,g), (0,2 * pi), color=hue(0.6)) # long time
p4 = parametric_plot((f,h), (0,2 * pi), color=hue(1.0)) # long time
ga = graphics_array(((p1,p2), (p3,p4))) # long time
ga.show() # long time; same output as above
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
print()
p1 = plot(sin(x^2), (x, 0, 6),axes_labels=[r'$\theta$', r'$\sin(\theta^2)$'], fontsize=8)
p2 = plot(x^3, (x, 1, 100), axes_labels=[r'$x$', r'$y$'],scale='semilogy', frame=True, gridlines='minor')
ga = graphics_array([p1, p2])
ga.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
n, l, x, y = 10000, 1, 0, 0; p = [[0, 0]]
for k in range(n):
    theta = (2*pi*random()).n(digits=5)
    x, y = x + l * cos(theta), y + l * sin(theta)
    p.append([x, y])
g1 = line([p[n], [0, 0]], color='red', thickness=2)
g1 += line(p, thickness=.4); g1.show(aspect_ratio=1)
</script>
</div>
<br>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
z = var('z')
g1 = complex_plot(abs(cos(z^4))-1,(-3,3), (-3,3), plot_points=400)
f = lambda x, y : (abs(cos((x + I * y) ** 4)) - 1)
g2 = implicit_plot(f, (-3, 3), (-3, 3), plot_points=400)
g1.show(aspect_ratio=1); g2.show(aspect_ratio=1)
</script>
</div>
<br>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
t = var('t')
x = cos(t) + cos(7*t)/2 + sin(17*t)/3
y = sin(t) + sin(7*t)/2 + cos(17*t)/3
g = parametric_plot((x, y), (t, 0, 2*pi))
g.show(aspect_ratio=1)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
f2(x) = 1; f1(x) = -1
f = piecewise([[(-pi,0),f1],[(0,pi),f2]])
S = f.fourier_series_partial_sum(20,pi)
g = plot(S, x, -8, 8, color='blue')
saw(x) = x - 2 * pi * floor((x + pi) / (2 * pi))
g += plot(saw(x) / abs(saw(x)), x, -8, 8, color='red')
g
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
a = animate([[sin(x), taylor(sin(x), x, 0, 2*k+1)]\
             for k in range(0, 14)], xmin=-14, xmax=14,\
            ymin=-3, ymax=3, figsize=[8, 4])
a.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
</script>
</div>

<hr class="horizontal-line">
<div class="subsection">
    <h3 style='text-align: justify;margin-left:220px;margin-right:25px;'>
      1.4. 3D Graph
    </h3>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Sage also provides extensive 3D plotting functionality. The underlying rendering is done using the matplotlib Python library. To get information on 3D plots, type <code>plot3d?</code>, from this information you can try drawing graphs from the existing examples. Click the left mouse button and move around. By doing this, you can see the image from different angles.
<br>
<br>
Given any 3D graphics object M one can compute a raytraced representation by typing <code>M.show(viewer='tachyon')</code>. For example, we draw two translucent spheres that contain a red tube, and render the result using Tachyon.
SageMath's 3D graphics capabilities are truly remarkable, as evidenced by the various examples provided here. Readers can learn from the 3D graphics code presented here and experiment by modifying the commands to suit their needs.
<br>
<br>
In addition to the 3D graphics presented here, you can interact with the Three.js JavaScript WebGL Renderer. A web-based interactive viewer using the Three.js JavaScript library maintained by <a href="https://threejs.org" target="_blank">https://threejs.org</a>.
<br>
<br>
The viewer is invoked by adding the keyword argument <code>viewer='threejs'</code> to the command <code>show()</code> or any three-dimensional graphic. The scene is rendered and displayed in the users’s web browser. Interactivity includes
</p>
 <ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>Zooming in or out with the mouse wheel or pinching on a touch pad</li>
<li>Rotation by clicking and dragging with the mouse or swiping on a touch pad</li>
<li>Panning by right-clicking and dragging with the mouse or swiping with three fingers on a touch pad</li>
</ul>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The generated HTML file contains all data for the scene apart from the <code>JavaScript</code> library and can be saved to disk for sharing or embedding in a web page. The option online can be set to <code>true</code> to provide links to the required files in an online content delivery network. Alternately the required files can be downloaded from the Three.js GitHub repository and linked directly from the web server.
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
import numpy as np
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D

# Generate data
x = np.linspace(-5, 5, 100)
y = np.linspace(-5, 5, 100)
x, y = np.meshgrid(x, y)
z = np.sin(np.sqrt(x**2 + y**2))

# Plot
fig = plt.figure()
ax = fig.add_subplot(111, projection='3d')
ax.plot_surface(x, y, z, cmap='viridis')

# Set labels and title
ax.set_xlabel('X')
ax.set_ylabel('Y')
ax.set_zlabel('Z')
ax.set_title('3D Surface Plot')

plt.show()
</script>
</div>
<br>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
plot3d?
</script>
</div>
<br>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
from sage.plot.plot3d.shapes import *
S = Sphere(.5, color='yellow')
S += Cone(.5, .5, color='red').translate(0,0,.3)
S += Sphere(.1, color='white').translate(.45,-.1,.15)
S += Sphere(.05, color='black').translate(.51,-.1,.17)
S += Sphere(.1, color='white').translate(.45, .1,.15)
S += Sphere(.05, color='black').translate(.51, .1,.17)
S += Sphere(.1, color='yellow').translate(.5, 0, -.2)

S.scale(1,1,2).show(frame=False)
</script>
</div>
<br>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x,y = var('x,y')
plot3d(sin(x - y)*y*cos(x), (x, -3, 3), (y, -3, 3),mesh=True)
</script>
</div>
<br>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x, y = var('x y')
W = plot3d(sin(pi*((x)^2 + (y)^2))/2, (x, -1, 1), (y, -1, 1),frame=False, color='purple', opacity=0.8)
S = sphere((0, 0, 0), size=0.3, color='red', aspect_ratio=[1,1,1])
show(W + S, figsize=8)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
def f(x,y):
    return math.sin(y^2 + x^2)/math.sqrt(x^2 + y^2 + 0.0001)
P = plot3d(f, (-3, 3),(-3, 3), adaptive=True,color=rainbow(60, 'rgbtuple'), max_bend=.1, max_depth=15)
P.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
def f(x,y):
    return math.exp(x/5)*math.sin(y)
P = plot3d(f, (-5, 5), (-5, 5), adaptive=True, color=['red', 'yellow'])
from sage.plot.plot3d.plot3d import axes
S = P + axes(6, color='black')
S.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x, y = var('x y')
cm = colormaps.hsv
def c(x, y): return float((x + y + x*y)/15) % 1
plot3d(x*x + y*y, (x, -4, 4), (y, -4, 4), color=(c, cm))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
T = Cylindrical('height', ['radius', 'azimuth'])
r, theta, z = var('r theta z')
T.transform(radius=r, azimuth=theta, height=z)
plot3d(9-r^2, (r, 0, 3), (theta, 0, pi), transformation=T)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
S = Cylindrical('radius', ['azimuth', 'height'])
theta, z = var('theta, z')
plot3d(3, (theta, 0, 2*pi), (z, -2, 2), transformation=S)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
T = Spherical('radius', ['azimuth', 'inclination'])
r, phi, theta = var('r phi theta')
T.transform(radius=r, azimuth=theta, inclination=phi)
plot3d(phi * theta, (theta, 0, pi), (phi, 0, 1), transformation=T)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
S = Spherical('inclination', ['radius', 'azimuth'])
r, theta = var('r,theta')
plot3d(10, (r,0,5), (theta, 0, 2*pi), transformation=S)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
SE = SphericalElevation('elevation', ['radius', 'azimuth'])
r, theta = var('r,theta')
plot3d(10, (r, 0, 5), (theta, 0, 2*pi), transformation=SE)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
SE = SphericalElevation('elevation', ['radius', 'azimuth'])
r, theta = var('r,theta')
P1 = plot3d((pi/12)*sin(8*theta), (r,0.99,1), (theta, 0, 2*pi),transformation=SE, plot_points=(10,200))
P2 = sphere(center=(0,0,0), size=1, color='red', opacity=0.3)
P1 + P2
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
r, phi, theta = var('r phi theta')
SE = SphericalElevation('elevation', ['radius', 'azimuth'])
angles = [pi/18, pi/12, pi/6]
P1 = [plot3d(a, (r,0,3), (theta, 0, 2*pi), transformation=SE,
             opacity=0.85, color='blue')
      for a in angles]

S = Spherical('inclination', ['radius', 'azimuth'])
P2 = [plot3d(a, (r,0,3), (theta, 0, 2*pi), transformation=S,
             opacity=0.85, color='red')
      for a in angles]
show(sum(P1+P2), aspect_ratio=1)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
r, u, v = var('r,u,v')
f = u*v; urange = (u, 0, pi); vrange = (v, 0, pi)
T = (r*cos(u), r*sin(u), v, [u, v])
plot3d(f, urange, vrange, transformation=T)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
theta, z = var('theta,z')
cylindrical_plot3d(2, (theta, 0, 3*pi/2), (z, -2, 2))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
theta, z = var('theta,z')
cylindrical_plot3d(cosh(z), (theta, 0, 2*pi), (z, -2, 2))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
theta, z = var('theta,z')
cylindrical_plot3d(e^(-z^2)*(cos(4*theta) + 2) + 1, (theta, 0, 2*pi), (z, -2, 2), plot_points=[80, 80]).show(aspect_ratio=(1, 1, 1))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
plot3d(lambda x, y: x^2 + y^2, (-2,2), (-2,2))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
plot3d(lambda x, y: x^2 + y^2, (-2,2), (-2,2), adaptive=True)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
plot3d(lambda x, y: x^2 + y^2, (-2,2), (-2,2), adaptive=True, initial_depth=5)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
var('x,y')
plot3d(x^2 + y^2, (x,-2,2), (y,-2,2))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
var('x,y')
plot3d(sin(x*y), (x, -pi, pi), (y, -pi, pi))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
var('x,y')
plot3d(sin(x^2 + y^2), (x,-5,5), (y,-5,5), plot_points=200)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
var('x,y')
plot3d(sin(x^2 + y^2), (x, -5, 5), (y, -5, 5), plot_points=[10, 100])
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
var('x,y')
plot3d(sin(x - y)*y*cos(x), (x, -3, 3), (y, -3, 3), mesh=True)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
var('x,y')
plot3d(sin(x - y)*y*cos(x), (x, -3, 3), (y, -3, 3), mesh=True,
       thickness=2, viewer='threejs')
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x,y = var('x,y')
P = plot3d(x + y + sin(x*y), (x, -10, 10), (y, -10, 10),
           opacity=0.87, color='blue')
Q = plot3d(x - 2*y - cos(x*y),(x, -10, 10), (y, -10, 10),
           opacity=0.3, color='red')
P + Q
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x,y = var('x,y')
L = plot3d(lambda x,y: 0, (-5,5), (-5,5), color="lightblue", opacity=0.8)
P = plot3d(lambda x,y: 4 - x^3 - y^2, (-2,2), (-2,2), color='green')
Q = plot3d(lambda x,y: x^3 + y^2 - 4, (-2,2), (-2,2), color='orange')
L + P + Q
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x, y = var('x y')
plot3d(sin(pi*(x^2 + y^2))/2, (x, -1, 1), (y, -1, 1))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x, y = var('x y')
plot3d(4*x*exp(-x^2 - y^2), (x, -2, 2), (y, -2, 2))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
r, phi, z = var('r phi z')
trans = (r*cos(phi), r*sin(phi), z)
plot3d(cos(r), (r, 0, 17*pi/2), (phi, 0, 2*pi), transformation=trans, opacity=0.87).show(aspect_ratio=(1,1,2), frame=False)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
phi, theta = var('phi, theta')
Y = spherical_harmonic(2, 1, theta, phi)
rea = spherical_plot3d(abs(real(Y)), (phi, 0, 2*pi), (theta, 0, pi), color='blue', opacity=0.6)
ima = spherical_plot3d(abs(imag(Y)), (phi, 0, 2*pi), (theta, 0, pi), color='red', opacity=0.6)
(rea + ima).show(aspect_ratio=1)  
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x,y = var('x,y')
spherical_plot3d((2 + cos(2*x))*(y + 1), (x, 0, 2*pi), (y, 0, pi), rgbcolor=(1, .1, .1))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x,y = var('x,y')
spherical_plot3d(1 + sin(5*x)/5, (x, 0, 2*pi), (y, 0, pi), rgbcolor=(1, 0.5, 0), plot_points=(80, 80), opacity=0.7)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
x, y = var('x,y')
spherical_plot3d(1 + 2*cos(2*y), (x, 0, 3*pi/2), (y, 0, pi)).show(aspect_ratio=(1, 1, 1))
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
S = sphere(opacity=0.8, aspect_ratio=[1,1,1])
L = line3d([(0,0,0),(2,0,0)], thickness=10, color='red')
M = S + S.translate((2,0,0)) + L
M.show(viewer='tachyon')
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
t = Tachyon(xres=500, yres=500, camera_position=(2,0,0))
t.light((4,3,2), 0.2, (1,1,1))
t.texture('t2', ambient=0.1, diffuse=0.9, specular=0.5, opacity=1.0, color=(1,0,0))
t.texture('t3', ambient=0.1, diffuse=0.9, specular=0.5, opacity=1.0, color=(0,1,0))
t.texture('t4', ambient=0.1, diffuse=0.9, specular=0.5, opacity=1.0, color=(0,0,1))
t.sphere((0,0.5,0), 0.2, 't2')
t.sphere((0.5,0,0), 0.2, 't3')
t.sphere((0,0,0.5), 0.2, 't4')
t.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
t = Tachyon(camera_position=(0,-4,1), xres=800, yres=600, raydepth=12,
            aspectratio=.75, antialiasing=4)
t.light((0.02,0.012,0.001), 0.01, (1,0,0))
t.light((0,0,10), 0.01, (0,0,1))
t.texture('s', color=(.8,1,1), opacity=.9, specular=.95, diffuse=.3, ambient=0.05)
t.texture('p', color=(0,0,1), opacity=1, specular=.2)
t.sphere((-1,-.57735,-0.7071),1,'s')
t.sphere((1,-.57735,-0.7071),1,'s')
t.sphere((0,1.15465,-0.7071),1,'s')
t.sphere((0,0,0.9259),1,'s')
t.plane((0,0,-1.9259),(0,0,1),'p')
t.show() 
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
cedges = [[[1, 1, 1], [-1, 1, 1]], [[1, 1, 1], [1, -1, 1]],
[[1, 1, 1], [1, 1, -1]], [[-1, 1, 1], [-1, -1, 1]], [[-1, 1, 1],
[-1, 1, -1]], [[1, -1, 1], [-1, -1, 1]], [[1, -1, 1], [1, -1, -1]],
[[-1, -1, 1], [-1, -1, -1]], [[1, 1, -1], [-1, 1, -1]],
[[1, 1, -1], [1, -1, -1]], [[-1, 1, -1], [-1, -1, -1]],
[[1, -1, -1], [-1, -1, -1]]]

t = Tachyon(xres=800, yres=600, camera_position=(-1.5,0.0,0.0), zoom=.2)
t.texture('t1', color=(0,0,1))
for ed in cedges:
    t.fcylinder(ed[0], ed[1], .05, 't1')
t.light((-4,-4,4), .1, (1,1,1))
t.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
cedges = [[[1, 1, 1], [-1, 1, 1]], [[1, 1, 1], [1, -1, 1]],
[[1, 1, 1], [1, 1, -1]], [[-1, 1, 1], [-1, -1, 1]], [[-1, 1, 1],
[-1, 1, -1]], [[1, -1, 1], [-1, -1, 1]], [[1, -1, 1], [1, -1, -1]],
[[-1, -1, 1], [-1, -1, -1]], [[1, 1, -1], [-1, 1, -1]],
[[1, 1, -1], [1, -1, -1]], [[-1, 1, -1], [-1, -1, -1]],
[[1, -1, -1], [-1, -1, -1]]]

t = Tachyon(xres=800, yres=600, camera_position=(-1.5,0.0,0.0),
projection='fisheye', frustum=(-1.2, 1.2, -1.2, 1.2))
t.texture('t1', color=(0,0,1))
for ed in cedges:
    t.fcylinder(ed[0], ed[1], .05, 't1')
t.light((-4,-4,4), .1, (1,1,1))
t.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
T = Tachyon(xres=800, antialiasing=4, raydepth=10,
            projection='perspective_dof', focallength='1.0', aperture='.0025')
T.light((0,5,7), 1.0, (1,1,1))
T.texture('t1', opacity=1, specular=.3)
T.texture('t2', opacity=1, specular=.3, color=(0,0,1))
T.texture('t3', opacity=1, specular=1, color=(1,.8,1), diffuse=0.2)
T.plane((0,0,-1), (0,0,1), 't3')
ttlist = ['t1', 't2']
tt = 't1'
T.cylinder((0,0,.1), (1,1/3,0), .05, 't3')
for q in srange(-3, 100, .15):
    if tt == 't1':
        tt = 't2';
    else:
        tt = 't1'
    T.sphere((q, q/3+.3*sin(3*q), .1+.3*cos(3*q)), .1, tt)
T.show()
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
p1 = sphere(color='red', opacity='.5')
p2 = sphere((-1,-1,1), color='cyan', opacity='.3')
p3 = sphere((1,-1,-1), color='yellow', opacity='.7')
show(p1 + p2 + p3, viewer='threejs')
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
def build_frame(t):
    e = parametric_plot3d([sin(x-t), 0, x], (x, 0, 2*pi), color='red')
    m = parametric_plot3d([0, -sin(x-t), x], (x, 0, 2*pi), color='green')
    return e + m
frames = [build_frame(t) for t in (0, pi/32, pi/16, .., 2*pi)]
plot = animate(frames).interactive()
show(plot, delay=5, auto_play=False, projection='orthographic')
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
We present examples of animations created with the Three.js JavaScript WebGL Renderer.
<center style='text-align: justify;margin-left:220px;margin-right:0px;'>
<iframe src="https://threejs.org/examples/#webgl_animation_skinning_blending" style="width:97%; height:1600%;" target="_blank" rel="noopener">
</iframe>
</center>
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
# This Sagemath cell is provided for practice!
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
# This Sagemath cell is provided for practice!
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
# This Sagemath cell is provided for practice!
</script>
</div>
 </div>
</section>

<hr class="horizontal-line">
<section id="DatSut">
<h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>2. Data Structures</h2>
<hr class="horizontal-line">
<p class="ex1" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<span class="tooltip2"><b>Data structures</b> <span class="tooltiptext"> A data organization, and storage format that is usually chosen for efficient access to data. More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data, i.e., it is an algebraic structure about data. <a href="https://en.wikipedia.org/wiki/Data_structure" target="blank"><mark>[Source]</mark></a></span></span> 
are fundamental building  blocks in <span class="tooltip1"><b>computer science</b> <span class="tooltiptext">Computer science is the study of computation, information, and automation. Computer science spans theoretical disciplines (such as algorithms, theory of computation, and information theory) to applied disciplines (including the design and implementation of hardware and software). <a href="https://en.wikipedia.org/wiki/Computer_science" target="blank"><mark>[Source]</mark></a></span></span>. They organize and store data efficiently, enabling easy access, modification, and retrieval. These structures are crucial for writing efficient algorithms and managing large <span class="tooltip2"><b>datasets</b> <span class="tooltiptext"> A data set (or dataset) is a collection of data. In the case of tabular data, a data set corresponds to one or more database tables, where every column of a table represents a particular variable, and each row corresponds to a given record of the data set in question. The data set lists values for each of the variables, such as for example height and weight of an object, for each member of the data set. Data sets can also consist of a collection of documents or files. <a href="https://en.wikipedia.org/wiki/Data_set" target="blank"><mark>[Source]</mark></a></span></span> in software development.
<br>
<br>
Here are some common data structures:
</p>
<ol style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li><b>Arrays</b>: A collection of elements stored in contiguous memory locations. Arrays offer constant-time access to elements but may have limitations when resizing.
</li>
<li><b>Linked Lists</b>: A sequence of elements where each element points to the next one in the sequence. Linked lists allow for efficient insertion and deletion but may have slower access times compared to arrays.
</li>
<li><b>Stacks</b>: A Last-In-First-Out (LIFO) data structure. Elements are added and removed from the same end, called the top. Common operations include push (add) and pop (remove).
</li>
<li><b>Queues</b>: A First-In-First-Out (FIFO) data structure. Elements are added at the rear and removed from the front. Common operations include enqueue (add) and dequeue (remove).
</li>
<li><b>Trees</b>: Hierarchical data structures composed of nodes. Trees have a root node, parent nodes, and child nodes. Examples include binary trees, binary search trees, and AVL trees.
</li>
<li><b>Graphs</b>: A collection of nodes (vertices) connected by edges. Graphs can be directed or undirected and may have weighted edges.
</li>
<li><b>Hash Tables</b>: Data structures that store key-value pairs. They use a hash function to compute an index into an array of buckets or slots, where the value can be stored or retrieved with an associated key.
</li>
</ol>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
These are just some of the foundational data structures, and there are many variations and combinations used in different scenarios depending on the requirements of the problem at hand. Understanding data structures and their properties is essential for designing efficient algorithms and building robust software systems.
</p>

<hr class="horizontal-line">
<div class="subsection">
    <h3 style='text-align: justify;margin-left:220px;margin-right:25px;'>2.1. Greedy algorithm</h3>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
 The <span class="tooltip2"><b>greedy algorithm</b><span class="tooltiptext">A greedy algorithm is any algorithm that follows the problem-solving heuristic of making the locally optimal choice at each stage. In many problems, a greedy strategy does not produce an optimal solution, but a greedy heuristic can yield locally optimal solutions that approximate a globally optimal solution in a reasonable amount of time. <a href="https://en.wikipedia.org/wiki/Greedy_algorithm#Specifics" target="blank"><mark>[Source]</mark></a></span></span> can be used to determine the minimum number of bills to give when making a refund in a cash transaction. Here's how it works in practice: Imagine you need to return change for an amount like 678, using only bills of denominations 500, 100, 50, 20, 10, 5, and 1. How many bills would you need to minimize the total number given?
 <br>
 <br>
 Let us understand this with the help of an example: If you have 1,000 and needs to return 678. We will start with 500 (the highest denomination) and find the number of bills of this denomination required by dividing the amount to be returned by the denomination (and then taking the floor), which is 678/500, which is 1. Now, the remaining balance can be found by subtracting from 678, which gives 178. This is followed by repeating the process with the next highest denomination. That is, for finding the number of denominations of 100, divide the remaining, i.e., 178 by 100 (and then take the floor), which gives 1. The remaining amount in the next step will be 78. Likewise, the number of notes of 50, 20, 10, 5, and 1 will be 1, 1, 0, 1, and 3. That is, the number of bills required for change are [1, 1, 1, 1, 0, 1, 3].
 <br>
 <br>
 Here is the Python code to solve the problem mentioned before.
 </p>
 <br>
 <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
<script type="text/x-sage">
def coin_changing(L, amount):
    denomination = []
    i=0
    while(i<len(L)):
        num = floor(amount/L[i])
        amount = amount - num*L[i]
        denomination.append(num)
        i+=1
    return denomination
L=[500, 100, 50, 20, 10, 5, 1] # List of changeable denominations
print(len(L))
den=coin_changing(L, 678)  # The return amount is 678. You can change it.
print(den)
</script>
</div>
</div>

<hr class="horizontal-line">
<div class="subsection">
    <h3 style='text-align: justify;margin-left:220px;margin-right:25px;'>2.2. NumPy array</h3>
<hr class="horizontal-line"> 
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
   NumPy is not imported into sage initially. To use NumPy, you first need to import it. The basic object of computation in NumPy is an array. It is simple to create an array.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
a = np.array([1,24, 3, 2])
a
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  NumPy arrays can store any type of python object. However, for speed, numeric types are automatically converted to native hardware types (i.e., <code>int, float</code>, etc.) when possible. If the value or precision of a number cannot be handled by a native hardware type, then an array of Sage objects will be created. You can do calculations on these arrays, but they may be slower than using native types. When the numpy array contains Sage or python objects, then the data type is explicitly printed as object. If no data type is explicitly shown when NumPy prints the array, the type is either a hardware float or int.
  </p>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
a = np.array([2**40, 3**40, 4**40])
a
  </script>
  </div>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
a = 2.0000000000000000001
print(a.prec()) # higher precision than hardware floating point numbers
print(np.array([a,2*a,3*a]))
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  The <code>dtype</code> attribute of an array tells you the type of the array. For fast numerical computations, you generally want this to be some sort of float. If the data type is float, then the array is stored as an array of machine floats, which takes up much less space and which can be operated on much faster.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
l = np.array([1.0, 2.0, 3.0])
l.dtype
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  You can create an array of a specific type by specifying the dtype parameter. If you want to make sure that you are dealing with machine floats, it is good to specify <code>dtype=float</code> when creating an array.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
l = numpy.array([1,2,3], dtype=float)
l.dtype  
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  You can access elements of a NumPy array just like any list, as well as take slices
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
l = numpy.array(range(10),dtype=float)
print("l =",l)
print("l[3] =",l[3])
print("l[3:6] =",l[3:6])
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  You can do basic arithmetic operations
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
l = numpy.array(range(10),dtype=float)
print("l =",l)
print("l + l =",l+l)
print("2.5*l =",2.5*l)
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Note that <code>l*l</code> will multiply the elements of <code>l</code> componentwise. To get a dot product, use <code>numpy.dot()</code>.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
l = numpy.array(range(10),dtype=float)
print("l =",l)
print("l*l =",l*l)
print("numpy.dot(l,l) =",numpy.dot(l,l))
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  We can also create two dimensional arrays
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
m = np.array([[1,2],[3,4]])
print("m =",m)
print("m[1,1] =",m[1,1])
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  This is basically equivalent to the following
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
m = np.matrix([[1,2],[3,4]])
print("m =",m)
print("m[1,1] =",m[1,1])
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  The difference is that with <code>np.array(), m</code> is treated as just an array of data. In particular <code>m*m</code> will multiply componentwise, however with <code>np.matrix(), m*m</code> will do matrix multiplication. We can also do matrix vector multiplication, and matrix addition.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy as np
n = np.matrix([[1,2],[3,4]],dtype=float)
v = np.array([[1],[2]],dtype=float)
print("n*v =",n*v)
print("n+n =",n+n)
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  If <code>n</code> was created with <code>numpy.array()</code>, then to do matrix vector multiplication, you would use <code>numpy.dot(n,v)</code>.
  <br>
  <br>
  All NumPy arrays have a shape attribute. This is a useful attribute to manipulate
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  n = numpy.array(range(25),dtype=float)
print("n =",n)
n.shape = (5,5)
print("n =",n)
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  This changes the one-dimensional array into a  $5\times 5$ array.
  <br>
  <br>
  NumPy arrays can be sliced as well
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  n = numpy.array(range(25),dtype=float)
n.shape = (5,5)
print("n[2:4,1:3] =",n[2:4,1:3])
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  It is important to note that the sliced matrices are references to the original.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  n = numpy.array(range(25),dtype=float)
n.shape = (5,5)
m = n[2:4,1:3]
m[0,0] = 100
print("n =",n)
print("m =",m)
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  You will note that the original matrix changed. This may or may not be what you want. If you want to change the sliced matrix without changing the original you should make a copy.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  n = numpy.array(range(25),dtype=float)
n.shape = (5,5)
m = n[2:4,1:3].copy()
print("m =",m)
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Some particularly useful commands are
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  x = numpy.arange(0,2,.1,dtype=float)
print("x =",x)
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  You can see that <code>numpy.arange()</code> creates an array of floats increasing by <code>0.1</code> from <code>0</code> to <code>2</code>. There is a useful command <code>numpy.r_()</code> that is best explained by example.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  from numpy import r_
j = complex(0,1)
RealNumber = float
Integer = int
n = r_[0.0:5.0]
print("n =",n)
n = r_[0.0:5.0, [0.0]*5]
print("n =",n)
j
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  <code>numpy.r_()</code> provides a shorthand for constructing NumPy arrays efficiently. Note in the above <code>0.0:5.0</code> was shorthand for <code>0.0, 1.0, 2.0, 3.0, 4.0</code>. Suppose we want to divide the interval from <code>0</code> to <code>5</code> into <code>10</code> intervals. We can do this as follows
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  from numpy import r_
j = complex(0,1)
r_[0.0:5.0:11*j]
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  The notation <code>0.0:5.0:11*j</code> expands to a list of <code>11</code> equally space points between <code>0</code> and <code>5</code> including both endpoints. Note that <code>j</code> is the NumPy imaginary number, but it has this special syntax for creating arrays. We can combine all of these techniques.
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  from numpy import r_
j = complex(0,1)
n = r_[0.0:5.0:11*j,int(5)*[0.0],-5.0:0.0]
n
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Another useful command is <code>numpy.meshgrid()</code>, it produces meshed grids. As an example suppose you want to evaluate $f(x,y)=x^2+y^2$ on a an equally spaced grid with $\Delta x=\Delta y = 0.25$ for $0\leq x,y\leq 1$. You can do that as follows
 </p> 
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy
j = complex(0,1)
def f(x,y):
    return x**2+y**2
from numpy import meshgrid
x = numpy.r_[0.0:1.0:5*j]
y = numpy.r_[0.0:1.0:5*j]
xx,yy = meshgrid(x,y)
print("xx =",xx)
print("yy =",yy)
print("f(xx,yy) =",f(xx,yy))
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  You can see that <code>numpy.meshgrid()</code> produces a pair of matrices, here denoted $xx$ and $yy$, such that 
 $(xx[i,j],yy[x,j])$ has coordinates $(x[i],y[j])$. This is useful because to evaluate $f$ over a grid, we only need to evaluate it on each pair of entries in $xx, yy$. Since NumPy automatically performs arithmetic operations on arrays componentwise, it is very easy to evaluate functions over a grid with very little code.
 <br>
 <br>
 A useful module is the <code>numpy.linalg</code> module. If you want to solve an equation $Ax=b$ do
  </p>
  <br>
  <div class="compute" style="justify;margin-left:220px;margin-right:25px;">
  <script type="text/x-sage">
  import numpy
from numpy import linalg
A = numpy.random.randn(5,5)
b = numpy.array(range(1,6))
x = linalg.solve(A,b)
numpy.dot(A,x)
  </script>
  </div>
  <br>
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  This creates a random $5\times 5$ matrix $A$, and solves $Ax=b$ where $b=[1.0,2.0,3.0,4.0,5.0]$. There are many other routines in the <code>numpy.linalg</code> module that are mostly self-explanatory. For example there are <code>qr</code> and <code>lu</code> routines for doing <b>QR</b> and <b>LU</b> decompositions. There is also a command <code>eigs</code> for computing <b>eigenvalues</b> of a matrix. You can always do <code><function name>?</code> to get the documentation which is quite good for these routines.
  <br>
  <br>
  Hopefully this gives you a sense of what NumPy is like. You should explore the package as there is quite a bit more functionality.
  </p>
</div>

</section>
<hr class="horizontal-line">
<section id="InInt">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>3. Indefinite Integrals</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Click the "<b><mark>Enable</mark></b>" button below to calculate indefinite integrals. To perform the computation, click the "<b>Update</b>" button. Please type other functions in the available box to perform indefinite integration of the functions you want.
  </p>
  <div id="mycell" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
x=var('x')
@interact
def _(f = input_box(default = x^3/(x^2-1),width=25),auto_update=False):
    q=integrate(f,x)
    pretty_print(html(r"The value of integral: $$\int\left(%s\right)\\ dx=%s+c$$"%(latex(f),latex(q))))
 </script>
</div>
<br>

<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
You can also perform indefinite integral computations using <b>Geogebra</b> as follows. Try observing and comparing the computation results in the <b>SageMath</b> Cell with the results in <b>Geogebra</b>.
<br>
<center style='text-align: justify;margin-left:220px;margin-right:25px;'>
<iframe src="https://www.geogebra.org/m/vbjkrb3d" width="100%" height="500" style="border:1px solid black;">">
</iframe>
</center>
</p>
</section>
<hr class="horizontal-line">

<section id="Latihan">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>4. Exercises!</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  
  <div  style="background-color:powderblue; border-style:solid double;border-width:7px;margin-left:220px;margin-right:25px;">
  <p style='text-align: justify;margin-left:10px;margin-right:60px;'>
  We provide some problems, you can try solving them with SageMath.
  </p>
<ol style='text-align: justify;'>
<li> Find the integral: \(\operatorname{\Large\int} \dfrac{\sqrt{3}}{\sqrt{3x^2-2}}\; dx\).<br>

<!-- Text to be toggled -->
<script>
  // JavaScript function to toggle the text visibility
  function toggleText() {
    var text = document.getElementById("toggle-text");
    if (text.style.display === "none") {
      text.style.display = "block";
    } else {
      text.style.display = "none";
    }
  }
</script>
<span class="toggle-btn" onclick="toggleText()">
<b><mark>Solution:</mark> Click to display/hide!</b>
</span>
<div id="toggle-text" class="hidden-text">
<p style='text-align: justify;margin-left:10px;margin-right:60px;'>
 To solve this problem, we need a geometric diagram of the following right triangle:
</p>

<center>
<script type="text/tikz">
  \begin{tikzpicture}
\draw node at (-1.0cm,-0.85cm){$\theta$};
\coordinate [label=left:$C$] (A) at (-1.5cm,-1.cm);
\coordinate [label=right:$A$] (C) at (1.5cm,-1.0cm);
\coordinate [label=above:$B$] (B) at (1.5cm,1.0cm);
\draw (A) -- node[above] {$a$} (B) -- node[right] {$c$} (C) --node[below] {$b$} (A);
\draw (1.25cm,-1.0cm) rectangle (1.5cm,-0.75cm);
  \end{tikzpicture}
</script>
</center>

<br>
<p style='text-align: justify;margin-left:0px;margin-right:20px;'>
If \(a=u\) and \(b=1\), then \(c=\sqrt{u^{2} - 1}\).  This leads to \(\sec(\theta)=u\) and \(\tan(\theta)=\sqrt{u^{2} - 1}\). We will also be utilizing the following trigonometric identities:
\begin{equation}
\fbox{\(\tan^2(\theta)=\sec^{2} - 1\)}.\label{eqn1}\tag{1}
\end{equation}
and (<b>the reader is encouraged to verify</b>) the equation:
\begin{equation}
\fbox{\(\int\; \sec(\theta)\;d\theta=\ln|\sec(\theta)+\tan(\theta)|+k\)}.\label{eqn2}\tag{2}
\end{equation}  
Now, we are ready to calculate the requested integral.
\begin{eqnarray*}
\operatorname{\Large\int} \dfrac{\sqrt{3}}{\sqrt{3x^2-2}}\; dx &=& \operatorname{\Large\int} \dfrac{\sqrt{3}}{\sqrt{2(\frac{3}{2}x^2-1)}}\; dx\\
&=& \operatorname{\huge\int} \dfrac{\sqrt{3}}{\sqrt{2}}\dfrac{1}{\sqrt{\left(\frac{\sqrt{3}}{\sqrt{2}}x\right)^2-1)}}\; dx,\\
&& \qquad{\rm{let,}}\ u=\frac{\sqrt{3}}{\sqrt{2}}x\Rightarrow du=\frac{\sqrt{3}}{\sqrt{2}}dx\\
&=& \operatorname{\Large\int} \dfrac{1}{\sqrt{u^2-1}}\; du.
\end{eqnarray*}

To calculate the last integral that appears here, we substitute \(u=\sec(\theta)\). We discussed the reason for this substitution when we discussed the trigonometric diagram. This gives us \(du=\sec(\theta)\tan(\theta)d\theta\). Using Equation (\ref{eqn1}) and Equation (\ref{eqn2}), we have
\[
\begin{eqnarray*}
\operatorname{\Large\int} \dfrac{1}{\sqrt{u^2-1}}\; du &=& \operatorname{\Large\int} \dfrac{\sec(\theta)\tan(\theta)}{\sqrt{\sec^2(\theta)-1}}\; d\theta\\
&=& \operatorname{\Large\int} \dfrac{\sec(\theta)\tan(\theta)}{\sqrt{\tan^2(\theta)}}\; d\theta\\
&=& \operatorname{\Large\int} \dfrac{\sec(\theta)\tan(\theta)}{\tan(\theta)}\; d\theta\\
&=& \int\; \sec(\theta)\;d\theta\\
&=& \ln|\sec(\theta)+\tan(\theta)|+k\\
&=& \ln|u + \sqrt{u^{2} - 1}|+k\\
&=& \ln\left| \frac{\sqrt{3}}{\sqrt{2}}x +\sqrt{\frac{3}{2}x^2 -1} \right| + k\\
&=& \ln\left| \frac{6}{2\sqrt{6}}x +\frac{1}{\sqrt{2}}\sqrt{3x^2 -2} \right| + k\\
&=& \ln\left| \frac{6}{2\sqrt{6}}x +\frac{2\sqrt{3}}{2\sqrt{6}}\sqrt{3x^2 -2} \right| + k\\
&=& \ln\left|\frac{1}{2\sqrt{6}} \left(6x +2\sqrt{3}\sqrt{3x^2 -2}\right) \right| + k\\
&=& \ln\left|6x +2\sqrt{3}\sqrt{3x^2 -2}\right| + \ln\left(\frac{1}{2\sqrt{6}}\right)+k,\\
&&\qquad\qquad \ c=\ln\left(\frac{1}{2\sqrt{6}}\right)+k \\
&=& \ln\left|6x +2\sqrt{3}\sqrt{3x^2 -2}\right| + c.
\end{eqnarray*}
\]
The reader is invited to verify this result using SageMath computation, noting that \(\ln\) in SageMath is represented as \(\log\).\(\qquad\bigstar\)
<br>
</p>
</div>
</li>
 
 <li> Compute \(\operatorname{\Large\int} \dfrac{1}{2+x^2}\; dx\).<br>
<!-- Text to be toggled -->
<script>
  // JavaScript function to toggle the text visibility
  function toggleText1() {
    var text = document.getElementById("toggle-text1");
    if (text.style.display === "none") {
      text.style.display = "block";
    } else {
      text.style.display = "none";
    }
  }
</script>
<span class="toggle-btn" onclick="toggleText1()">
<b><mark>Solution:</mark> Click to display/hide!</b>
</span>
<div id="toggle-text1" class="hidden-text">
<p style='text-align: justify;margin-left:0px;margin-right:20px;'>
\[
\begin{eqnarray*}
\operatorname{\Large\int} \dfrac{1}{2+x^2}\; dx &=& \operatorname{\huge\int} \dfrac{1}{2\left(1+\left(\frac{x}{\sqrt{2}}\right)^{2}\right)}\; dx,\\ 
&&\qquad {\rm{suppose}}\ 
 \tan(\theta)=\frac{x}{\sqrt{2}}\Rightarrow \sqrt{2}\sec^{2}(\theta)d\theta=dx\\
&=& \operatorname{\Large\int} \dfrac{\sqrt{2}\sec^{2}(\theta)}{2(1+\tan^2(\theta)}\; d\theta\\
&=&\frac{\sqrt{2}}{2}\int \frac{\sec^2(\theta)}{\sec^2(\theta)}\;d\theta\\
&=& \frac{\sqrt{2}}{2}\int d\theta\\
&=& \frac{\sqrt{2}}{2}\theta +c\\
&=& \frac{\sqrt{2}}{2}\arctan\left(\frac{1}{2}\sqrt{2}x\right)+c.\quad\bigstar
\end{eqnarray*}
\]
</p>
</div>
</li>


<li> Compute \(\operatorname{\Large\int} \dfrac{e^{x}}{\sqrt{1-e^{2x}}}\;dx\).<br>

<!-- Text to be toggled -->
<script>
  // JavaScript function to toggle the text visibility
  function toggleText2() {
    var text = document.getElementById("toggle-text2");
    if (text.style.display === "none") {
      text.style.display = "block";
    } else {
      text.style.display = "none";
    }
  }
</script>
<span class="toggle-btn" onclick="toggleText2()">
<b><mark>Solution:</mark> Click to display/hide!</b>
</span>
<div id="toggle-text2" class="hidden-text">
<p style='text-align: justify;margin-left:0px;margin-right:20px;'>
\[
\begin{eqnarray*}
\operatorname{\Large\int} \dfrac{e^{x}}{\sqrt{1-e^{2x}}}\;dx &=& \operatorname{\Large\int} \dfrac{e^{x}}{\sqrt{1-(e^{x})^2}}\;dx\\
&&\qquad {\rm{suppose}}\ 
 \sin(\theta)=e^{x}\Rightarrow \cos(\theta)d\theta=e^{x}dx\\ 
&=& \operatorname{\Large\int} \dfrac{\cos(\theta)}{\sqrt{1-\sin^2(\theta)}}\;d\theta\\
&=& \operatorname{\Large\int} \dfrac{\cos(\theta)}{\sqrt{\cos^2(\theta)}}\;d\theta\\
&=& \operatorname{\Large\int} \dfrac{\cos(\theta)}{\cos(\theta)}\;d\theta\\
&=& \int d\theta\\
&=& \theta + c\\
&=& \arcsin(e^x)+c.\quad\bigstar
\end{eqnarray*}
\]
</p>
</div>
</li>


<li> Compute \(\operatorname{\Large\int}\dfrac{x}{4x^2+12x+13}\,dx\).<br>

<!-- Text to be toggled -->
<script>
  // JavaScript function to toggle the text visibility
  function toggleText3() {
    var text = document.getElementById("toggle-text3");
    if (text.style.display === "none") {
      text.style.display = "block";
    } else {
      text.style.display = "none";
    }
  }
</script>
<span class="toggle-btn" onclick="toggleText3()">
<b><mark>Solution:</mark> Click to display/hide!</b>
</span>
<div id="toggle-text3" class="hidden-text">
<p style='text-align: justify;margin-left:0px;margin-right:20px;'>
From <b>Exercise 2</b>, we can conclude that \(\fbox{\(\int\frac{1}{1+u^2}\;du=\arctan(u)+c\)}\). We use this result:
\begin{eqnarray*}
\operatorname{\Large\int}\dfrac{x}{4x^2+12x+13}\;dx &=& \frac{1}{4}\operatorname{\Large\int}\dfrac{x}{x^2+3x+\frac{9}{4}+1}\;dx\\
&=& \frac{1}{4}\operatorname{\Large\int}\dfrac{x}{\left(x+\frac{3}{2}\right)^2+1}\;dx,\\
&&\qquad {\rm{suppose}}\ u=x+\frac{3}{2}\Rightarrow du=dx, x=u-\frac{3}{2}\\
&=& \frac{1}{4}\operatorname{\Large\int}\dfrac{u-\frac{3}{2}}{u^2+1}\;du\\
&=& \frac{1}{4}\operatorname{\Large\int}\dfrac{u}{u^2+1}\;du-\frac{3}{8}\operatorname{\Large\int}\dfrac{1}{u^2+1}\;du\\
&=&\frac{1}{4}\operatorname{\Large\int}\dfrac{u}{u^2+1}\;du-\frac{3}{8}\arctan(u)+k\\
&=&\frac{1}{4}\operatorname{\Large\int}\dfrac{u}{u^2+1}\;du-\frac{3}{8}\operatorname{\Large\int}\dfrac{1}{u^2+1}\;du\\
&=&\frac{1}{4}\operatorname{\Large\int}\dfrac{u}{u^2+1}\;du-\frac{3}{8}\arctan(x+\frac{3}{2})+k\\ 
&=&\frac{1}{8}\operatorname{\Large\int}\dfrac{2udu}{u^2+1}-\frac{3}{8}\arctan(x+\frac{3}{2})+k,\\ 
&&\qquad {\rm{suppose}}\; v=u^2+1\Rightarrow dv=2udu\\
&=& \frac{1}{8}\operatorname{\Large\int}\dfrac{dv}{v}-\frac{3}{8}\arctan(x+\frac{3}{2})+k\\
&=& \frac{1}{8}\ln(v)-\frac{3}{8}\arctan(x+\frac{3}{2})+k\\
&=& \frac{1}{8}\ln(u^2+1)-\frac{3}{8}\arctan(x+\frac{3}{2})+k\\
&=& \frac{1}{8}\ln(x^2+3x+\frac{13}{4})-\frac{3}{8}\arctan(x+\frac{3}{2})+k\\
&=& \frac{1}{8}\ln\left(\frac{1}{4}(4x^2+12x+13)\right)-\frac{3}{8}\arctan(x+\frac{3}{2})+k\\
&=& \frac{1}{8}\ln(4x^2+12x+13)-\frac{3}{8}\arctan(x+\frac{3}{2})+\frac{1}{8}\ln(\frac{1}{4})+k\\
&=& \frac{1}{8}\ln(4x^2+12x+13)-\frac{3}{8}\arctan(x+\frac{3}{2})+c,\\
&&\qquad\text{where}\ c=\frac{1}{8}\ln(\frac{1}{4})+k.\ \qquad\bigstar
\end{eqnarray*}
</p>
</div>
</li>
</ol>
</div>
<br>
<div class="compute" style="justify;margin-left:220px;margin-right:25px;">
<script type="text/x-sage">
# Please do the computation in SageMath yourself!
</script>
</div>
  
</section>
<hr class="horizontal-line">

<section id="DefInt">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>5. Definite Integral</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  This computational tool calculates definite integrals of the form: \(\mathop{\int}\limits_{a}^{b}f(x)dx\) 
  where \(f(x)\) is defined on the closed interval \([a,b]\). The tool requires two conditions:
  </p>
  <ol style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>\(f(x)\) must be Riemann integrable on the interval \([a,b]\).</li>
<li>The antiderivative of \(f(x)\), denoted by \(F(x)\), must satisfy the equation \(F'(x) = f(x)\) for all \(x\)-values within the interval.</li>
</ol>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
If these conditions are not met, an "integral divergence error message" will appear. 
<br>
<br>
To use the tool:
</p>
<ol style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>Click the "<b><mark>Enable</mark></b>" button below to calculate a definite integral.</li>
<li>Click the "<b>Update</b>" button to change the integration limits \(a\) and \(b\) using the provided boxes.</li>
<li>Enter your desired function in the designated box.</li>
<li>Specify the desired integration limits \(a\) and \(b\) in the corresponding boxes.</li>
</ol>
<br>
<div id="Intent" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
x=var('x')
@interact
def _(f = -2*sin(x)+x,a=-3,b=5,auto_update=False):
    q=integrate(f,x).canonicalize_radical()
    p=integrate(f,x,a,b)
    r=plot([f],x,a,b,gridlines='minor',\
           legend_label='automatic',fill = true)
    r.show(figsize=4)
    pretty_print(html("The value of the integral:\
    $$\\int\\limits_{%s}^{%s}\\left(%s\\right)\\,dx=\
    \\left.%s\\right|_{%s}^{%s}=%s\
    \\approx %s$$"%(latex(a),latex(b),latex(f),latex(q),\
                    latex(a),latex(b),latex(p),latex(n(p)))))
 </script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
<b>Geogebra</b> can also be used to perform definite integral computations. Readers can then compare the results obtained with <b>Geogebra</b> to those produced by <b>SageMath</b>.
<center style='text-align: justify;margin-left:220px;margin-right:25px;'>
<iframe src="https://www.geogebra.org/m/syvvvvxj" width="100%" height="500" style="border:1px solid black;">">
</iframe>
</center>
</p>
</section>

<hr class="horizontal-line">
<section id="Non-HSE">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>6. Non-Homogeneous System of Equations</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  To solve the non-homogeneous system of equations \(Ax=b\):
  </p>
  <ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>Click the "<mark><b>Enable</b></mark>" button.</li>
<li>Enter the respective values of \(A\) and \(b\) in the provided boxes.</li>
<li>Click the "<b>Update</b>" button to perform the computation.</li>
</ul>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
You can convert the system to a homogeneous system of equations by setting \(b=0\). To demonstrate the role of pivots, try changing the value of \(a_{1,1}\) to \(0\). This will result in row swapping. Enjoy!
</p>
<div id="Sisthom" style='text-align: justify;margin-left:220px;margin-right:25px;'> 
<script type="text/x-sage">
def SLE_as_latex(A, b, variables):
    nvars = A.ncols()
    pretty_print(html( 
    r'$$\left\{\begin{array}{%s}'%latex('r'*(nvars+1))+
    r'\\'.join('%s=&%s'%( 
        (' & '.join((r'%s%s\cdot %s'%('+' if c>0 else '',c,v) if c else '') for c,v in zip(row, variables))
        if not row.is_zero() else '&'*(nvars-1)+'0',y) 
               ) for row,y in zip(A,b))+
    r'\end{array}\right.$$'))

def extended_matrix_as_latex(M):
    A = M[:,:-1]
    b = M.column(-1)
    nvars = A.ncols()
    pretty_print(html(
    r'$$\left(\begin{array}{%s}'%latex('r'*nvars+ '|r')+
    r'\\'.join('%s&%s'%( 
        ' & '.join('%s'%c for c in row)
        ,y) for row,y in zip(A,b))+
    r'\end{array}\right)$$'))

@interact
def SEL(M_A='[(1,1,1,2),(-1,3,2,5),(1,-7,1,-2)]',
        M_b='[2,1,3]',
        auto_update=False
    ):
    %display latex
    A = matrix(eval(M_A))
    b = vector(eval(M_b))
    M = A.augment(b)
    neqs = len(b)
    nvars = A.ncols()
    var_names = ','.join('x%s'%j for j in [1..nvars]) #####
    variables = var(var_names)
    pretty_print(html(r'Variables: $%s$'%latex(variables)))
    for row,y in zip(A,b):
        pretty_print(html(sum(c*v for c,v in zip(row, variables))==y))

    SLE_as_latex(A, b, variables)
    pretty_print(html( 'We create an augmented matrix'))
    extended_matrix_as_latex(M)

    pivot = {}
    ibound_variables = []
    for m,row in enumerate(A):
        for k in range(m,nvars):
            lista = [(abs(M[j,k]),j) for j in range(m,neqs)]
            maxi, c = max(lista)
            if maxi > 0:
                ibound_variables.append(k)
                if M[m,k]==0:
                    M[c,:],M[m,:]=M[m,:],M[c,:]
                    pretty_print( html('Swap rows: %d and %d'%(m+1,c+1)))
                    extended_matrix_as_latex(M)
                pivot[m] = k
                break

        a=M[m,k]
        for n in range(m+1,neqs):
            if M[n,k]!=0:
                pretty_print(html("We add the elements of row %s multiplied by %d to row %d"%(m+1, -M[n,k]/a, n+1)))
                M=M.with_added_multiple_of_row(n,m,-M[n,k]/a)
                extended_matrix_as_latex(M)

    A = M[:,:-1]
    b = M.column(-1)
    SLE_as_latex(A, b, variables)
    SEL_type = 'compatible'
    null_rows = None
    for k,(row,y) in enumerate(zip(A,b)):
        if row.is_zero():
            if y==0 and null_rows is None:
                null_rows = k
                break
            elif y!=0:
                SEL_type = 'incompatible'
    if SEL_type == 'incompatible':
        pretty_print(html('The system has no solution.'))
        return
    if null_rows:
        pretty_print(html('We eliminate the trivial equation 0=0.'))
        A = A[:null_rows,:]
        b = b[:null_rows]
        SLE_as_latex(A, b, variables)

    ifree_variables = [k for k in range(nvars) if k not in ibound_variables]
    bound_variables = [variables[k] for k in ibound_variables]
    free_variables = [variables[k] for k in ifree_variables]
    pretty_print(html('Free Variables: $%s$'%latex(free_variables)))
    pretty_print(html('Dependent variables: $%s$'%latex(bound_variables)))
    reduced_eqs = [
        sum(c*v for c,v in zip(row, variables))==y
        for row,y in zip(A,b)
    ]
    xvector = vector(variables)
    if len(bound_variables)==1:
        soldict = solve(reduced_eqs, bound_variables[0], solution_dict=True)[0]
    else:
        soldict = solve(reduced_eqs, bound_variables, solution_dict=True)[0]
    pretty_print(html('Solution in terms of parameters'))
    parametric_sol = matrix(
        xvector.apply_map(lambda s:s.subs(soldict))
    ).transpose()
    show(parametric_sol)
    pretty_print(html('Solution in vector form'))
    pretty_print(html(
        r'$$ %s + \left\langle %s\right\rangle$$'%(
            latex(parametric_sol.subs(dict(zip(free_variables, [0]*len(free_variables))))),
            ','.join(latex(
            parametric_sol.apply_map(lambda s:s.diff(v))
        ) for v in free_variables) if free_variables else latex(matrix([0]*nvars).transpose()))
    ))
    pretty_print(html('Its dimension is %d'%len(free_variables)))
 </script>
</div>
</section>

<hr class="horizontal-line">
<section id="Cy-ani">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>7. Cycloid Animation</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Click the "<b><mark>Enable</mark></b>" button below to see the cycloid motion animation. Please try it!
  </p>
  
  <div id="selsaya" style='justify;margin-left:220px;margin-right:80px;'>
<script type="text/x-sage">
#cycloid animation

a = 0.2
v = []
t = var("t")
for s in srange(0.01, 4.0*pi, a):
    sikloida = parametric_plot((t-sin(t),1-cos(t)), (t, 0, s),thickness=3)
    t_sikloida = (s-sin(s),1-cos(s))
    lingkaran = circle((s,1),1,thickness=2,rgbcolor='green')
    lingkaran1 = circle((s,1),0.5,thickness=4,fill=True,edgecolor='red')
    titik = point(t_sikloida, pointsize=90, rgbcolor="brown")
    garis = line([(s, 1),t_sikloida], thickness=4,color="red")
    v.append(sikloida + lingkaran + lingkaran1 + titik + garis)
a = animate(v, figsize=[7,2], aspect_ratio=1, xmin=0.5,xmax=20, ymin=0, ymax=2.2)    
show(a)
 </script>
</div>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
<b><mark>Cycloid Animation using Geogebra</mark></b></br>
 <center style='text-align: justify;margin-left:220px;margin-right:25px;'>
<iframe src="https://www.geogebra.org/m/gws8uakv" width="95%" height="500" style="border:1px solid black;">>
</iframe>
</center>
</p>
</section>
<hr class="horizontal-line">

<section id="UYPCM">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>8. Using Your Personal Computer in Math: Powerful Tools and Applications</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  Perform SageMath Computations Independently. Follow the commands provided below:
  </p>
  
  <ol style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>Click "<b><mark>Evaluate</mark></b>" to see the results.</li>
<li>Feel free to replace the commands with other SageMath commands that you are familiar with.</li>
</ol>


<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# Graphing cos(x) on the interval 0<= x <= 2*pi
plot(cos(x), (x, 0, 2*pi))
</script>
</div>
<br>


<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
<b><mark>Surface Area of a Revolved Solid</mark></b>
Given a curve \(y=f(x)\) and \(x\in [a,b]\). If the object is bounded by \(f(x)\) and \(x=a, x=b\) and rotated about the \(x\)-axis, then the surface area of the revolved solid is \(A\) with \(dA=2\pi\ y\ ds\) so that we get:

$$
A=2\pi\mathop{\int}\limits_{a}^{b}f(x)\sqrt{1+\left(f'(x)\right)^2}dx.
$$
<b><mark>Example</mark></b><br>
Given the curve \(y=f(x)=x\) and \(x\in [-1,1]\). If the object is bounded by \(f(x)\) and \(x=-1, x=1\) and rotated about the \(x\)-axis, then the surface area of the revolved solid is \(A\) with \(dA=2\pi\ y\ ds\) so that we get:
\[
A=2\pi\int_{-1}^{1}f(x)\sqrt{1+\left(f'(x)\right)^2}dx.
\]
Note: You can replace \(y=f(x)\) and the domain interval \([a,b]\) as desired!
<br>
The computational result is given in the SageMath cell as follows:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
var('x y')
y=(x)
dy=diff(y,x)
t = integrate(y*sqrt(1+dy^2),x)
A = integrate(y*sqrt(1+dy^2),x,0,1)
pretty_print(html("$f(x)=%s$"%latex(y)))
pretty_print(html("$A=2\\pi\\int\\limits_{0}^{1}f(x)\
\\sqrt{1+f'(x)^2}\\ dx=\\left.\\left(%s\\right)\\right|_{0}^{1}$"\
                  %latex(t)))
pretty_print(html("$\\ \\ \\ =%s$"%latex(A)))
</script>
</div>
<br>
<br>


<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The following SageMath cell can be used to practice drawing various types of functions, including implicit functions. For example: \(y^3-3x^2+2x+5 = 0,\ -4\leq x\leq 4,\ -4\leq y \leq 4\). 
About <b>plotting</b>, we recommend that our readers see more details at <a href="https://doc.sagemath.org/html/en/reference/plotting/sage/plot/contour_plot.html#sage.plot.contour_plot.implicit_plot" target="blank">[plotting]</a>.
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# Please use this SageMath Cell to draw other functions as you wish!

var('x y')
implicit_plot( y^3-3*x^2+2*x+5 == 0, (x,-4,4), (y,-4,4), color="red")
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Let's give an example to calculate the value:
$$
\int \sqrt{x}\;\sqrt{1+x}\;dx.
$$
To get an exact result, we use the <code>canonicalize_radical()</code> command as follows:
</p>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
%display latex

x = var('x')
f=sqrt(x)*sqrt(1+x)
g=integrate(f, x).canonicalize_radical()
pretty_print(html(r"$f(x) = %s$"%latex(f)))
pretty_print(html(r"The value of $\int f(x)\; dx$ is : $$%s + c$$"%latex(g)))
</script>
</div>
<br>

<br>
<h3 style='text-align: justify;margin-left:220px;margin-right:25px;'>
<mark>Mathematical Applications</mark>
</h3>
<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'>  
<b> 
1. Simulation of Dynamical Systems
</b>
</h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
SageMath can be used to simulate dynamical systems, such as the predator-prey system or the Lotka-Volterra model. Here is an example of a simulation of a predator-prey system:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# Simulation of a predator-prey model

import matplotlib.pyplot as plt
import numpy as np

# Parametric model
a = 1.0
b = 0.2
c = 0.5
d = 0.1

# time simulation
t = np.linspace(0, 100, 1000)

# Model Solution
x = np.zeros(len(t))
y = np.zeros(len(t))

x[0] = 10
y[0] = 5
dt = 0.01

# Simulation
for i in range(1, len(t)):
  x[i] = x[i-1] + a*x[i-1]*dt - b*x[i-1]*y[i-1]*dt
  y[i] = y[i-1] - c*y[i-1]*dt + d*x[i-1]*y[i-1]*dt

# Solution plot
plt.plot(t, x, label="Prey")
plt.plot(t, y, label="Predator")
plt.legend()
plt.title("Lotka-Volterra model simulation results:")
plt.show()
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Let's delve deeper into the Lotka-Volterra equations, previously mentioned. These equations, also known as the Lotka-Volterra predator-prey model, are a pair of first-order, nonlinear differential equations. They're frequently used to describe the dynamics of biological systems where two species interact: one as a predator and the other as prey. Population changes over time according to the following equation:
\begin{eqnarray*}
\frac{dx}{dt} &=& \alpha x - \beta xy\\
\frac{dy}{dt} &=& \delta xy - \gamma y
\end{eqnarray*}
where
</p>
<ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>the variable \(x\) represents the population density of the prey (e.g., the number of rabbits per square kilometer);</li>
<li>the variable \(y\) represents the population density of a predator (e.g., the number of foxes per square kilometer);</li>
<li>\(\frac{dx}{dt}\) and \(\frac{dy}{dt}\) represent the instantaneous rates of change of the two populations;</li>
<li>\(t\) represents time.</li>
<li>The prey model considers two factors affecting prey populations; \(\alpha\) represents the maximum rate at which prey can reproduce per individual \(\beta\), on the other hand, reflects the increased mortality rate of prey due to the presence of predators.
</li>
<li>The predator model also relies on two key parameters, \(γ\) and \(δ\); \(γ\) represents the per capita death rate of the predator, while \(δ\) captures the impact of prey presence on the predator's growth rate.</li>
<li>All parameters are positive and real.</li>
</ul>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The solution to the differential equation is deterministic and continuous. This, in turn, implies that the generations of predators and prey continuously overlap. 
<br>
<br>
The Lotka-Volterra equation system is an example of a Kolmogorov model, which is a more general framework that can model the dynamics of ecological systems with predator-prey interactions, competition, disease, and mutualism.
<br>
<br>
We simulate Lotka-Volterra Population Dynamics in a SageMath Cell. With the following code:
</p>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# Simulating Lotka-Volterra population dynamics, generating a vector field
# Arrows indicate the direction of population evolution
# Blue contours represent one potential stable loop

var('t R F R0 F0 a b c d')
# constant
a = 0.04         # rabbit birth rate
b = 0.0005       # predator probability per encounter
c = 0.1*0.0005   # probability of predation per encounter, rabbit -> fox conversion efficiency
d = 0.2          # fox death rate
## Kondisi awal
R0 = 5000     #initial number of rabbits
F0 = 200      #initial number of foxes

## Differentialial equation
de_R = (diff(R,t) == a*R - b*R*F)
de_F = (diff(F,t) == c*R*F - d*F)

## PARAMETER CALCULATION
titik_akhir = 500
stepsize = 1.0
steps = titik_akhir/stepsize
ics = [0,R0,F0]
des = [de_R.rhs(), de_F.rhs()]

## NUMERICAL SOLUTION OF DIFFERENTIAL EQUATIONS
sol = desolve_system_rk4(des,[R,F],ics,ivar=t,end_points=titik_akhir,step=stepsize)

sol_t=[]; sol_R=[]; sol_F=[]
for i in srange(0,titik_akhir):
    sol_t.append(sol[i][0])
    sol_R.append(sol[i][1])
    sol_F.append(sol[i][2])

## Figure of simulation results
a = plot([],figsize=[6,4])
a += line(zip(sol_R,sol_F))
a += plot_vector_field((des[0], des[1]), (R,0,7000), (F,0,225),xmin=1500,color='orange')
a.axes_labels(['Rabbit','Fox']); show(a)
</script>
</div>

<br>
<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>2. Solving Differential Equations</b></h4>

<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
SageMath can be used to model differential equations, both ordinary differential equations (ODEs) and partial differential equations (PDEs): Here is an example of modeling an ODE and solving it exactly if there is a solution.
</p>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Now, let's consider the following ODE (Ordinary Differential Equation):
$$
\frac{dy}{dx} + y - 1 = 0,
$$
We'll solve it in a SageMath cell as shown below
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
%display latex

x = var('x')
y = function('y')(x)
pdb = diff(y,x) + y - 1
solpdb = desolve(diff(y,x) + y - 1, y)
pretty_print(html(r"The solution to the ODE: $%s = 0$ is: $y(x) = %s$ "%(latex(pdb),latex(solpdb))))
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The following is a second-order linear ODE:
$$
\frac{d^2 y}{dx^2}+2\frac{dy}{dx} + y -\cos(x)=0,\ y(0)=3,\ y^{\prime}(0)=1.
$$
Here's the solution code in a SageMath cell:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
%display latex

x = var('x')
y = function('y')(x)
pdb = diff(y,x,2)+2*diff(y,x)+y - cos(x)
solpdb = desolve(diff(y,x,2)+2*diff(y,x)+y == cos(x),y,[0,3,1])

pretty_print(html(r"The solution to the ODE: $%s = 0,\ y(0)=3, y'(0)=1$ is: <center>$y(x) = %s.$</center> "%(latex(pdb),latex(solpdb))))
</script
</div>
<br>
<br>

</div>
<br>

<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Next, we consider a higher-order linear ODE, in this case:
$$
-2 \, x^{4} + x^{3} \frac{d^{3}}{(d x)^{3}}y\left(x\right) + x^{2} \frac{d^{2}}{(d x)^{2}}y\left(x\right) - 2 \, x \frac{d}{d x}y\left(x\right) + 2 \, y\left(x\right) = 0.
$$
The solution is given in a SageMath cell using <b>sympy</b> as follows:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
from sympy import Function, dsolve, Derivative
from sympy.abc import x
from sympy.interactive.printing import init_printing
init_printing(use_unicode=False, wrap_line=False)
from sympy import *

y = Function('y')
# Selesaikan ODE
p = x^3*Derivative(y(x), x,x,x) + x^2*Derivative(y(x),x,x)-2*x*Derivative(y(x),x) + 2*y(x)-2*x^4
hasil = dsolve(p, y(x))
print("Higher-order ODE forms:")
display(p)
print("ODE solution:")
display(hasil)
</script

</div>
<br>

</div>

<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>3. Fitting Data to a Mathematical Model</b></h4>

<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
SageMath can be used to fit data to a mathematical model. Here is an example of fitting data to a linear regression model:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
import numpy as np
import matplotlib.pyplot as plt

# Data
x = np.array([1, 2, 3, 4, 5])
y = np.array([5, 2, 6, 7, 10])

# Third degree polynomial linear regression model
a, b, c, d = np.polyfit(x, y, 3) 

# Plot data and models
plt.plot(x, y, 'o')
plt.plot(x, a*x**3 + b*x**2+c*x+d)
plt.show()
</script>
</div>
<br>
<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>4. Optimization</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
SageMath can be used to solve optimization problems, such as finding the maximum or minimum value of a function. Here is an example of finding the maximum value of the function \(f(x) = x^2 - 4x + 3\):
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
import sympy

# function
f = sympy.Function('f')
f(x) = x^2 - 4*x + 3

# Finding the maximum value
x = sympy.Symbol('x')
max_x = sympy.solve(f(x).diff(x) == 0, x)

# Calculating the maximum value
max_value = f(max_x[0])

print("The maximum value of f(x) is", max_value, "for x = ", max_x[0])
</script>
</div>
<br>
<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>5. Mathematical Visualization</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
SageMath can be used to visualize mathematical objects, such as curves, surfaces, and graphs. Here is an example of visualizing a curve:
</p>
<br>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
from sympy import symbols
from sympy.plotting import plot, plot3d, PlotGrid
x, y = symbols('x, y')

p1 = plot((x**2, (x, -6, 6)), (x, (x, -5, 5)))
p2 = plot(x**3, (x, -5, 5))
p3 = plot3d(x*y, (x, -5, 5), (y, -5, 5))

PlotGrid(1, 3, p1, p2, p3)
</script>
</div>
<br>
<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>6. Analyzing a Matrix</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
A square matrix is provided. We will analyze its behavior in a SageMath cell as follows:
</p>
<br>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
A = matrix([[6,-2,-1],[-2,6,-1],[-1,-1,5]])
p = charpoly(A,"lambda")
h = A.eigenvectors_right()
v1 = h[0][1][0]
v2 = h[1][1][0]
v3 = h[2][1][0]
P = matrix([v1,v2,v3])
G,B = P.gram_schmidt()
u1 = G.row(0)
u2 = G.row(1)
u3 = G.row(2)
p1 = u1/norm(u1)
p2 = u2/norm(u2)
p3 = u3/norm(u3)
P = transpose(matrix([p1,p2,p3]))
D = transpose(P)*A*P
a1 = (p1.column())*transpose(p1.column())
a2 = (p2.column())*transpose(p2.column())
a3 = (p3.column())*transpose(p3.column())
x = matrix([[1],[2],[3]])
a1x = a1*x

pretty_print(html(r"Given a <b>symmetric</b> matrix $A=%s$"%latex(A)))
pretty_print(html(r"Characteristic polynomial of the matrix $A$: <center> $p(\lambda)=%s=%s$</center>"%(latex(p),latex(factor(p)))))
pretty_print(html(r"The eigenvalues are obtained: :$\lambda_1=%s,\ \lambda_2=%s$  and $\lambda_3=%s$, always real (because $A$ is <b>symmetric</b>)."%(h[0][0],h[1][0],h[2][0])))
pretty_print(html(r"The eigenvectors corresponding to the eigenvalues: <center> $\mathbf{v_1}=%s,\ \mathbf{v_2}=%s$ and $\mathbf{v_3}=%s$</center>"%(latex(v1.column()),latex(v2.column()),latex(v3.column()))))
pretty_print(html(r"and $\langle\mathbf{v_1,v_2}\rangle=%s,\ \langle\mathbf{v_1,v_3}\rangle=%s,\ \langle\mathbf{v_2,v_3}\rangle=%s$, always <b>orthogonal</b> (because $A$ is <b>symmetric</b>)."%(v1.dot_product(v2),v1.dot_product(v3),v2.dot_product(v3))))
pretty_print(html(r"The normalized vectors $\mathbf{v_1,v_2,v_3}$ are obtained: <center> $\mathbf{u_1}=%s, \mathbf{u_2}=%s, \mathbf{u_3}=%s$</center>"%(latex(p1.column()),latex(p2.column()),latex(p3.column()))))
pretty_print(html(r"and an orthogonal matrix $P=[\mathbf{u_1\ u_2\ u_3}]=%s$"%latex(P)))
pretty_print(html(r"Therefore, $A$ can be diagonalized as follows: \begin{eqnarray*}P'AP &=& %s%s%s\\ &=& %s\end{eqnarray*}"%(latex(transpose(P)),latex(A),latex(P),latex(D))))
pretty_print(html(r"The vectors $\pmb{u}_1, \pmb{u}_2$ dan $\pmb{u}_3$ related to each eigenvalue satisfy: <center> $8\mathbf{u_1u_1'}+6\mathbf{u_2u_2'}+3\mathbf{u_3u_3'}=%s=A$</center>"%latex(8*a1+6*a2+3*a3)))
pretty_print(html(r"Given a vector $\pmb{x} = %s$, it can be shown that the projection of $\pmb{x}$ onto $\langle\pmb{u}_1\rangle$ is $(\pmb{u}_1 \pmb{u}_1')\pmb{x}$ as follows:"%latex(x)))
pretty_print(html(r"<center>$(\pmb{u}_1\pmb{u}_1')\pmb{x} = %s %s = %s$</center>"%(latex(a1),latex(x),latex(a1x))))
pretty_print(html(r"The projection of  $\pmb{x}$ onto $\langle\pmb{u}_1\rangle$ is given by $(\langle\pmb{x},\pmb{u}_1\rangle/\langle\pmb{u}_1,\pmb{u}_1\rangle)\pmb{u}_1$:"))
pretty_print(html(r"that is: <center>$(\langle\pmb{x},\pmb{u}_1\rangle/\langle\pmb{u}_1,\pmb{u}_1\rangle)\pmb{u}_1 = \left\{\begin{pmatrix}1 & 2 & 3\end{pmatrix}\begin{pmatrix}-\frac{1}{\sqrt{2}}\cr \frac{1}{\sqrt{2}}\cr 0\end{pmatrix}\right\}\begin{pmatrix}-\frac{1}{\sqrt{2}}\cr \frac{1}{\sqrt{2}}\cr 0\end{pmatrix}=\begin{pmatrix}-\frac{1}{2}\cr \frac{1}{2}\cr 0\end{pmatrix}$</center>"))
</script>
</div>
<br>

<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>7. Animation Simulation of Taylor Series Expansion</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
We provide the Taylor Series Expansion of the function:
$$
f(x) = e^{-x}\sin(x).
$$
Please click the <b><mark>Enable</mark></b> box and move the slider to the desired order.
</p>
<br>

<div id="taylor" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
x   = SR.var('x')
x0  = 0
f   = sin(x) * e^(-x)
v = []

@interact
def _(order=slider([1 .. 12])):
  p   = plot(f, -1, 5, thickness=2)
  dot = point((x0, f(x=x0)), pointsize=80, rgbcolor=(1, 0, 0))
  ft = f.taylor(x, x0, order)
  pt = plot(ft, -1, 5, color='green', thickness=2)
  pretty_print(html(r'$f(x)\;=\;%s$' % latex(f)))
  pretty_print(html(r'$\hat{f}(x;%s)\;=\;%s+\mathcal{O}(x^{%s})$' % (x0, latex(ft), order+1)))
  v.append(dot + p + pt)
  a = animate(v, figsize=[7,3], xmin=0,xmax=8, ymin=-1, ymax=3) 
  show(a) 
</script>
</div>
<br>
<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>8. Numerical and exact values of an integral</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
To calculate the integral
$$
\int_{0}^{\infty}e^{-x^2} dx
$$
we need the SciPy module <code>scipy.integrate</code>, which contains several integration routines such as the Trapezoidal and Simpson's Rules. The workhorse for numerical integration in Python is the quad function (for quadrature, the traditional term for numerical integration). The quad function itself is not a single method but a collection of routines that work together to achieve an accurate answer efficiently. The algorithm behind quad was originally written in Fortran in a package called QUADPACK. Here is the basic syntax for the quad function:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
import numpy as np
import matplotlib.pyplot as plt
import scipy.integrate as integrate
f = lambda x: np.exp(-x**2)
integral, error = integrate.quad(f, 0, np.inf)
print("The numerical result of the integral is: ",integral)
print("The error value is: ",error)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Next, we calculate the exact value of
$$
\int_{0}^{\infty}e^{-x^2} dx
$$
as well as its numerical value using SageMath as follows:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
ni = integral(exp(-x**2),(x, 0, oo))
ne = ni.n()
pretty_print(html(r"The value of the integral: $$\int_{0}^{\infty}e^{-x^2} dx = %s\ \approx %s.$$"%(latex(ni),latex(ne))))
</script>
</div>
<br>
<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>9. Taylor Series</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Compute and plot the partial sum of the Taylor series for:
$$
\ln(1 + x)
$$
At what value of \(x\) does the Taylor series converge?
<br>
<br>
Recall that the Taylor series for a continuous differentiable function \(f\) expanded about \(x = 0\) (also known as the Maclaurin series) is given by:
\begin{equation}
f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + \frac{f'''(0)}{3!} x^3 + \cdots = \sum_{n=0}^{\infty}\frac{f^{(n)}}{n!}x^n.
\tag{1}
\end{equation}
For the given function, we obtain:
$$
\ln(1 + x) = \sum_{n=1}^{\infty}\frac{(-1)^{n+1}}{n}x^n.\tag{2}
$$
Plotting the graph of \(y=\ln(1 + x)\) together with the partial sums of the Taylor series up to the term \(x^{20}\) is given in the SageMath cell below. Because of the large number of lines, it may be helpful to start plotting only the partial sums up to the \(5\)th and so on. The first few partial sums do not tell you much more than the fact that they are poor approximations.
<br>
<br>
Systematically coloring the different curves can also be helpful. In our plot, we gradually adjust the values of <code>(r, g, b)</code> to make the curves 'bluer' as the number of terms increases (i.e., by increasing the value of <code>b</code> from <code>0</code> to <code>1</code> and keeping <code>r = g = 0</code>).
<br>
The <code>(r, g, b)</code> values are the red, green, and blue components of the color, respectively. By increasing the value of b from \(0\) to \(1\), we are making the curves bluer. Keeping \(r = g = 0\) means that the curves will have no red or green components.
<br>
<br>
From the graph (and further experimentation with the number of terms in the partial sum), we can make the following observations:
<br>
The Taylor series for \(\ln(1+x)\) appears to converge to \(\ln(1+x)\) for \(x\in(−1,1)\), possibly also at \(x=1\).
However, for \(x > 1\), the graphs with a large number of terms \(n\) show divergence (i.e., the \(y\) values become very large around \(x=1\) from the right).
<br>
<br>
<b>Explanation:</b>
<br>
The Taylor series for \(\ln(1+x)\) is given by:
$$
\ln(1 + x) = \sum_{n=1}^{\infty} \frac{(-1)^{n+1}}{n} x^n
$$
This series converges for all values of \(x\) in the interval \((−1,1]\). However, it diverges for all values of \(x\) outside of this interval.
<br>
The graphs in the SageMath cell above show the partial sums of the Taylor series for \(\ln(1+x)\) up to the term-\(x^{20}\). As you can see, the partial sums converge to \(\ln(1+x)\) for \(x\in(−1,1)\). However, they diverge for \(x > 1\).
<br>
This is because the Taylor series for \(\ln(1+x)\) is an alternating series. Alternating series are known to converge if the terms decrease in absolute value and approach zero. However, the terms of the Taylor series for \(\ln(1+x)\) do not decrease in absolute value for \(x > 1\). This is why the series diverges for \(x > 1\).
<br>
<b>Conclusion:</b>
<br>
The Taylor series for \(\ln(1+x)\) converges to \(\ln(1+x)\) for \(x\in(−1,1]\). However, it diverges for \(x > 1\).
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
import matplotlib.pyplot as plt
import numpy as np

def ln(x):
  return sum((-1)**(n+1)/n * x**n for n in range(1, 21))

x = np.linspace(-1, 1, 1000)

for n in range(5, 21):
  y = [sum((-1)**(k+1)/k * xi**k for k in range(1, n+1)) for xi in x]
  
  # Set the color of the curve
  if n == 5:
    color = (0, 0, 0)
  elif n == 10:
    color = (0, 0, 0.25)
  elif n == 15:
    color = (0, 0, 0.5)
  elif n == 20:
    color = (0, 0, 0.75)
  else:
    color = (0, 0, 1)
  
  plt.plot(x, y, color=color, label="Partial sum to $x^{%d}$" % n)

plt.legend()
plt.show()
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
We perform computations with SageMath to determine the Taylor series of the previously discussed function as follows:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
%display latex
f = log(x+1)
g = f.taylor(x, 0,20)
pretty_print(html(r"Taylor series of $y=\ln(1+x)$ is : $$%s$$"%latex(g)))
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Next, we show the graph of the function \(f(x) = \ln(x+1)\) and the graph of \(g(x)\) which is the result of the Taylor series of \(f(x)\):
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
%display latex
f = log(x+1)
g = f.taylor(x, 0,20)

p1 = plot(log(x+1), (x, -0.1, 1),color='red',legend_label=r'$f(x)=\log(x+1)$', legend_color='red')
p2 = plot(g, (x, -0.1, 1),color='green', legend_label=r'$g(x)$', legend_color='green')
(p1 + p2).show(frame=True, axes=False, aspect_ratio=0.75)
</script>
</div>
<br>

<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>10. Plotting 3D surfaces in SageMath</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
SageMath has a great ability to display a surface in 3D. This is very useful for analyzing the behavior of 3D surfaces, especially those related to Differential Geometry. To see the image from different angles, click the left cursor and move it!
</p>

<h5 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>1. Cylinder</b></h5>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
u, v = var('u', 'v', domain='real')
formula = (cos(u), sin(u), v)
parameters = ((u, -pi, pi), (v, -5, 5))
surface = ParametrizedSurface3D(formula, parameters)
show(surface.plot(aspect_ratio=1, color='lightblue'),viewer='threejs')
</script>
</div>
<br>

<h5 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>2. Paraboloid</b></h5>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
u, v = var('u', 'v', domain='real')
formula = (u, v, u^2+v^2)
parameters = ((u, -2, 2), (v, -2, 2))
surface = ParametrizedSurface3D(formula, parameters)
show(surface.plot(aspect_ratio=1, color='lightblue'),viewer='threejs')
</script>
</div>
<br>
<h5 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>3. Sphere</b></h5>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
t, theta = var('t, theta', domain='real')
x(t) = cos(t)
z(t) = sin(t)
formula = (x(t)*cos(theta), x(t)*sin(theta), z(t))
parameters = ((t, -pi/2, pi/2), (theta, -pi, pi))
surface = ParametrizedSurface3D(formula, parameters)
show(surface.plot(aspect_ratio=1, color='lightgrey'),viewer='threejs')
</script>
</div>
<br>
<h5 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>4. Catenoid</b></h5>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
t, theta = var('t, theta', domain='real')
x(t) = cosh(t)
z(t) = t
formula = (x(t)*cos(theta), x(t)*sin(theta), z(t))
parameters = ((t, -3, 3), (theta, -pi, pi))
surface = ParametrizedSurface3D(formula, parameters)
show(surface.plot(aspect_ratio=1, color='yellow'),viewer='threejs')
</script>
</div>
<br>
<h5 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>5. Helicoid</b></h5>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
u, v = var('u', 'v', domain='real')
formula = (u*cos(v), u*sin(v), v)
parameters = ((u, -5, 5), (v, -5, 5))
surface = ParametrizedSurface3D(formula, parameters)
show(surface.plot(aspect_ratio=1, color='yellow'),viewer='threejs')
show(surface.shape_operator())
</script>
</div>
<br>
<h5 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>6. Enneper surface</b></h5>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
u, v = var('u', 'v', domain='real')
formula = (u - u^3/3 + u*v^2, v - v^3/3 + v*u^2, u^2 - v^2)
parameters = ((u, -3, 3), (v, -3, 3))
surface = ParametrizedSurface3D(formula, parameters)
show(surface.plot(aspect_ratio=1, color='orange'),viewer='threejs')
</script>
</div>
<br>
<h5 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>7. 600-cells polytope</b></h5>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
These are two different Schlegel projections. The first is projected onto an icosahedron. The SageMath code is below the diagram.
</p>

<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
show(polytopes.six_hundred_cell()
     .plot(color='grey', projection_direction=[1,1,1,1], radius=0.01, frame=False),
     viewer='threejs', online=True)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
show(polytopes.six_hundred_cell()
     .plot(color='blue', radius=0.01, frame=False),
     viewer='threejs', online=True)
</script>
</div>
<br>

<h4 style='text-align: justify;margin-left:220px;margin-right:25px;'> <b>11. Data Fitting with SageMath</b></h4>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
A common situation in science and engineering: you have collected a bunch of data and you want to fit a function to it. SageMath trivializes this procedure.
<br>
First, we will create some data that has some inherent variance using list comprehension and the <code>normalvariate()</code> function and store it in the array <code>data</code>; then we will propose a model with some adjustable parameters, and find the parameter values that fit best. Finally, we will plug those parameter values back into the model and plot it alongside the data.
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# for this example, we first create some data with built-in variance:
data = [(i, 1.2 * sin(0.5*i-0.2) + 0.1 * normalvariate(0, 1)) for i in xsrange(0, 4*pi, 0.2)]

# design a model with parameters a,b,c that can be adjusted and describe the data
var('a, b, c, x')
model(x) = a * sin(b * x - c)

# calculate the parameter values that best fit the model and data
sol = find_fit(data,model)
show(sol)

# determine f(x), a model with parameters set to appropriate values
f(x) = model(a=sol[0].rhs(),b=sol[1].rhs(),c=sol[2].rhs())

# creates an empty plot object
a = plot([])
# Add a plot of the model, against x from -0.5 to 12.5
a += plot(f(x),x,[-0.5,12.5])

# add data plot, colored red
a += list_plot(data,color='red')
show(a)
</script>
</div>
  
</section>
<hr class="horizontal-line">


<section id="CGASagM">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>9. Cayley graph of an Abelian group using SageMath</h2>
<hr class="horizontal-line">
  <p class="ex1" style='text-align: justify;margin-left:220px;margin-right:25px;'>
A natural source of graphs, known as <span class="tooltip1"><b>Cayley graphs</b>,<span class="tooltiptext"> In mathematics, a Cayley graph, also known as a Cayley color graph, Cayley diagram, group diagram, or color group, is a graph that encodes the abstract structure of a group. Its definition is suggested by Cayley's theorem (named after Arthur Cayley), and uses a specified set of generators for the group. It is a central tool in combinatorial and geometric group theory. The structure and symmetry of Cayley graphs makes them particularly good candidates for constructing expander graphs. <a href="https://en.wikipedia.org/wiki/Cayley_graph" target="blank"><mark>[Source]</mark></a></span></span> comes from group theory. <span class="tooltip1"><b>Representation theory</b><span class="tooltiptext"> Representation theory is a branch of mathematics that studies abstract algebraic structures by representing their elements as linear transformations of vector spaces, and studies modules over these abstract algebraic structures. In essence, a representation makes an abstract algebraic object more concrete by describing its elements by matrices and their algebraic operations (for example, matrix addition, matrix multiplication). The theory of matrices and linear operators is well-understood, so representations of more abstract objects in terms of familiar linear algebra objects helps glean properties and sometimes simplify calculations on more abstract theories. <a href="https://en.wikipedia.org/wiki/Representation_theory" target="blank"> <mark>[Source]</mark> </a></span></span> motivates us to analyze the eigenvalues of Cayley graphs at least for Abelian groups.
<br>
<br>
<b>Definition</b>
<br>
Let \(G\) be a  <span class="tooltip1"><b>finite group.</b><span class="tooltiptext"> In abstract algebra, a finite group is a group whose underlying set is finite. Finite groups often arise when considering symmetry of mathematical or physical objects, when those objects admit just a finite number of structure-preserving transformations. Important examples of finite groups include cyclic groups and permutation groups. The study of finite groups has been an integral part of group theory since it arose in the 19th century. One major area of study has been classification: the classification of finite simple groups (those with no nontrivial normal subgroup) was completed in 2004. <a href="https://en.wikipedia.org/wiki/Finite_group" target="blank"> <mark>[Source]</mark> </a></span></span> A symmetric subset of \(G\) is a subset \(S\subseteq G\) that satisfies the following conditions:
</p>
<ol style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>The identity element \(1\) is not in \(S\).</li>
<li>If \(s\) is in \(S\), then the inverse \(s^{-1}\) is also in \(S\).
</ol>
<p class="ex1" style='text-align: justify;margin-left:220px;margin-right:25px;'>
If \(S\) is a symmetric subset of \(G\), then the graph of \(G\) associated with \(S\) is the graph with vertex set \(G\) and with an edge \(\{g,h\}\) connecting \(g\) to \(h\) if and only if \(gh^{-1}\in S\) or equivalently \(hg^{-1}\in S\).
<br>
In other words, the graph of \(G\) associated with \(S\) is the graph that has a vertex for each element of \(G\) and an edge between two vertices \(g\) and \(h\) if and only if \(gh^{-1}\in S\) or \(hg^{-1}\in S\).
<br>
<br>
This graph is called the <b>Cayley graph</b> of G with respect to \(S\). It is a useful tool for studying the properties of \(G\). For example, the diameter of the Cayley graph is equal to the length of the longest word in \(G\).
<br>
<br>
<b>Note</b>: In the definition, \(S\) can be the empty set. In this case, the Cayley graph has no edges. Also, as is known, any finite group \(G\) is isomorphic to a permutation group \(G_p\). Therefore, to determine the graph of a group \(G\), we do it through the 
<span class="tooltip3"><b>permutation group</b><span class="tooltiptext"> In mathematics, a permutation group is a group \(G\) whose elements are permutations of a given set \(M\) and whose group operation is the composition of permutations in \(G\) (which are thought of as bijective functions from the set \(M\) to itself). The group of all permutations of a set \(M\) is the symmetric group of \(M\), often written as Sym(\(M\)). The term permutation group thus means a subgroup of the symmetric group. If \(M = \{1, 2,\ldots, n\}\) then Sym(\(M\)) is usually denoted by \(S_n\), and may be called the symmetric group on \(n\) letters. By Cayley's theorem, every group is <b>isomorphic</b> to some permutation group. The way in which the elements of a permutation group permute the elements of the set is called its group action. Group actions have applications in the study of symmetries, combinatorics and many other branches of mathematics, physics and chemistry.  <a href="https://en.wikipedia.org/wiki/Permutation_group" target="blank"> <mark>[Source]</mark> </a></span></span> \(G_p\).
<br>
<br>
We can verify that the Cayley graph is connected (every two vertices are connected by a path) if and only if \(S\) <b>generates</b> \(G\).
<br>
<br>
<b>Example</b><br>
Let \(G=\mathbb{Z}/ 4\mathbb{Z}\) and \(S=\{\pm [1]_4\}\). To obtain the Cayley graph associated with \(S\); in SageMath cell, do the following:
<br>
1. Create the Abelian group \(G=\mathbb{Z}/ 4\mathbb{Z}\).<br>
2. Construct the permutation group \(G_p\) from the Abelian group \(G\).<br>
3. Determine the generators of the group \(G_p\).<br>
​4. From the available generators, create the symmetric set \(S\).<br>
5. Associated with the group \(G_p\), create the adjacency matrix \(A\) with the generator \(S\).<br>
6. From the adjacency matrix \(A\), create the Cayley graph.<br>
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([4])
G1 = Set(G.list())
Gp = G.permutation_group()
Gp1 = Set(Gp.list())
g0= Gp.gens()
g1=g0[0]
S=[g1,g1^-1]
S1=set(S)
A = Gp.cayley_graph(generators=S,simple=True).adjacency_matrix()
Gamma = Graph(A)
pretty_print(html(r" $G = \{%s\}$"%G1))
pretty_print(html(r" $G_p = \{%s\}$"%Gp1))
pretty_print(html(r"A generator of group $G_p$ is:  $%s$"%g0[0]))
pretty_print(html(r"Simmetric set: $S = \{%s\}$"%S1))
pretty_print(html(r"Adjacency matrix $A=%s$"%latex(A))) 
pretty_print(html(r"Graph $\Gamma$ of adjacency matrix $A$ :"))
Gamma.show(layout="circular",dpi = 60)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The SageMath commands for generating a <b>Cayley graph</b> can be a bit tricky. We want to make sure to select the "simple" option and to choose a symmetric generating set, as shown in the two examples below of Cayley graphs of the Abelian group \(\mathbb{Z}/6\mathbb{Z}\) for the symmetric sets \(S_1=\{\pm 1,\pm 2\}\) and \(S_2=\{\pm 1,\pm 3\}\): 
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([6])
G1 = Set(G.list())
Gp = G.permutation_group()
Gp1 = Set(Gp.list())
g1,g2 = Gp.gens()
S1=[g1*g2,(g1*g2)^-1,(g1*g2)^2,(g1*g2)^-2]
A1 = Gp.cayley_graph(generators=S1,simple=True).adjacency_matrix()
Gamma1 = Graph(A1)

pretty_print(html(r" $G = \{%s\}$"%G1))
pretty_print(html(r" $G_p = \{%s\}$"%Gp1))
pretty_print(html(r"Simmetric set $S_1 = \{%s\}$"%set(S1)))
pretty_print(html(r"Adjacency matrix  $A_1 = %s$"%latex(A1)))
pretty_print(html(r"Graph $\Gamma_1$ of Adjancency matrix $A_1$ :"))
Gamma1.show(layout="circular", dpi = 60)
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([6])
G1 = Set(G.list())
Gp = G.permutation_group()
Gp1 = Set(Gp.list())
g1,g2 = Gp.gens()
S2=[g1*g2,(g1*g2)^-1,(g1*g2)^3,(g1*g2)^-3]
A2 = Gp.cayley_graph(generators=S2,simple=True).adjacency_matrix()
Gamma2 = Graph(A2)

pretty_print(html(r" $G = \{%s\}$"%G1))
pretty_print(html(r" $G_p = \{%s\}$"%Gp1))
pretty_print(html(r"Simmetric set $S_2 = \{%s\}$"%set(S2)))
pretty_print(html(r"Adjacency matrix  $A_2 = %s$"%latex(A2)))
pretty_print(html(r"Graph $\Gamma_2$ of adjancency matrix $A_2$ :"))
Gamma2.show(layout="circular", dpi = 60)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Next, we discuss the Cayley graph \(\Gamma\) of \(\mathbb{Z}/4\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}\), with the generator set \(S=\{±(0,1),±(1,0),±(1,1)\}\). We implement this in SageMath as follows:
<br>
<br>
Here is the SageMath code that implements the Cayley graph \(\Gamma\):
</p>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([4,4])
G1 = Set(G.list())
GP = G.permutation_group()
GP1 = Set(GP.list())
g0 = GP.gens()[0]
g1 = GP.gens()[1]
S = [g0,g1, g0^(-1), g1^(-1),(g0*g1)^(-1),g0*g1]
s1 = Set(S)
Gamma = GP.cayley_graph(side='left', generators = S)
A = Gamma.adjacency_matrix()
Gamma1 = Graph(A, format = "adjacency_matrix")
Gam = Gamma1.show(layout="circular", dpi = 70)

pretty_print(html(r"The Cayley graph $\Gamma$ of group $\mathbb{Z}/4\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}$ generated by $S$"))
Gam
pretty_print(html(r"$S = \{%s\}$"%s1))
pretty_print(html(r"$\mathbb{Z}/4\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z} = \{%s\}$"%G1))
pretty_print(html(r"<b>It should be noted here that:</b>: $\mathbb{Z}/4\mathbb{Z}\times\mathbb{Z}/4\mathbb{Z}\cong G_p =$ <center>$\{%s\}$</center>"%GP1))
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The following shows the Cayley graph of the group \(\mathbb{Z}/24\mathbb{Z}\) with the symmetry set \(S=\{[8]_{24},[16]_{24},[3]_{24},[21]_{24}\}\).
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([24])
Gp = G.permutation_group()
g1,g2 = Gp.gens()
S2 = [g1,g1^-1,g2,g2^-1]
A2 = Gp.cayley_graph(generators=S2,simple=True).adjacency_matrix()
Gamma2 = Graph(A2)
pretty_print(html(r"Adjacency matrix $A_2 = %s$"%latex(A2)))
pretty_print(html(r"Graph $\Gamma$ of the adjacency_matrix $A_2$ :"))
Gamma2.show(layout="circular", dpi = 60)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The following shows the Cayley graph of the group \(\mathbb{Z}/24\mathbb{Z}\) with the symmetry set 
$$
S_1=\{\pm [2]_{24},\pm [4]_{24},\pm [6]_{24},\pm [8]_{24},\pm [10]_{24}\}.
$$
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([24])
Gp = G.permutation_group()
g1,g2 = Gp.gens()
S1 = [(g1*g2)^2,(g1*g2)^-2,(g1*g2)^4,(g1*g2)^-4,(g1*g2)^6,(g1*g2)^-6,\
      (g1*g2)^8,(g1*g2)^-8,(g1*g2)^10,(g1*g2)^-10]
A1 = Gp.cayley_graph(generators=S1,simple=True).adjacency_matrix()
Gamma1 = Graph(A1)
p1=Gamma1.characteristic_polynomial().factor()
pretty_print(html(r"Adjacency matrix $A_1 = %s$"%latex(A1)))
pretty_print(html(r"The characteristic polynomial of the graph $\Gamma_1 = %s$"%latex(p1)))
pretty_print(html(r"Graph $\Gamma_1$ of the adjacency matrix $A_1$ :"))
Gamma1.show(layout="circular", dpi = 70)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The following shows the Cayley graph of the group \(\mathbb{Z}/24\mathbb{Z}\) with the symmetry set 
$$
S_2=\{\pm [2]_{24},\pm [4]_{24},\pm [6]_{24},\pm [8]_{24},\pm [10]_{24},\pm [12]_{24}\}.
$$
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([24])
Gp = G.permutation_group()
g1,g2 = Gp.gens()
S2 = [(g1*g2)^2,(g1*g2)^-2,(g1*g2)^4,(g1*g2)^-4,(g1*g2)^6,(g1*g2)^-6,\
      (g1*g2)^8,(g1*g2)^-8,(g1*g2)^10,(g1*g2)^-10,(g1*g2)^12,(g1*g2)^-12]
A2 = Gp.cayley_graph(generators=S2,simple=True).adjacency_matrix()
Gamma2 = Graph(A2)
p2=Gamma2.characteristic_polynomial().factor()
pretty_print(html(r"Adjacency matrix $A_2 = %s$"%latex(A2)))
pretty_print(html(r"The characteristic polynomial of the graph $\Gamma_2 = %s$"%latex(p2)))
pretty_print(html(r"Graph $\Gamma_2$ of the adjacency matrix $A_2$ :"))
Gamma2.show(layout="circular", dpi = 70)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
At first glance, graphs \(\Gamma_1\) and \(\Gamma_2\) appear to be the same. However, they are actually different, as evidenced by their distinct characteristic polynomials. Furthermore, it can be demonstrated that graphs \(\Gamma_1\) and \(\Gamma_2\) are not isomorphic, and thus \(\Gamma_1\) and \(\Gamma_2\) are indeed different. We will show this as follows:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = AdditiveAbelianGroup([24])
Gp = G.permutation_group()
g1,g2 = Gp.gens()
S1 = [(g1*g2)^2,(g1*g2)^-2,(g1*g2)^4,(g1*g2)^-4,(g1*g2)^6,(g1*g2)^-6,\
      (g1*g2)^8,(g1*g2)^-8,(g1*g2)^10,(g1*g2)^-10]
S2 = [(g1*g2)^2,(g1*g2)^-2,(g1*g2)^4,(g1*g2)^-4,(g1*g2)^6,(g1*g2)^-6,\
      (g1*g2)^8,(g1*g2)^-8,(g1*g2)^10,(g1*g2)^-10,(g1*g2)^12,(g1*g2)^-12]
S1 = [(g1*g2)^2,(g1*g2)^-2,(g1*g2)^4,(g1*g2)^-4,(g1*g2)^6,(g1*g2)^-6,\
      (g1*g2)^8,(g1*g2)^-8,(g1*g2)^10,(g1*g2)^-10]
A1 = Gp.cayley_graph(generators=S1,simple=True).adjacency_matrix()
Gamma1 = Graph(A1)
A2 = Gp.cayley_graph(generators=S2,simple=True).adjacency_matrix()
Gamma2 = Graph(A2)
a = Gamma1.is_isomorphic(Gamma2)

pretty_print(html(r"Are $\Gamma_1$ and $\Gamma_2$ isomorphic? $%s$"%latex(a)))
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
To get complete information about a graph in SageMath Cell, use the command <code>Graph?</code>.
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
Graph?
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Before we conclude our discussion of Cayley graphs, let us introduce a different topic from before: Cayley graphs generated from a non-commutative group. For example, if G is a group and \(C\subseteq G\) (i.e., a list of some elements of \(G\)), then we can generate the Cayley graph \(X(G,C)\) as follows:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = DihedralGroup(5)
C = [G.gen(0), G.gen(1)]
CG = G.cayley_graph( generators = C)
CG.show(dpi = 80)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
The output is a directed graph, even if \(C\) is closed under inversion; in the latter case we can turn \(G\) into a graph as follows:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = DihedralGroup(5)
C = [G.gen(0), G.gen(1)]
CG = G.cayley_graph( generators = C)
CGU = CG.to_undirected()
CGU.show(dpi = 80)
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Note that C is not required to construct G. There are a number of keywords for this command (e.g., side and simple).
<br>
<br>
Also, note that the command <code>_Graph()</code> makes it easy to create your own Cayley graphs. For example, the cube-like graph is the Cayley graph for \(GF(2)^d\). We can construct it using the command <code>_Graph()</code>. In the following example, <code>_vector_list_</code> is a list of \(01\)-vectors of length \(d\).
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
def cubelike(d, vector_list):
    VS = VectorSpace(GF(2),d)
    vxs = range(2^d)
    return Graph([vxs, lambda i,j: VS[i]-VS[j] in vector_list])

V = GF(2)^5
vl = [V([0,1,1,0,0]), V([1,1,0,1,1]), V([1,0,0,0,1])]         
T = cubelike(5, vl)                                   
show(T, layout='circular') 
</script>
</div>
<br>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
For a general group, we can use the following construction to create an undirected Cayley graph.
</p>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
G = DihedralGroup(6)
C = [G.gen(0), G.gen(0)^-1, G.gen(1), G.gen(1)^-1]
CG = Graph( [ G.list(), lambda g, h: h*g^(-1) in C])
CG.show()
</script>
</div>
<br>
<p class="ex1" style='text-align: justify;margin-left:220px;margin-right:25px;'>
We can also use a <span class="tooltip3"><b>free group</b><span class="tooltiptext"> In mathematics, the free group \(F_S\) over a given set \(S\) consists of all words that can be built from members of \(S\), considering two words to be different unless their equality follows from the group axioms (e.g. \(st = suu^{-1}t\) but \(s\neq t^{-1}\) for \(s,t,u\in S\)). The members of \(S\) are called generators of \(F_S\), and the number of generators is the rank of the free group. An arbitrary group \(G\) is called free if it is isomorphic to \(F_S\) for some subset \(S\) of \(G\), that is, if there is a subset \(S\) of \(G\) such that every element of \(G\) can be written in exactly one way as a product of finitely many elements of \(S\) and their inverses (disregarding trivial variations such as \(st = suu^{-1}t\)). <a href="https://en.wikipedia.org/wiki/Free_group" target="blank"> <mark>[Source]</mark> </a></span></span> \(G\) generated by elements through a set of relations to construct a Cayley graph. Here is an example:
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
F.<a,b> = FreeGroup()
G = F/[a^2, b^2,a*b*~a*~b]
Gp=G.as_permutation_group()
gen = [G.gen(0), G.gen(1)]
CG = Gp.cayley_graph( generators = gen)

pretty_print(html(r"Free group $G = %s$"%latex(G)))
pretty_print(html(r"Permutation group of $G$: $G_p = %s$ "%latex(Gp)))
print()
CG.show()
</script>
</div>
<br>
<p class="ex1" style='text-align: justify;margin-left:220px;margin-right:25px;'>
We will next illustrate the concept of a <span class="tooltip2"><b>total graph</b><span class="tooltiptext"> The total graph \(T = T(G)\) of a graph G is a graph such that (i) the vertex set of \(T\) corresponds to the vertices and edges of \(G\) and (ii) two vertices are adjacent in \(T\) if and only if their corresponding elements are either adjacent or incident in \(G\). <a href="https://en.wikipedia.org/wiki/Total_coloring" target="blank"> <mark>[Source]</mark> </a></span></span> for a ring. Here's an example for the ring of integers modulo \(R\), along with the corresponding SageMath code.
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# Importing required libraries
from sage.graphs.graph import Graph

n = 4 # you can change the value of integer n > 1

# Define the ring Z_n
R = Integers(n)

# Get the elements of the ring
elements = list(R)

# Create the total graph
total_graph = Graph()

# Add vertices to the graph
total_graph.add_vertices(elements)

# Add edges between all pairs of vertices
for i in range(len(elements)):
    for j in range(i + 1, len(elements)):
        total_graph.add_edge(elements[i], elements[j])

# Plot the total graph
total_graph.show(layout='circular')
</script>
</div>
</section>
<hr class="horizontal-line">

<section id="SagMathfP">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>10. SAGEMATH CELL FOR PRACTICE!</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
<blockquote style='text-align: justify;margin-left:220px;margin-right:25px;'>We provide ten SageMath Cells that you can use as practice to <b>verify mathematical theories</b> learned in lectures!
</blockquote>
</p>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
0+1
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3+4
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3+4+5
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3+4+5+6
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3+4+5+6+7
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3+4+5+6+7+8
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3+4+5+6+7+8+9
</script>
</div>
<br>
<div class="compute" style='text-align: justify;margin-left:220px;margin-right:25px;'>
<script type="text/x-sage">
# This Sagemath cell is provided for practice!
1+2+3+4+5+6+7+8+9+10
</script>
</div>

<hr class="horizontal-line">


<section id="JupNot">
  <h2 style='text-align: justify;margin-left:220px;margin-right:25px;'>11. JupyterLab and Jupyter Notebooks</h2>
<hr class="horizontal-line">
  <p style='text-align: justify;margin-left:220px;margin-right:25px;'>
  <b>JupyterLab</b> is a next-generation web-based user interface for Project Jupyter. It enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner. It is the interface that you're looking at right now.
  <br>
  <br>
  <b>Jupyter Notebooks</b> are a community standard for communicating and performing interactive computing. They are a document that blends computations, outputs, explanatory text, mathematics, images, and rich media representations of objects
  <br>
  <br>
  To start a Jupyter notebook, click the <mark><b>File</b></mark> menu, then select <mark><b>New</b></mark> and <mark><b>Notebook</b></mark>.
  <br>
  <br>
  To carry out activities in Jupyter Notebook, click <mark><b>Code</b></mark> and choose one option: <mark><b>Code</b></mark>, <mark><b>Markdown</b></mark>, or <mark><b>Raw</b></mark>.
  <br>
  <br>
  In Jupyter Notebook, cells containing code are called <b>code cells</b>. These cells are where you write and execute programming instructions. The default kernel in Jupyter Notebook typically runs <b>Python</b> code, but you can use other languages depending on the chosen kernel. Here are some key points about code cells:
</p>
<ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li>They allow multiline text input with syntax highlighting for easier code readability.</li>
<li>You can run the code in a cell by using the "Run" button, keyboard shortcuts (like Shift+Enter), or selecting the option from the "Cell" menu.</li>
<li>The output from the code execution, such as text, plots, or tables, is displayed below the code cell.</li>
</ul>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
Jupyter Notebook also offers other cell types for different purposes:
</p>
<ul style='text-align: justify;margin-left:220px;margin-right:25px;'>
<li><b>Markdown cells</b>: Used for formatted text explanations, notes, or documentation within the notebook using Markdown syntax.</li>
<li><b>Raw cells</b>: Intended for arbitrary content that isn't evaluated by the kernel. They are useful for including things like system commands or notes that you don't want to execute.</li>
</ul>
<p style='text-align: justify;margin-left:220px;margin-right:25px;'>
If you need help with Jupyter Notebook, click <b><mark>Help</mark></b> and select the information you need.
<br>
<br>
This section provides access to computing facilities through a Jupyter notebook. To deepen your understanding of Jupyter notebooks' role in mathematics, particularly mathematical modeling, we've included the "<b>On-Jupyter-Maths.ipynb</b>" file. Click on this file to launch it in the Jupyter Notebook environment and explore the concepts discussed.
</p>
<br>
<center style='text-align: justify;margin-left:220px;margin-right:25px;'>
<iframe src="https://jupyterlite.github.io/demo/lab/index.html" width="100%" height="500" style="border:1px solid black;">">
</iframe>
</center>
</section>
<hr class="horizontal-line">
</section>
</body>
</html>
