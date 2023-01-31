# 找出99999以内纯数字的profile。并且寻找空缺的
handles_num = ['{:0>5s}'.format(str(i)) for i in range(100000)]
# print(handles_num)
# handles = []
with open('registeredDigit.data', 'r') as f:
    lensData = [x.strip() for x in f.readlines()]

count = 0
for i in lensData:
    # handle = i.split(',')[1].strip()
    # profileID = i.split(',')[0]
    # print(handle, profileID)
    for j in handles_num:
        if i == j:
            print(i, 'is registered')
            count += 1
            handles_num.pop(handles_num.index(i))
            break
    # print(i, 'no match')
print(handles_num)
print(count)
