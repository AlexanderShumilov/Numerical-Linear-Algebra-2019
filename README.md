# Numerical-Linear-Algebra-2019

HW1:
77/97

-2 pts. build_X() naive loop would be more efficient.
-1 pts. test_x and predicted have different sizes

Problem 4.
2) Wrong multiplication of compressed matrix representation: several multiplications of vector by matrix is much faster the several matrix by matrix multiplications and then one matrix by vector multiplication: -5 pts
3) No correct plots

HW2:
121.5/145

Problem 3
37/45

* Small deficiency in theoretical proof (-2)
* Did not show, that critical point is maximum

* Wrong corpus construction (-2)
* Wrong window slicing
* SPPMI matrix is not sparse by construction (-4)

Problem 2. 
-5 pts gram_schmidt_qr() is wrong (test failed), check np.linalg.norm(A - Q @ R) for random matrix A. -6 pts delete_column_QR() and insert_column_QR() are wrong, check np.allclose(R_hat, np.triu(R_hat)) and np.allclose(R_tilde, np.triu(R_tilde)), they are not triangluar. -1 pts delete_row_QR() modifying elements that are known to be zero.
