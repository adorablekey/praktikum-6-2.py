# praktikum-6-2.py
# nama : keysia nurhayati boru panjaitan
# Nim : 312410350
# kelas  : TI 24.A4
# mata kulia : bahasa pemograman
# latihan 1
![image](https://github.com/user-attachments/assets/0b50551b-5c3a-4e26-b8df-ebc82836fa75)
# latihan 1 .py
      import math

         a = lambda x: x**2
         b = lambda x, y: math.sqrt(x**2 + y**2)
         c = lambda *args: sum(args)/len(args) if args else 0
         d = lambda s: "".join(set(s)) 

          print("lambda a(5):", a(5))
          print("lambda b(3, 4):", b(3, 4))
          print("lambda c(1, 2, 3, 4, 5):", c(1, 2, 3, 4, 5))
          print("lambda d('hello keysia'):", d("keysia"))
