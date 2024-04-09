Created: April-09-2024

CLA Adders are a better way to add bits. Because it doesn't contain the propagation delay among calculating Sum and Carry.

CLA Adders take the approach of predicting the Carry.

We have,

$C_o$ = A.B + A $\oplus$ B . $C_i$
$\implies$ $C_o$ = G + P.$C_i$

where,

G = Carry generator
P = Carry predictor

# Related Notes

1. [[Digital Electronics]]
# References

1. 