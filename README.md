from sklearn.preprocessing import OneHotEncoder

Education = [["bachelor"],["Master"],["PhD"]]

Experience_Years=[["2"],["5"],["7"]]

encoder = OneHotEncoder()

result = encoder.fit_transform(Education)

print(result.toarray())
