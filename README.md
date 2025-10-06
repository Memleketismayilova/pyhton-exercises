# pyhton-exercises
Basic Python tasks solved with recursion and conditions

# exercise 1
# Ən azı bir ədəd müsbət və ən azı biri mənfidirsə → YES, əks halda → NO.
a, b, c = map(int, input().split())

if (a > 0 or b > 0 or c > 0) and (a < 0 or b < 0 or c < 0):
    print("YES")
else:
    print("NO")



# exercise 2
# Üçrəqəmli ədədin bütün rəqəmləri fərqlidirsə YES, əks halda NO.
n = input().strip()

if len(set(n)) == 3:
    print("YES")
else:
    print("NO")



# exercise 3
# İki ədəd arasında yerləşən tam ədədlərin sayını tap.
a, b = map(int, input().split())

print(abs(a - b) - 1)



# exercise 4
# Dörd ədəd arasında ən böyüyünü tap.
a, b, c, d = map(int, input().split())

print(max(a, b, c, d))



# exercise 5
# Ekrana "Hello, Python!" yaz.
print("Hello, Python!")



# exercise 6
# Düzbucaqlı paralelepipedin səth sahəsini və həcmini tap.
a, b, c = map(int, input().split())

S = 2 * (a*b + b*c + a*c)
V = a * b * c

print(S, V)
