import random

def find_magical_coin(K):
    consecutive_heads = 0
    found_magical_coin = False

    for attempt in range(1, K + 1):
        result = random.choice(["Heads", "Tails"])
        print(f"Attempt {attempt}: {result}")

        if result == "Heads":
            consecutive_heads += 1

            if consecutive_heads % 4 == 0:
                found_magical_coin = True
                break
        else:
            consecutive_heads = 0

    if found_magical_coin:
        print("Congratulations, you have found a magic coin!")
    else:
        print("Unfortunately, you didn't get a coin.")

try:
    K = int(input("How many times do you want to toss a coin: "))
    find_magical_coin(K)
except ValueError:
    print("Please enter a valid number of attempts.")

