# dictionary operations
person= {'name':'vinay', "age":22, 'city':'vizag'}
print(person)
print("accessing and modify the person age:")
person ["age"]= 22
print(person)
print("adding and removing items")
person['email']= 'cheepurapallivinay123@gmail.com'
print(person)
del person['city']
print(person)
print("All keys & values")
print(person.keys())
print(person.values())
print(person.items())
print(person.get("age"))
