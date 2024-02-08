def main():
    print("This program converts rupees to US dollars Sterling")
    print()

    rupees = eval(input("Enter amount in rupees: "))

    dollars = convert_to_dollars(rupees)

    print("That's" , dollars, " USD.")

convert_to_dollars = lambda rupees: rupees * 0.012

main()