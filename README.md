# Zadanie_17.7.3
deposit = []
per_cent = {'TKБ': 5.6, 'CKБ': 5.9, 'BTБ': 4.28, 'CБEP': 4.0}
money = int(input("Введите сумму: "))
deposit.append(int(per_cent['TKБ'] * money / 100))
deposit.append(int(per_cent['CKБ'] * money / 100))
deposit.append(int(per_cent['BTБ'] * money / 100))
deposit.append(int(per_cent['CБEP'] * money / 100))
print(deposit)
print("Максимальная сумма, которую вы можете заработать:", max(deposit))
