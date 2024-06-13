# Survival-detection

def calculate_duration(age):
    # Calculate the durations
    months = age * 12
    weeks = age * 52 
    days = age * 365    
    hours = days * 24
    minutes = hours * 60
    seconds = minutes * 60

    return months, weeks, days, hours, minutes, seconds

def main():
    # Input the age of the person
    age = 30
    print(f"The person's age is {age} years.\n")

    # Calculate the durations
    months, weeks, days, hours, minutes, seconds = calculate_duration(age)

    # Output the results
    print(f"The person lived for {months:.2f} months.")
    print(f"The person lived for {weeks:.2f} weeks.")
    print(f"The person lived for {days:.2f} days.")
    print(f"The person lived for {hours:.2f} hours.")
    print(f"The person lived for {minutes:.2f} minutes.")
    print(f"The person lived for {seconds:.2f} seconds.")

if __name__ == "__main__":
    main()
