Objective: To identify whether a name is human name (i.e. Sandy Wang) or a functional account name (a.k.a service account, admin account name) like Admin1,
TestingAccount, etc...

Steps Overview:
1- Use FakeName generator with a wide range of English dialects to generate 100k human names (First Name + Last name)
2- Use FakeName generator, in combination of a dataset of sample functional account names, to generate 100k of these
3- Tokenize these names
4- Train a Sequential Text processing model from Tensorflow
5- Achieved 99.6% accuracy from model testing, and 100% from an actual dataset

