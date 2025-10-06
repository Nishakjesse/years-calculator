# years-calculator
calculates the years,month and weeks of life remainng for someone if they ever reach the age of 90years
print("welcome to the \"life in weeks\"calculator")
age=int(input("what is your age in years?"))
years_remaining=90-age
months_remaining=years_remaining*12
weeks_remaining=years_remaining*52
days_remaining=years_remaining*365
print(f"you have {years_remaining}years or {weeks_remaining}weeks or {days_remaining}days")
