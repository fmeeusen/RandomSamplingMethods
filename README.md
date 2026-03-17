# RandomSamplingMethods
A research project I did for my BSc level Theory of Statistics and Data analysis course.
Please have a look at the report before trying to figure out the code


The field of random number generation algorithms describes procedures for generating independent observations from a particular standard distribution, such as the Normal or Poisson distribution. These random samples can be used as an important tool for various applications in fields such as, statistics, physics, computer science and engineering.

Most modern computer software packages are already equipped with functions that can generate random samples from a whole variety of distributions. However,  it is still useful and interesting to know how these functions exactly generate these samples, since the choice of sampling algorithm or function depends on the specific requirements of the desired distribution and the limitations of each algorithm.  

Note that most software packages are also capable of generating pseudo-random real numbers. These are real numbers that seem to be random but are actually generated using deterministic procedures, as this is the way for computers to operate. However, from a practical point of view, these numbers can be treated to be truly random.  Taking advantage of this property, it is possible to create an Uniform distribution with a range between 0 and 1. The random number generating algorithms describe a set of steps to transform this created random Uniform distribution into the distribution that is desired . 

Some standard distributions, such as the Bernoulli and Binomial, can be derived by Additive sampling methods: iteratively adding or subtracting a simple transformation of the basic distribution that is easier to sample from, i.e., the uniform distribution in this case. However, this approach does not work for every distribution, and for these cases other methods are needed.    
Common random number-generating algorithms that can be used for these distributions include the Inverse Transform Method, the Box-Mueller Transform, and the Accept and Reject Method. The explanation and limitations behind each of these methods will be discussed in this report along with a number of examples to show their performance which are simulated in _Mathematica_. 
