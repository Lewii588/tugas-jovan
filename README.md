harga_asli = float(input("Masukkan harga barang: "))
persen_diskon = float(input("Masukkan persentase diskon (contoh: 20): "))


# potongan harga
potongan = harga_asli * (persen_diskon / 100)

harga_akhir = harga_asli - potongan

print("-" * 30)
print(f"Harga Asli          : Rp {harga_asli:,.2f}")
print(f"Diskon              : {persen_diskon}%")
print(f"Potongan Harga      : Rp {potongan:,.2f}")
print(f"Harga Setelah Diskon: Rp {harga_akhir:,.2f}")
print("-" * 30)
