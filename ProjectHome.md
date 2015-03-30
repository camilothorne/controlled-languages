These scripts analyze the distribution of controlled languages in (raw) corpora. The fragments themselves are approximated using the [Boxer](http://svn.ask.it.usyd.edu.au/trac/candc/wiki/boxer) semantic parser. They also:
  * generate the bar chart of the distribution,
  * perform a log-log regression to test for power law distributions, and
  * run statistical significance tests.

They depend on Python 2.6.x and the scipy, numpy matplotlib and nltk libraries.

For a full description of the the experiments, please refer to my paper: http://camilothorne.altervista.org/perso/isa8-thorne.pdf