# Non-linear datasets need non-linear SVM models. 
# Linear data can be separated with a line but non-linear not. 
# Because of that, we need to add an additional dimension to make the non-linear data seperable. 
# As a result, we use SVM models. 
# Like the other classification algorithms, SVM also have some disadvantages. 
# As an example, more dimension brings curse of dimensionality. 
# That curse describes the difficulty of the analysis. 
# For an another example, SVM works for only two class separation. 
# It cannot separate more than two classes. 
# That does not mean you cannot fit multi-class datasets to an SVM model, of course you can fit to it. 
# But it will work with principle “One-to-One” or “One-to-Rest”. 
# So, at the end, you will get only two separated part.
