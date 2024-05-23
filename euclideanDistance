import math

# 1. Noktaların Tanımlanması
points = [(1, 2), (4, 6), (7, 8), (2, 1)]

# 2. Öklid Mesafesi İçin Bir Fonksiyon Yazma
def euclideanDistance(point1, point2):
    x1, y1 = point1
    x2, y2 = point2
    distance = math.sqrt((x2 - x1) ** 2 + (y2 - y1) ** 2)
    return distance

# 3. Mesafelerin Hesaplanması
distances = []
num_points = len(points)

for i in range(num_points):
    for j in range(i + 1, num_points):
        dist = euclideanDistance(points[i], points[j])
        distances.append(dist)

# 4. Minimum Mesafenin Bulunması
min_distance = min(distances)
print("Minimum Öklid mesafesi:", min_distance)
