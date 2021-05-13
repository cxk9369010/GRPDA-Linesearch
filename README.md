# GRPDA-Linesearch


Xiaokai Chang, Junfeng Yang, Hongchao Zhang. Golden ratio primal-dual algorithm with linesearch, manuscript, 2021


We propose a linesearch strategy for GRPDA, which not only does not require the spectral norm of the linear transform but also allows adaptive and potentially much larger stepsizes. Within each linesearch step, only the dual variable needs to be updated, and it is thus quite cheap and does not require any extra matrix-vector multiplications for many special yet important applications, e.g., regularized least squares problem.
