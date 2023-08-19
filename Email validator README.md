# cognifyz-task3 level 1
import re

regex = '^[a-z0-9]+[\._]?[a-z0-9]+[@]\w+[.]\w{2,3}$'


def check(email):
    if (re.search(regex, email)):
        print("Valid Email")
    else:
        print("Invalid Email")


if __name__ == '__main__':
    email = "prajwalkale17@gmail.com"
    check(email)

    email = "prajwal@c-sharpcorner.com"
    check(email)

    email = "praj8wal@gmail.com"
    check(email)
