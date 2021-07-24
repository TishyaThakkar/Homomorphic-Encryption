# Homomorphic-Encryption
The project consists of a Data Owner and Data Scientist. The Data Owner seeking to
perform machine learning or deep learning on his sensitive data uses Federated
Learning to allow access to only specific parts of the data needed for model creation.
The Data Scientist Creates and hosts the model himself. The Data Owner encrypts the
data needed to be inferred from the model and sends it to the Data Scientist who then
Infers the encrypted data and sends the encrypted result back to the Data Owner.
The Data owner then Decrypts the result. The project is implemented using python and 
it's libraries such as PySyft, Duet, Tenseal, PyTorch.
