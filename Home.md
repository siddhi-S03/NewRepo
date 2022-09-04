Welcome to the NewRepo wiki!

Todays Hackerrank question: 
 def plusminus(arr):
    pos=0
    neg=0
    zer=0
    for i in range(len(arr)):
        if arr[i] >= 1:
            pos += 1
        elif arr[i] <= -1:
            neg += 1
        elif arr[i] == 0:
            zer += 1
        
    print(str(round(pos/len(arr), 6)))
    print(str(round(neg/len(arr), 6)))
    print(str(round(zer/len(arr), 6)))
if __name__ == '__main__':
    n = int(input().strip())

    arr = list(map(int, input().rstrip().split()))
plusMinus(arr)