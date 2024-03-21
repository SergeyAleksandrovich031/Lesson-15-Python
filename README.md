# Lesson-15-Python
Task 44
 В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца. Ваша задача перевести его в one hot вид. Сможете ли вы это сделать без get_dummies?

import random /n
lst = ['robot'] * 10 /n
lst += ['human'] * 10 /n
random.shuffle(lst) /n
data = pd.DataFrame({'whoAmI'lst}) /n
data.head() |
