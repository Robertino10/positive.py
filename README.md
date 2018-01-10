# positive.py
def positive(a_list):

    answer = []

    for a in a_list:
        if a > 0:
            answer.append(a)

    return answer


print positive([1, -2, 0, 5, -5, 3, 3, 6])

values = [45, -67, 90, -56]
print positive(values)

all_negative = [-45, -67, -90, -56]
print positive(all_negative)

