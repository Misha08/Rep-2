# Hiii
That's new repository
``` html
  <html>
    <body>
      <p> Hello world! </p>
    </body>
</html>
```
Some wolf-facts 

:wolf: Wolf won't say the sh**, wolf will show it :point_up:

``` python
  print('I try to write in Python')
```
![голову дома забыл](https://user-images.githubusercontent.com/59179698/136330453-95a1ff3a-8889-46c8-9167-af2e33473e99.jpg)

Ok, shut down and start work

``` python
  arr = list()
count = 0
for _ in range(int(input())):
    write_arr = [str(x) for x in input().split()]
    integer = list()
    for j in write_arr:
        integer.append(int(j))
    arr.append(integer)
median_arr = list()
while count != len(arr):
    a_arr = list()
    arr[count].sort()
    if len(arr[count]) % 2 == 0:
        median_1 = arr[count][len(arr[count]) // 2]
        median_2 = arr[count][len(arr[count]) // 2 - 1]
        main_median = (median_1 + median_2) / 2
        count += 1
        a_arr.append(main_median)
        median_arr.append(main_median)
    else:
        main_median = arr[count][len(arr[count]) // 2]
        count += 1
        a_arr.append(main_median)
        median_arr.append(main_median)
    print(*a_arr, end=" ")
count = 0
b_arr = list()
for i in range(len(arr)):
    amax = 0
    bmax = 0
    for j in arr[i]:
        k = arr[i].count(j)
        if k > amax or k == amax and j < bmax:
            amax = k
            bmax = j
    b_arr.append(bmax)
print()
print(*b_arr, end=" ")
median_arr.sort()
main_median = 0
if len(median_arr) % 2 == 0:
    median_1 = median_arr[len(median_arr) // 2]
    median_2 = median_arr[len(median_arr) // 2 - 1]
    main_median = (median_1 + median_2) / 2
else:
    main_median = median_arr[len(median_arr) // 2]
print()
print(main_median)
b_arr.sort()
amax = 0
bmax = 0
for i in b_arr:
    k = b_arr.count(i)
    if k > amax or k == amax and i < bmax:
        amax = k
        bmax = i
print(int(bmax))
big_count = 0
big_arr = list()
for s in range(len(arr)):
    big_arr = big_arr + arr[s]
main_arr = big_arr
bmain_arr = main_arr
main_median = 0
main_arr.sort()
if len(main_arr) % 2 == 0:
    median_1 = main_arr[len(main_arr) // 2]
    median_2 = main_arr[len(main_arr) // 2 - 1]
    main_median = (median_1 + median_2) / 2
else:
    main_median = main_arr[len(main_arr) // 2]
print(int(main_median))
amax = 0
bmax = 0
for i in bmain_arr:
    k = bmain_arr.count(i)
    if k > amax or k == amax and i < bmax:
        amax = k
        bmax = i
print(int(bmax))
```
