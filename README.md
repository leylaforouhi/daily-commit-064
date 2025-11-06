def power_and_root(number, exponent, root_n):
    power_result = number ** exponent
    root_result = number ** (1 / root_n)
    return power_result, root_result

if __name__ == "__main__":
    num = 16
    exp = 2
    root_n = 4
    power_val, root_val = power_and_root(num, exp, root_n)
    print(f"{num}^{exp} = {power_val}")
    print(f"{root_n}th root of {num} = {root_val}")
