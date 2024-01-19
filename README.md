# hour-menits-secend.PY
# `secend = int (input('enter secend ='))` is taking user input for the number of seconds and
# converting it to an integer using the `int()` function. The `input()` function prompts the user to
# enter a value, and the `int()` function converts that value to an integer. The entered value is then
# assigned to the variable `secend`.
secend = int (input('enter secend ='))
# hour= secend//3600
menits1 = secend //60
secend1 = secend % 60
h = menits1 // 60
menits2 = menits1 % 60
# The line `print('hour =', h, 'menits=', menits2, 'secend2=',secend1)` is printing the values of the
# variables `h`, `menits2`, and `secend1` along with some text. It will display the output in the
# format "hour = [value of h] menits = [value of menits2] secend2 = [value of secend1]".
print('hour =', h, 'menits=', menits2, 'secend2=',secend1)
