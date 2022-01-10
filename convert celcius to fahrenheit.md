def convert(c):
    f=(9/5)*c+32
    return (f)
while True:
    try:

            cel=float(input(f"enter the temperature:"))
            fah=convert(cel)
            print(f"Temperature in fahrenheit is {fah}")
            break
    except:
        print("enter the numeric value")
