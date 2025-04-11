name = input('Enter your Name = ')
yearOfBirth = int(input('Enter your year of birth = '))
currentYear = int(input('Enter the current year = '))
age=currentYear-yearOfBirth
if(age>=60):
    print(name+'is a  senior citizen')
else:
    print(name+'is not a senior citizen')
