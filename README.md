# x-start-stop
x start stop


def find_positions(arr, x, start, stop):
    positions = []
    for i in range(start, stop):
        if arr[i] == x:
            positions.append(i)
    return positions

arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
x = 5
start = 0
stop = len(arr)
print(find_positions(arr, x, start, stop))

