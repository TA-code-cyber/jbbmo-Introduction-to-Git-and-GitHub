#1/bin/bash
# This script calculate simple interest given pricipals,
# annual rate of interest and time rate in years,

# Do not used this in production. Sample purpose only

# Arthur: Upkar Liddler (IBM)
# Additional Aarthurs:
# <TA-cyber-code>

# Input:
# p, principa; amount
# t, time in years
# r, annual rate of interest

# output:
# simple interest = p*t*r

echo "Enter the principla :"
read p
echo "Enter rate of interest per year :"
read r
echo "Enter time period in years :"
read t

s=' ex[r $p \* $t \*$r /100'
echo "the simple interest is :"
echo $s
