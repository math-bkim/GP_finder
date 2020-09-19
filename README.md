# GP_finder

This is an algorithm based on a generic algorithm and reinforced learning. 
For given n, it tries to find an integer partition such that the reciprocal sum of parts equals one.

For example, 
4 = 2+2
and
1 = 1/2 + 1/2.

For more examples, see the text files.

There should be such a partition for n > 23.
The algorithm works well for small numbers, say less than 500.
If it runs with larger initial population, it works better.

We may give a list of parts which should be in the partition. For this case, there is no garantee that there is such a partition in general.

Policy network (actor) is trained using TD3 alorithm and a trained agent (test_policy) is included.
I use TD3 paper's authors code from
https://github.com/sfujim/TD3/blob/master/TD3.py


Dependency: Python 3.6 and Pytorch 1.6
