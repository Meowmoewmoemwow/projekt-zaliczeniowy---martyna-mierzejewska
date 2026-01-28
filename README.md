# projekt-zaliczeniowy---martyna-mierzejewska
zadania: paris, 3D surface area, extra long factorials
#!/bin/python3

import math
import os
import random
import re
import sys


#
# Complete the 'extraLongFactorials' function below.
#
# The function accepts INTEGER n as parameter.
#

def extraLongFactorials(n):
    # Write your code here
    res = 1
    while (n != 0):
        res *= n
        n -= 1
    return res


if __name__ == '__main__':
    n = int(input().strip())

    print(extraLongFactorials(n))
