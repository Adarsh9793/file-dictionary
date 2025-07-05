# file-dictionary
normal dictionary program

marks = {"Raj": 45, "Ravi": 78, "Rani": 89, "Ravi": 90, "Rani": 67, "Raj": 56, "Ravi": 45}
print(marks.items())
print(marks.keys())
print(marks.values())   
marks.update({"Ravi": 90,"Raj":34})
print(marks)

print(marks.get("Ravi"))

        #OR

print(marks["Ravi"])
