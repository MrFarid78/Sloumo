class Iterable:
    def __init__(self, max_num):
        self.max_num = max_num

    def __iter__(self):
        for i in range(self.max_num):
            yield i

# Пример использования
for num in Iterable(5):
    print(num)
    
   ----------------------------
   
def calculate(func):
 def  eval(expression):
        try:
            result = eval(expression)
        except (SyntaxError, NameError, ZeroDivisionError):
            print("Ошибка: Неправильное выражение")
            return None
        except Exception as e:
            print(f"Ошибка: {e}")
            return None

        return result

    return calculate
