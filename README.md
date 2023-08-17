# First_simpel_math_with_python
saldo_awal = 5000
deposit = input('berapa mau depositnya?')
saldo_total = int(saldo_awal) + int(deposit)
hutang = 50_000 # jadi deposit mesti sama atau lebih besar dari 45.000
sisa = saldo_total - hutang

if saldo_total >= 50_000:
    print('hutang lunas')
    print('sisa: ' + str(sisa))
else:
    print('masih kurang bro')
    print('ini kurangnya: ' + str(sisa))
